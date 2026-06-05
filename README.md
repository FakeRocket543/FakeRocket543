# Hey, I'm Félix

I build tools at the intersection of **NLP × edge computing × news media**.

My code solves one problem: **ensuring factual accuracy when content crosses language boundaries and hardware platforms.**

---

### 🔍 News NLP Pipeline

Deterministic QA for multilingual news — no AI, no hallucination, pure arithmetic.

- [**numlint**](https://github.com/FakeRocket543/numlint) — Catches magnitude errors, currency mismatches, and unit conversion bugs in translated text. 28 languages.
- [**ner-mundo**](https://github.com/FakeRocket543/ner-mundo) — Cross-lingual named entity resolution. Merges partial names, translations, and coreferences into one canonical entry.
- [**Anseropolis**](https://github.com/FakeRocket543/anseropolis) — Linguistic fingerprinting × manipulation detection.
- [**TWGY**](https://github.com/FakeRocket543/TWGY) — ASR correction for Taiwan Mandarin accents.

### 🤖 Edge NLP on ARM

Production NLP on RK3588S ($50 ARM board).

- [**GLiNER-Forge**](https://github.com/FakeRocket543/GLiNER-Forge) — Zero-shot NER across macOS (MLX), NVIDIA (CUDA), and RK3588S (ONNX INT8). Includes a fp16 quantization bug fix.
- [**rk-stantaz**](https://github.com/FakeRocket543/rk-stantaz) — Stanza NLP on RK3588S: 3.66× speedup. Found that RK3588S NPU is *slower* than CPU for LSTM workloads.
- [**rk-clip**](https://github.com/FakeRocket543/rk-clip) — Traditional Chinese NLP (CKIP) on RK3588S: 3.32× total speedup.

### 🍎 Apple Silicon NLP

- [**ckip-mlx**](https://github.com/FakeRocket543/ckip-mlx) — CKIP BERT on Apple MLX. WS/POS/NER for Traditional Chinese.
- [**ckip-coreml**](https://github.com/FakeRocket543/ckip-coreml) — Same, compiled for iOS/macOS via Core ML.
- [**mlx-gemma4**](https://github.com/FakeRocket543/mlx-gemma4) — MLX quantization for Google Gemma 4 with PLE-safe calibration.

### 🛠️ Tools

- [**yabomish**](https://github.com/FakeRocket543/yabomish) — A CJK input method for macOS, written in Swift.
- [**webplow**](https://github.com/FakeRocket543/webplow) — WebP conversion API in Go.
- [**glitchtip-mcp**](https://github.com/FakeRocket543/glitchtip-mcp) — MCP server for GlitchTip error tracking.
- [**oh-my-kiro**](https://github.com/FakeRocket543/oh-my-kiro) — Behavioral tuning for Kiro CLI.
- [**inff.cc**](https://inff.cc) — A news aggregator I operate.

---

Mandarin · English · French
