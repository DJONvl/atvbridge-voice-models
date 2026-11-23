# atvbridge-voice-models

ONNX ASR models and the Android app for the ATV2ZESP voice service.

## Install

1. Download `atvbridge-voice-debug.apk` from the [models-v1 release](https://github.com/DJONvl/atvbridge-voice-models/releases/tag/models-v1).
2. Install and open the app. On first launch it downloads the selected ASR model automatically over Wi-Fi/Ethernet (SHA-256 verified, resumable).

Release assets:

- `atvbridge-voice-debug.apk` — app (debug signed)
- `gigaam.zip` — GigaAM v3 CTC (quality)
- `zipformer.zip` — zipformer-ru transducer (speed)
- `streaming.zip` — streaming zipformer for VAD cache
- `vosk.zip` — Vosk full Russian model

The app downloads these at first launch (`assets/models.json`, SHA-256 verified).
