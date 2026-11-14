# Third-party notices

HotKey is built on the open-source projects below. Thank you to their authors.
The full texts also ship inside the installer (`THIRD_PARTY.txt`).

## Included in the installer

| Component | What it does in HotKey | License |
|---|---|---|
| [Keyboop](https://github.com/iffuno/keyboop) — © 2026 Keyboop contributors | Layout detection rules and dictionaries, ported to C# | MIT |
| [keyswitcher](https://github.com/graninilya/keyswitcher) — © 2026 Ilya Granin | Dictionaries and letter statistics | MIT |
| [Mozilla Common Voice](https://github.com/common-voice/common-voice) — Uzbek sentences | Uzbek word list for Latin ↔ Cyrillic | CC0 1.0 |
| [whisper.cpp](https://github.com/ggml-org/whisper.cpp) — © 2023-2026 The ggml authors | Speech recognition | MIT |
| [Whisper.net](https://github.com/sandrohanea/whisper.net) — © 2024 sandrohanea | whisper.cpp for .NET | MIT |
| [llama.cpp](https://github.com/ggml-org/llama.cpp) — © 2023-2026 The ggml authors | Local language model server (grammar and translation) | MIT |
| [NAudio](https://github.com/naudio/NAudio) — © Mark Heath | Microphone capture | MIT |
| [ONNX Runtime](https://github.com/microsoft/onnxruntime) — © Microsoft Corporation | Light translator engine | MIT |
| [.NET 10](https://github.com/dotnet/runtime) — © .NET Foundation and Contributors | Runtime, bundled | MIT |
| LLVM OpenMP runtime (`libomp.dll`, ships with llama.cpp) | Threads for llama.cpp | Apache 2.0 with LLVM Exceptions |
| Gilroy typeface — Radomir Tinkov | Interface font | Its own license |

## Downloaded separately, on request

Models are not part of the installer. HotKey downloads them only when you press **Download**.

| Model | Used for | License |
|---|---|---|
| [Whisper](https://huggingface.co/ggerganov/whisper.cpp) (OpenAI), ggml | Voice typing | MIT |
| [Kotib uzbek_stt_v1](https://huggingface.co/Kotib/uzbek_stt_v1) (Kotib AI, Rubai Team), converted to ggml q5_0 | Uzbek voice typing | Apache 2.0 |
| [Qwen3.5 9B / 4B](https://huggingface.co/Qwen) (Alibaba Cloud, Qwen team), GGUF | Grammar and translation | Apache 2.0 |
| [Opus-MT ru-en / en-ru](https://huggingface.co/Helsinki-NLP) (Helsinki-NLP, University of Helsinki), ONNX by Xenova | Light translator | CC-BY 4.0 |

## MIT License

Applies to the MIT components above, with their copyright holders.

```
Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
