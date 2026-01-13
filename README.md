# FPDev FPC Releases

Pre-built FPC (Free Pascal Compiler) binary releases.

## Overview

This repository provides pre-built FPC binary packages for various platforms, ready to use without compilation.

## Available Versions

| Version | Linux x86_64 | Windows x86_64 | macOS x86_64 | macOS ARM64 |
|---------|--------------|----------------|--------------|-------------|
| 3.2.2   | -            | -              | -            | -           |
| 3.2.0   | -            | -              | -            | -           |

## Package Contents

Each FPC release package contains the complete FPC installation:

```
fpc-{version}-{platform}/
├── bin/
│   ├── fpc
│   ├── ppcx64
│   └── ...
├── lib/
│   └── fpc/
│       └── {version}/
│           ├── units/
│           │   └── {target}/
│           │       ├── rtl/
│           │       └── ...
│           └── ...
└── share/
    └── ...
```

## Usage

```bash
# Install FPC binary release
fpdev fpc install 3.2.2

# Or explicitly request binary installation
fpdev fpc install 3.2.2 --from-binary
```

## Mirrors

- **GitHub**: https://github.com/dtamade/fpdev-fpc
- **Gitee**: https://gitee.com/dtamade/fpdev-fpc (China)

## License

FPC is licensed under LGPL with linking exception.
