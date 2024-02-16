# JDemetra+ v3 latest snapshot

This repository contains the **latest binary snapshot of [JDemetra+ v3](https://github.com/jdemetra/jd3-main)**.  
Each snapshot is created automatically every night.

_Note that this snapshot is available for test only and should not be used in production._

## Requirements

JDemetra+ v3 runs on any operating system that supports **Java 17 or later** such as Microsoft **Windows**, **Solaris** OS, Apple **macOS**, **Ubuntu** and other various **Linux** distributions.

## Installation

### ☕️ Bundled Java runtime

This binary provides its own Java runtime.

1. **Download** the [platform-specific package](https://github.com/nbbrd/jdemetra-app-snapshot/releases) (`jdemetra-standalone-VERSION-PLATFORM.zip`)
    
    | `PLATFORM`  | Intel            | Arm             |
    |:-----------:|------------------|-----------------|
    |  **MacOS**  | `mac-x86_64`     | `mac-aarch64`   |
    |  **Linux**  | `linux-x86_64`   | `linux-aarch64` |
    | **Windows** | `windows-x86_64` |                 |

2. **Extract** it to any folder on your system (i.e. `DEMETRA_PATH`)
3. **Run** the executable file located in the `DEMETRA_PATH/bin` directory

### 🌟 Universal

This binary requires an external Java runtime.

1. **Install** [Java version 17 or later](https://whichjdk.com/)
2. **Download** the [platform-independent package](https://github.com/nbbrd/jdemetra-app-snapshot/releases) (`jdemetra-VERSION.zip`)
3. **Extract** it to any folder on your system (i.e. `DEMETRA_PATH`)
4. **Run** the executable file located in the `DEMETRA_PATH/bin` directory
