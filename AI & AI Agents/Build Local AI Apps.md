# Build Local AI Apps

The supplied post recommends these repositories for running models locally and building self-hosted AI apps. New and refreshed counts below were checked on **23 October 2026**; older entries retain their earlier check dates. Counts marked `~` are rounded as displayed by GitHub.

| Repository | Stars | License type | Why it exists |
|---|---:|---|---|
| [Ollama](https://github.com/ollama/ollama) | 182,582 | MIT License | Download and run language models locally, then connect them to apps and agents. |
| [Open WebUI](https://github.com/open-webui/open-webui) | ~154.2k | Mixed: Open WebUI License with required branding preservation; previous contributions retain original licenses ([license](https://github.com/open-webui/open-webui/blob/main/LICENSE), [history](https://github.com/open-webui/open-webui/blob/main/LICENSE_HISTORY)) | Provide a self-hosted interface for local and cloud models, with offline operation and support for multiple backends. |
| [llama.cpp](https://github.com/ggml-org/llama.cpp) | ~130.7k | MIT License | Run large language model inference efficiently in C/C++ across a range of hardware. |
| [LocalAI](https://github.com/mudler/LocalAI) | ~49.5k | MIT License | Serve local models for text, vision, voice, image, and video through compatible APIs on varied hardware. |
| [Jan](https://github.com/janhq/jan) | ~44.9k | Apache License 2.0 | Offer a desktop ChatGPT alternative that downloads and runs models offline. |
| [LibreChat](https://github.com/LibreChat-AI/LibreChat) | 45.9k (18 Oct 2026) | MIT License | Provide a self-hosted chat interface that connects multiple AI providers and models. |

## Voice and speech tools

| Repository | Stars | License type | Why it exists |
|---|---:|---|---|
| [VoiceStudio](https://github.com/debpalash/VoiceStudio) | 82,797 (23 Oct 2026) | GNU Affero General Public License v3.0 (AGPL-3.0); model weights and third-party assets retain their own terms ([license notice](https://github.com/debpalash/VoiceStudio/blob/main/LICENSE-NOTICE.md)) | Provide a local voice studio for voice cloning, voice design, dubbing, dictation, transcription, and audiobook creation. |
| [FluidVoice](https://github.com/altic-dev/FluidVoice) | 12,102 (14 Oct 2026) | GNU General Public License v3.0 (GPL-3.0) | Provide an open-source macOS dictation app with on-device AI speech recognition and enhancement. |
| [OpenBMB/VoxCPM](https://github.com/OpenBMB/VoxCPM) | 39.5k (18 Oct 2026) | Apache License 2.0 | Generate multilingual speech and support creative voice design and voice cloning with a tokenizer-free text-to-speech model. |
| [OpenWhispr](https://github.com/OpenWhispr/openwhispr) | 9,824 (23 Oct 2026) | MIT License | Provide a privacy-first, cross-platform voice-to-text dictation app with local and cloud speech models. |

The supplied post frames these as ways to get more local control and reduce reliance on cloud services. Actual privacy and offline behavior depend on how each app is configured and which models or connected services are used.

## Route requests to model APIs

[BerriAI/litellm](https://github.com/BerriAI/litellm) had **60,903 stars** on 10 October 2026. It provides a unified gateway for calling many LLM APIs. Licensing is mixed: MIT terms apply outside `/enterprise`; the BerriAI Enterprise License applies within it ([MIT terms](https://github.com/BerriAI/litellm/blob/main/LICENSE), [Enterprise terms](https://github.com/BerriAI/litellm/blob/main/enterprise/LICENSE.md)).

For the project-wide ranking, see [GitHub Repositories Ranked by Stars](../GitHub%20Repositories%20Ranked%20by%20Stars.md).
