# Awesome Audio LLMs & Voice Agents

> A curated academic list of audio language models, speech language models, voice agents, and audio-native agent systems.

## Table of Contents

- [Awesome Audio LLMs & Voice Agents Paper List :page_with_curl:](#paper-list)
  - [Surveys & Perspectives](#surveys--perspectives)
  - [Speech Foundation Models](#speech-foundation-models)
  - [Audio Language Models](#audio-language-models)
  - [Speech-to-Speech & Real-Time Voice Interaction](#speech-to-speech--real-time-voice-interaction)
  - [Voice Agents & Spoken Dialogue](#voice-agents--spoken-dialogue)
  - [Others](#others)
- [Benchmarks :fire:](#benchmarks)
- [Datasets :card_file_box:](#datasets)
- [Toolboxes :toolbox:](#toolboxes)
- [Related Awesome Lists :astonished:](#related-awesome-lists)
- [Contributing :wink:](#contributing)
- [License](#license)

## Paper List

### Surveys & Perspectives

- [Recent Advances in Speech Language Models: A Survey](https://aclanthology.org/2025.findings-acl.82/) — Findings of ACL (2025). A current survey on speech language models, training recipes, and open problems for spoken interaction.
- [Spoken Conversational Agents with Large Language Models](https://arxiv.org/abs/2512.02593) — EMNLP Tutorial (2025). Tutorial-style overview of LLM-based spoken agents, including cascaded and speech-to-speech system design.
- [Towards Holistic Evaluation of Large Audio-Language Models: A Comprehensive Survey](https://arxiv.org/abs/2505.15957) — EMNLP (2025). Organizes evaluation dimensions for modern audio-language models and benchmarks.
- [Audio-Language Models for Audio-Centric Tasks: A Survey](https://arxiv.org/abs/2501.15177) — arXiv (2025). Reviews audio-language modeling for understanding, reasoning, and generation across speech and general audio.
- [Recent Advances in End-to-End Spoken Dialogue Systems](https://arxiv.org/abs/2104.03054) — arXiv (2021). Useful background survey for spoken dialogue pipelines and end-to-end SDS.

### Speech Foundation Models

- [wav2vec 2.0: A Framework for Self-Supervised Learning of Speech Representations](https://arxiv.org/abs/2006.11477) — NeurIPS (2020). Landmark self-supervised speech pretraining method.
- [HuBERT: Self-Supervised Speech Representation Learning by Masked Prediction of Hidden Units](https://arxiv.org/abs/2106.07447) — IEEE/ACM TASLP (2021). Strong masked-prediction speech representation learner.
- [Data2vec: A General Framework for Self-supervised Learning in Speech, Vision and Language](https://arxiv.org/abs/2202.03555) — ICML (2022). Unified self-supervised objective across modalities.
- [Whisper: Robust Speech Recognition via Large-Scale Weak Supervision](https://arxiv.org/abs/2212.04356) — arXiv (2022). Widely used large-scale ASR foundation model.
- [Universal Speech Model (USM): Scaling Automatic Speech Recognition Beyond 100 Languages](https://arxiv.org/abs/2303.01037) — arXiv (2023). Multilingual speech recognition at very large scale.
- [SeamlessM4T: Massively Multilingual and Multimodal Machine Translation](https://arxiv.org/abs/2308.11596) — arXiv (2023). Unified text and speech translation stack.
- [Scaling Analysis of Interleaved Speech-Text Language Models](https://arxiv.org/abs/2504.02398) — COLM (2025). Studies scaling laws and design tradeoffs for interleaved speech-text modeling.

### Audio Language Models

- [AudioLM: a Language Modeling Approach to Audio Generation](https://arxiv.org/abs/2209.03143) — arXiv (2022). Foundational language-model-style audio generation framework.
- [SpeechT5: Unified-Modal Encoder-Decoder Pre-Training for Spoken Language Processing](https://arxiv.org/abs/2110.07205) — ACL (2022). Unified encoder-decoder model for speech and text tasks.
- [SpeechGPT: Empowering Large Language Models with Intrinsic Cross-Modal Conversational Abilities](https://arxiv.org/abs/2305.11000) — arXiv (2023). Early speech-augmented LLM for spoken conversation.
- [SALMONN: Towards Generic Hearing Abilities for Large Language Models](https://arxiv.org/abs/2310.13289) — arXiv (2023). General hearing-oriented audio-LLM for speech and non-speech audio.
- [Qwen-Audio: Advancing Universal Audio Understanding via Unified Large-Scale Audio-Language Models](https://arxiv.org/abs/2311.07919) — arXiv (2023). General-purpose audio-language model covering diverse understanding tasks.
- [Audio Flamingo 2: An Audio-Language Model with Long-Audio Understanding and Expert Reasoning Abilities](https://arxiv.org/abs/2503.03983) — ICML (2025). Improves long-audio understanding and expert-style reasoning.
- [Mellow: a Small Audio Language Model for Reasoning](https://arxiv.org/abs/2503.08540) — arXiv (2025). Compact audio-language model focused on reasoning rather than pure transcription.
- [Qwen2.5-Omni Technical Report](https://arxiv.org/abs/2503.20215) — arXiv (2025). Native multimodal model with audio understanding and real-time interaction support.
- [DIFFA-2: A Practical Diffusion Large Language Model for General Audio Understanding](https://arxiv.org/abs/2601.23161) — arXiv (2026). Diffusion-based audio language model that improves general audio understanding with semantic and acoustic adapters.
- [UniAudio 2.0: A Unified Audio Language Model with Text-Aligned Factorized Audio Tokenization](https://arxiv.org/abs/2602.04683) — arXiv (2026). Introduces ReasoningCodec and a unified text-audio autoregressive model with strong few-shot and zero-shot generalization.

### Speech-to-Speech & Real-Time Voice Interaction

- [Translatotron 2: High-Quality Direct Speech-to-Speech Translation with Voice Preservation](https://arxiv.org/abs/2107.08661) — arXiv (2021). Strong direct speech-to-speech translation baseline with speaker preservation.
- [Moshi: a speech-text foundation model for real-time dialogue](https://arxiv.org/abs/2410.00037) — arXiv (2024). Full-duplex speech-text model for low-latency spoken dialogue.
- [Freeze-Omni: A Smart and Low Latency Speech-to-speech Dialogue Model with Frozen LLM](https://arxiv.org/abs/2411.00774) — arXiv (2024). Speech-to-speech dialogue system that reuses a frozen text LLM core.
- [Mini-Omni2: Towards Open-source GPT-4o with Vision, Speech and Duplex Capabilities](https://arxiv.org/abs/2410.11190) — arXiv (2024). Open multimodal duplex system for realtime speech and vision interaction.
- [GLM-4-Voice: Towards Intelligent and Human-Like End-to-End Spoken Chatbot](https://arxiv.org/abs/2412.02612) — arXiv (2024). End-to-end spoken chatbot focused on natural turn-taking and expressive response.
- [VITA-Audio: Fast Interleaved Cross-Modal Token Generation for Efficient Large Speech-Language Model](https://arxiv.org/abs/2505.03739) — arXiv (2025). Efficient large speech-language model for low-latency multimodal interaction.
- [LLMVoX: Autoregressive Streaming Text-to-Speech Model for Any LLM](https://arxiv.org/abs/2503.04724) — Findings of ACL (2025). Plug-and-play streaming TTS system that preserves the base LLM and lowers speech latency.

### Voice Agents & Spoken Dialogue

- [End-to-End Task-Completion Neural Dialogue Systems](https://arxiv.org/abs/1807.11125) — IJCNLP (2018). Early end-to-end task-oriented dialogue baseline.
- [TOD-BERT: Pre-trained Natural Language Understanding for Task-Oriented Dialogue](https://arxiv.org/abs/2004.06871) — EMNLP (2020). Widely used pretrained dialogue backbone.
- [Toolformer: Language Models Can Teach Themselves to Use Tools](https://arxiv.org/abs/2302.04761) — NeurIPS (2023). Core tool-use pattern that transfers directly to voice agents.
- [ReAct: Synergizing Reasoning and Acting in Language Models](https://arxiv.org/abs/2210.03629) — ICLR (2023). Foundational reasoning-plus-action loop for agent behavior.
- [AURA: Agent for Understanding, Reasoning, and Automated Tool Use in Voice-Driven Tasks](https://arxiv.org/abs/2506.23049) — arXiv (2025). Speech-native assistant for multi-turn tool use, task completion, and realtime voice interaction.

### Others

- [SPEAR-TTS: Language Models are Zero-Shot Text to Speech Synthesizers](https://arxiv.org/abs/2302.03540) — arXiv (2023). LLM-style text-to-speech with in-context prompting.
- [VALL-E: Neural Codec Language Models are Zero-Shot Text to Speech Synthesizers](https://arxiv.org/abs/2301.02111) — arXiv (2023). Neural codec LM for zero-shot personalized TTS.
- [Voicebox: Text-Guided Multilingual Universal Speech Generation at Scale](https://arxiv.org/abs/2306.15687) — arXiv (2023). Large generative speech model with editing and in-context control.
- [Audio Language Model for Deepfake Detection Grounded in Acoustic Chain-of-Thought](https://arxiv.org/abs/2603.28021) — arXiv (2026). Proposes CoLMbo-DF, an interpretable audio language model for deepfake speech detection with acoustic chain-of-thought supervision.

## Benchmarks :fire:

- [VoiceBench: Benchmarking LLM-Based Spoken Language Models](https://arxiv.org/abs/2410.17196) — arXiv (2024). Benchmarks spoken language models on speech instruction following and spoken interaction tasks.
- [AIR-Bench: Benchmarking Large Audio-Language Models via Generative Comprehension](https://arxiv.org/abs/2402.07729) — arXiv (2024). Audio-language benchmark focused on generative comprehension across varied audio tasks.
- [AudioBench: A Universal Benchmark for Audio Large Language Models](https://aclanthology.org/2025.naacl-long.448/) — NAACL (2025). Broad benchmark spanning speech, sound, music, and reasoning.
- [MMAU: A Massive Multi-Task Audio Understanding and Reasoning Benchmark](https://arxiv.org/abs/2410.19168) — ICLR (2025). Large multitask benchmark for audio understanding and reasoning.
- [AudioMarathon: A Comprehensive Benchmark for Long-Context Audio Understanding and Efficiency in Audio LLMs](https://arxiv.org/abs/2510.07293) — arXiv (2025). Long-context benchmark for realistic long-form audio understanding and efficiency.
- [VoiceAssistant-Eval: Benchmarking AI Assistants across Listening, Speaking, and Viewing](https://arxiv.org/abs/2509.22651) — arXiv (2025). Broad benchmark for next-generation multimodal voice assistants.
- [MAEB: Massive Audio Embedding Benchmark](https://arxiv.org/abs/2602.16008) — arXiv (2026). Large-scale benchmark spanning 30 tasks across speech, music, environmental sounds, and cross-modal audio-text reasoning in 100+ languages.

## Datasets :card_file_box:

- [LibriSpeech](https://www.openslr.org/12) — Standard ASR benchmark dataset.
- [Common Voice](https://commonvoice.mozilla.org/) — Large multilingual open speech dataset.
- [MLS (Multilingual LibriSpeech)](https://arxiv.org/abs/2012.03411) — Large-scale multilingual read-speech corpus.
- [LongAudio](https://huggingface.co/datasets/nvidia/LongAudio) — Long-form audio dataset introduced for long-context audio-language modeling.
- [ReasonAQA](https://github.com/soham97/mellow) — Audio question-answering dataset introduced with Mellow; the project links to the released JSONs and source audio assets.
- [MathLLMs/VoiceAssistant-Eval](https://huggingface.co/datasets/MathLLMs/VoiceAssistant-Eval) — Dataset release for the VoiceAssistant-Eval benchmark covering listening, speaking, and multimodal assistant tasks.

## Toolboxes :toolbox:

- [openai/whisper](https://github.com/openai/whisper) — Whisper inference and transcription codebase.
- [livekit/agents](https://github.com/livekit/agents) — Real-time voice AI agent framework for production systems.
- [pipecat-ai/pipecat](https://github.com/pipecat-ai/pipecat) — Open framework for low-latency voice and multimodal agents.
- [kyutai-labs/moshi](https://github.com/kyutai-labs/moshi) — Open-source realtime speech-text dialogue stack.
- [THUDM/GLM-4-Voice](https://github.com/THUDM/GLM-4-Voice) — Official repository for GLM-4-Voice.
- [VITA-MLLM/VITA-Audio](https://github.com/VITA-MLLM/VITA-Audio) — Official repository for VITA-Audio.
- [soham97/mellow](https://github.com/soham97/mellow) — Code and checkpoints for Mellow.
- [mbzuai-oryx/LLMVoX](https://github.com/mbzuai-oryx/LLMVoX) — Official LLMVoX implementation.
- [AIR-Bench/AIR-Bench](https://github.com/AIR-Bench/AIR-Bench) — Benchmark code and evaluation pipeline for AIR-Bench.
- [yangdongchao/UniAudio2](https://github.com/yangdongchao/UniAudio2) — Official UniAudio 2.0 code and checkpoints.
- [NKU-HLT/DIFFA](https://github.com/NKU-HLT/DIFFA) — Official DIFFA codebase, checkpoints, and benchmark scripts.
- [embeddings-benchmark/mteb](https://github.com/embeddings-benchmark/mteb) — MTEB repository that now hosts MAEB tasks, code, and leaderboard support.

## Related Awesome Lists

- [awesome-agents-in-medicine](https://github.com/Nanboy-Ronan/awesome-agents-in-medicine) — Reference example for a more structured academic awesome list.
- [Awesome-SpeechLM-Survey](https://github.com/dreamtheater123/Awesome-SpeechLM-Survey) — Broader list focused on speech language models and related resources.
- [awesome-multimodal-large-language-models](https://github.com/BradyFU/Awesome-Multimodal-Large-Language-Models) — Wider multimodal LLM list that overlaps with audio-native models.

## Contributing :wink:

Contributions are welcome. PRs adding missing 2025-2026 papers, benchmarks, datasets, and open-source voice-agent stacks are especially useful.

## License

[CC BY-SA 4.0](http://creativecommons.org/licenses/by-sa/4.0/)
