# wrp-c

C implementation of the Web Routing Protocol

[![Apache V2 License](http://img.shields.io/badge/license-Apache%20V2-blue.svg)](LICENSE)
[![GitHub release](https://img.shields.io/github/release/rdkcentral/wrp-c.svg)](https://github.com/rdkcentral/wrp-c/releases)

## Origin

This repository is based on the original
[wrp-c](https://github.com/xmidt-org/wrp-c) source code
maintained under the xmidt-org organization. The code was copied into the
rdkcentral organization, where ongoing maintenance and development now take place.

- Original project: https://github.com/xmidt-org/wrp-c
- Current repository: https://github.com/rdkcentral/wrp-c

# Building and Testing Instructions

```
mkdir build
cd build
cmake ..
make
make test
make coverage
firefox index.html
```

# Coding Formatter Settings

Please format pull requests using the following command to keep the style consistent.

```
astyle -A10 -S -f -U -p -D -c -xC90 -xL
```
