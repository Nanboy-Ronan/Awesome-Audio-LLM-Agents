# Awesome Audio LLMs & Voice Agents

> A curated list of **Audio LLMs, Speech LLMs, Voice Agents, and tools for building audio-native AI systems**.

>This repository collects research papers, models, frameworks, datasets, and projects related to **audio-language models and speech-based AI agents**.

## Table of Contents

- [Paper List](#paper-list)
  - [Surveys & Overviews](#surveys--overviews)
  - [Speech Foundation Models](#speech-foundation-models)
  - [Audio Language Models (Audio LLMs)](#audio-language-models-audio-llms)
  - [Speech-to-Speech and Voice Interaction](#speech-to-speech-and-voice-interaction)
  - [Voice Agents and Spoken Dialogue](#voice-agents-and-spoken-dialogue)
- [Benchmarks & Datasets](#benchmarks--datasets)
- [Tooling & Repos](#tooling--repos)
- [Related Awesome Lists](#related-awesome-lists)
- [Contributing](#contributing)
- [License](#license)

## Paper List

### Surveys & Overviews

- [Recent Advances in End-to-End Spoken Dialogue Systems](https://arxiv.org/abs/2104.03054) — arXiv (2021). Survey of modern spoken dialogue pipelines and end-to-end methods.
- [A Survey on Spoken Language Understanding: Recent Advances and New Frontiers](https://arxiv.org/abs/2103.03095) — arXiv (2021). Strong SLU overview covering intent, slot filling, and robust speech understanding.
- [A Survey on Audio-Visual Deep Learning for Speech and Language Processing](https://arxiv.org/abs/2001.09439) — arXiv (2020). Broader multimodal context for speech-language modeling.

### Speech Foundation Models

- [wav2vec 2.0: A Framework for Self-Supervised Learning of Speech Representations](https://arxiv.org/abs/2006.11477) — NeurIPS (2020). Landmark SSL speech pretraining method.
- [HuBERT: Self-Supervised Speech Representation Learning by Masked Prediction of Hidden Units](https://arxiv.org/abs/2106.07447) — IEEE/ACM TASLP (2021). Iterative pseudo-label learning for strong speech features.
- [Data2vec: A General Framework for Self-supervised Learning in Speech, Vision and Language](https://arxiv.org/abs/2202.03555) — ICML (2022). Unified SSL objective across modalities.
- [Whisper: Robust Speech Recognition via Large-Scale Weak Supervision](https://arxiv.org/abs/2212.04356) — arXiv (2022). Highly influential large-scale ASR model.
- [Universal Speech Model (USM): Scaling Automatic Speech Recognition Beyond 100 Languages](https://arxiv.org/abs/2303.01037) — arXiv (2023). Massive multilingual speech recognition model.
- [SeamlessM4T — Massively Multilingual and Multimodal Machine Translation](https://arxiv.org/abs/2308.11596) — arXiv (2023). Unified speech/text translation across many languages.

### Audio Language Models (Audio LLMs)

- [AudioLM: a Language Modeling Approach to Audio Generation](https://arxiv.org/abs/2209.03143) — arXiv (2022). Foundational language-model-style audio generation framework.
- [SPEAR-TTS: Language Models are Zero-Shot Text to Speech Synthesizers](https://arxiv.org/abs/2302.03540) — arXiv (2023). LLM-style TTS with in-context prompting.
- [VALL-E: Neural Codec Language Models are Zero-Shot Text to Speech Synthesizers](https://arxiv.org/abs/2301.02111) — arXiv (2023). Neural codec LM for zero-shot personalized TTS.
- [VALL-E X: Speak Foreign Languages with Your Own Voice](https://arxiv.org/abs/2303.03926) — arXiv (2023). Cross-lingual extension of neural codec TTS.
- [SpeechT5: Unified-Modal Encoder-Decoder Pre-Training for Spoken Language Processing](https://arxiv.org/abs/2110.07205) — ACL (2022). Unified framework for multiple speech-text tasks.
- [SpeechGPT: Empowering Large Language Models with Intrinsic Cross-Modal Conversational Abilities](https://arxiv.org/abs/2305.11000) — arXiv (2023). Early work integrating spoken/audio interaction into LLM chat.
- [SALMONN: Towards Generic Hearing Abilities for Large Language Models](https://arxiv.org/abs/2310.13289) — arXiv (2023). Audio-augmented LLM for speech/audio understanding.
- [Qwen-Audio: Advancing Universal Audio Understanding via Unified Large-Scale Audio-Language Models](https://arxiv.org/abs/2311.07919) — arXiv (2023). Large-scale audio-language model for diverse audio tasks.

### Speech-to-Speech and Voice Interaction

- [Translatotron: An End-to-End Speech-to-Speech Translation Model](https://arxiv.org/abs/1904.06037) — arXiv (2019). Early direct speech-to-speech translation architecture.
- [Translatotron 2: High-Quality Direct Speech-to-Speech Translation with Voice Preservation](https://arxiv.org/abs/2107.08661) — arXiv (2021). Stronger S2ST with speaker preservation.
- [YourTTS: Towards Zero-Shot Multi-Speaker TTS and Zero-Shot Voice Conversion for Everyone](https://arxiv.org/abs/2112.02418) — ICML (2022). Practical zero-shot voice cloning and conversion.
- [Voicebox: Text-Guided Multilingual Universal Speech Generation at Scale](https://arxiv.org/abs/2306.15687) — arXiv (2023). Large generative speech model with in-context editing.
- [Seamless: Multilingual Expressive and Streaming Speech Translation](https://arxiv.org/abs/2312.05187) — arXiv (2023). Family of models for expressive multilingual speech communication.

### Voice Agents and Spoken Dialogue

- [End-to-End Task-Completion Neural Dialogue Systems](https://arxiv.org/abs/1807.11125) — IJCNLP (2018). End-to-end task-oriented dialogue baseline.
- [TOD-BERT: Pre-trained Natural Language Understanding for Task-Oriented Dialogue](https://arxiv.org/abs/2004.06871) — EMNLP (2020). Widely used pretrained dialogue backbone.
- [Toolformer: Language Models Can Teach Themselves to Use Tools](https://arxiv.org/abs/2302.04761) — NeurIPS (2023). Core tool-use pattern relevant for voice agents.
- [ReAct: Synergizing Reasoning and Acting in Language Models](https://arxiv.org/abs/2210.03629) — ICLR (2023). Influential reasoning-plus-action loop for agent behavior.
- [WebRTC + LLM Voice Assistant Architecture (Open Source Reference)](https://github.com/livekit/agents) — LiveKit Agents (ongoing). Practical real-time voice-agent framework used in production systems.

## Benchmarks & Datasets

- [SUPERB: Speech processing Universal PERformance Benchmark](https://arxiv.org/abs/2105.01051) — arXiv (2021). Core benchmark suite for speech representation learning.
- [HEAR Benchmark](https://arxiv.org/abs/2203.03022) — NeurIPS Datasets and Benchmarks (2022). Holistic audio representation benchmark.
- [LibriSpeech](https://www.openslr.org/12) — standard ASR benchmark dataset.
- [Common Voice](https://commonvoice.mozilla.org/) — large multilingual open speech dataset.
- [MLS (Multilingual LibriSpeech)](https://arxiv.org/abs/2012.03411) — large-scale multilingual read speech corpus.

## Tooling & Repos

- [openai/whisper](https://github.com/openai/whisper) — Whisper inference and training code.
- [facebookresearch/fairseq](https://github.com/facebookresearch/fairseq) — includes wav2vec 2.0 and other speech foundations.
- [espnet/espnet](https://github.com/espnet/espnet) — end-to-end speech processing toolkit.
- [huggingface/transformers](https://github.com/huggingface/transformers) — broad ecosystem for speech and audio-language models.
- [livekit/agents](https://github.com/livekit/agents) — real-time voice AI agent framework.

## Related Awesome Lists

- [awesome-agents-in-medicine](https://github.com/Nanboy-Ronan/awesome-agents-in-medicine)

## Contributing

Contributions are welcome. PRs adding missing landmark papers, benchmarks, and production voice-agent stacks are encouraged.

## License

[CC BY-SA 4.0](http://creativecommons.org/licenses/by-sa/4.0/)
