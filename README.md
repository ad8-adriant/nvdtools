![Tests](https://github.com/ad8-adriant/nvdtools/actions/workflows/tests.yaml/badge.svg)

# NVD Tools

A cut-down fork of [github.com/facebookincubator/nvdtools](https://github.com/facebookincubator/nvdtools) that provides only CPE and CVSS parsing support.

## Libraries

### cvss2

Implementation of [CVSS v2 specification](https://www.first.org/cvss/v2/guide) which provides functions for serializing and deserializing vectors as well as score calculation.

### cvss3

Implementation of [CVSS v3 specification](https://www.first.org/cvss/specification-document) which provides functions for serializing and deserializing vectors as well as score calculation.

### wfn

Implementation of [CPE v2.3 specification](https://cpe.mitre.org/specification/) which provides functions for matching WFNs, and serializing and deserializing URI and FSB formatted names.

## License

NVD Tools is licensed under Apache License, Version 2.0, as found in the [LICENSE](LICENSE) file.
