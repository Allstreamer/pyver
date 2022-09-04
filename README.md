# PyVer

[![License](https://img.shields.io/badge/license-MIT-blue?style=flat-square)](LICENSE-MIT) [![🧪 Tests](https://github.com/Allstreamer/pyver/actions/workflows/tests.yml/badge.svg)](https://github.com/Allstreamer/pyver/actions/workflows/tests.yml) [![🖋  Check linting](https://github.com/Allstreamer/pyver/actions/workflows/lint.yml/badge.svg)](https://github.com/Allstreamer/pyver/actions/workflows/lint.yml) [![🔨 Build](https://github.com/Allstreamer/pyver/actions/workflows/build.yml/badge.svg)](https://github.com/Allstreamer/pyver/actions/workflows/build.yml) [![📦 Package](https://github.com/Allstreamer/pyver/actions/workflows/package.yml/badge.svg)](https://github.com/Allstreamer/pyver/actions/workflows/package.yml) [![📄 Build docs](https://github.com/Allstreamer/pyver/actions/workflows/docs.yml/badge.svg)](https://github.com/Allstreamer/pyver/actions/workflows/docs.yml) [![👔 Check formatting](https://github.com/Allstreamer/pyver/actions/workflows/format.yml/badge.svg)](https://github.com/Allstreamer/pyver/actions/workflows/format.yml)
<!-- {::ignore rule="MD013" relative_line="-1"} -->

> **Python PEP-440 Version Parser**

This package allows for parsing Python [PEP-440](https://peps.python.org/pep-0440/) version numbers and for comparisons between [PEP-440](https://peps.python.org/pep-0440/) version numbers.

## Usage

```Toml
[dependencies]
pyver = "0"
```

```Rust
use pyver::PackageVersion;

let a = PackageVersion::new("v1.0a2.dev456").unwrap();
let b = PackageVersion::new("v1.0a2.dev457").unwrap();

assert_eq!(a < b, true);
```

## Contribution

For now Contributions will be quite loose.
