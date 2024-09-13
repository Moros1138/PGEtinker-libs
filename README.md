# PGEtinker Libraries

This repository contains the support library files used in PGEtinker and PGEtinker-language-server. It provides the following libraries:

* olcPixelGameEngine, extensions, and utilities from the official repository for the following versions.
    * v2.23
    * v2.24
    * v2.25
    * v2.26
    * v2.27
* miniaudio
    * v0.11.21
* olcPGEX_Gamepad
    * latest git commit
* olcPGEX_MiniAudio
    * v1.5
    * v1.6
    * v1.7
* olcSoundWaveEngine
    * v0.02

# Build Notes

```bash
bash build-libs.sh
```

Building this repo expects emscripten to be installed at:

```bash
/opt/emsdk
```

Using the version **3.1.56**




# Deployment Notes

PGEtinker and PGEtinker-language-server expect this repo to be found at:

```bash
/opt/PGEtinker-libs
```

