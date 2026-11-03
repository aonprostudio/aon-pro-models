# AON Pro Studio — model files

Model files downloaded by the AON Pro Studio app. Not meant to be used directly.

## qwen3-tts-clone-v1 (release)

Used by the app's local voice cloning feature.

| File | Size | SHA-256 |
|---|---|---|
| `cp_step_int4.onnx` | 49,284,681 bytes | `7efb8a94aa27157ceb21a0e6a014255bab43a53f32f31a745db4ec51ded50cfe` |
| `cp_heads.npz` | 125,829,650 bytes | `f0872ea7e020a91c6c2273ae71db96c0b27b5f95f354809da743959be94a0f35` |

These are a modified form of the `talker.code_predictor` weights of
[Qwen/Qwen3-TTS-12Hz-0.6B-Base](https://huggingface.co/Qwen/Qwen3-TTS-12Hz-0.6B-Base)
(revision `5d83992436eae1d760afd27aff78a71d676296fc`), licensed under the Apache License 2.0.
See [NOTICE](NOTICE) for what was changed. The rest of the model is downloaded unchanged from
[onnx-community/Qwen3-TTS-12Hz-0.6B-Base](https://huggingface.co/onnx-community/Qwen3-TTS-12Hz-0.6B-Base)
and the Qwen repository.

## Use

Only clone your own voice, or a voice whose owner has given you permission. Do not use cloned voices to
impersonate people, defraud, or spread false information, and disclose AI-generated audio when you publish it.

## License

Apache License 2.0 — see [LICENSE](LICENSE).
