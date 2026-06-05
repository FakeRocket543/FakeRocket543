# Hi, I'm Félix Lin (林志祥)

Journalist, educator, and toolmaker at the intersection of **news media × NLP × edge computing**.

I teach journalism at [Shih Hsin University](https://www.shu.edu.tw/) and produce data-driven content at [Economic Daily News](https://money.udn.com/). My code solves problems I encounter in the newsroom — and then I optimize it to run on $50 ARM boards.

---

### 🔍 What I Build

**News NLP Pipeline** — Deterministic QA for multilingual news content

- [**numlint**](https://github.com/FakeRocket543/numlint) — Catches magnitude errors, currency mismatches, and unit conversion bugs in translated text. 28 languages, zero AI, pure arithmetic.
- [**ner-mundo**](https://github.com/FakeRocket543/ner-mundo) — Cross-lingual named entity resolution. Merges "Macron", "Emmanuel Macron", "le président français", and "法國總統馬克宏" into one entry before the LLM sees the text.
- [**Anseropolis**](https://github.com/FakeRocket543/anseropolis) — Linguistic fingerprinting × manipulation detection for Chinese text.
- [**TWGY**](https://github.com/FakeRocket543/TWGY) — ASR correction for Taiwan Mandarin accents.

**Edge NLP on ARM** — Production NLP on RK3588S (NanoPi M6)

- [**GLiNER-Forge**](https://github.com/FakeRocket543/GLiNER-Forge) — Zero-shot NER across macOS (MLX), NVIDIA (CUDA), and RK3588S (ONNX INT8). Includes a fp16 quantization bug fix that affects the entire ONNX ecosystem.
- [**rk-stantaz**](https://github.com/FakeRocket543/rk-stantaz) — Stanza NLP on RK3588S: 3.66× speedup via ONNX Runtime. Found that RK3588S NPU is *slower* than CPU for LSTM workloads.
- [**rk-clip**](https://github.com/FakeRocket543/rk-clip) — CKIP (Traditional Chinese NLP) on RK3588S: 3.32× total speedup.

**Apple Silicon NLP**

- [**ckip-mlx**](https://github.com/FakeRocket543/ckip-mlx) — CKIP BERT on Apple MLX. WS/POS/NER for Traditional Chinese.
- [**ckip-coreml**](https://github.com/FakeRocket543/ckip-coreml) — Same, but compiled for iOS/macOS via Core ML.
- [**mlx-gemma4**](https://github.com/FakeRocket543/mlx-gemma4) — MLX quantization for Google Gemma 4 with PLE-safe calibration.

**Tools & Infrastructure**

- [**inff.cc**](https://inff.cc) — FastAPI SSR news aggregator I built and operate. Nginx + PostgreSQL + 60s edge cache.
- [**yabomish**](https://github.com/FakeRocket543/yabomish) — Boshiamy (嘸蝦米) input method for macOS, written in Swift. Because the existing options weren't good enough.
- [**webplow**](https://github.com/FakeRocket543/webplow) — WebP conversion API in Go, backed by imgproxy.
- [**glitchtip-mcp**](https://github.com/FakeRocket543/glitchtip-mcp) — MCP server for GlitchTip error tracking. Query production errors from your AI assistant.
- [**oh-my-kiro**](https://github.com/FakeRocket543/oh-my-kiro) — Behavioral tuning layer for Kiro CLI. Three execution modes: Direct, Interview, and Ralph (structured persistence).

---

### 🧭 Theme

Everything I build traces back to one question: **How do you ensure factual accuracy when content crosses language boundaries and hardware platforms?**

The answer turns out to require:
- Deterministic verification (numlint, ner-mundo)
- Models that run anywhere from cloud to ARM SBCs (GLiNER-Forge, rk-stantaz)
- Tools that respect the user's language and input method (yabomish, ckip-mlx)

---

### 🗣️ Languages

Mandarin (native), English, French. Code in Python, Swift, Go, JavaScript. NLP in 28 languages.

---

### 📫

- [felixl.in](https://felixl.in) · [cv.felixl.in](https://cv.felixl.in)
- [inff.cc](https://inff.cc)
