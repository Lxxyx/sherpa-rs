# lxxyx-sherpa-rs

[![Crates](https://img.shields.io/crates/v/lxxyx-sherpa-rs?logo=rust)](https://crates.io/crates/lxxyx-sherpa-rs/)
[![License](https://img.shields.io/github/license/Lxxyx/sherpa-rs?color=00aaaa&logo=license)](https://github.com/Lxxyx/sherpa-rs/blob/main/LICENSE)

Rust bindings to [sherpa-onnx](https://github.com/k2-fsa/sherpa-onnx)

> **Note**: This is a fork of [thewh1teagle/sherpa-rs](https://github.com/thewh1teagle/sherpa-rs) with updates to sherpa-onnx v1.12.23

## Features

- Spoken language detection
- Speaker embedding (labeling)
- Speaker diarization
- Speech to text
- Text to speech
- Text punctuation
- Voice activity detection
- Audio tagging
- Keyword spotting

## Supported Platforms

- Windows
- Linux
- macOS
- Android
- IOS

## Install

```console
cargo add lxxyx-sherpa-rs
```

## Build

Please see [BUILDING.md](BUILDING.md).

## Feature flags

- `cuda`: enable CUDA support
- `directml`: enable DirectML support
- `tts`: enable TTS
- `download-binaries`: use prebuilt sherpa-onnx libraries for faster builds. cached.
- `static`: use static sherpa-onnx libraries and link them statically.
- `sys`: expose raw c bindings (sys crate)

## Documentation

For the documentation on `lxxyx_sherpa_rs`, please visit [docs.rs/lxxyx-sherpa-rs](https://docs.rs/lxxyx-sherpa-rs/latest/lxxyx_sherpa_rs).

For documentation on `sherpa-onnx`, refer to the [sherpa/intro.html](https://k2-fsa.github.io/sherpa/intro.html).

## Examples

See [examples](examples)

## Models

All pretrained models available at [sherpa/onnx/pretrained_models](https://k2-fsa.github.io/sherpa/onnx/pretrained_models/index.html)
