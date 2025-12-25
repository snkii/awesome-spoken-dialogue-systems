# Awesome Spoken Dialogue Systems [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![Contribution](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/snkii/awesome-spoken-dialogue-systems?tab=readme-ov-file#contributing)

> **“Is this a computer, or a human?”**

A curated list of **awesome spoken dialogue systems**, focusing on speech-first, real-time conversational agents.
This list covers research papers and toolkits that treat speech as the primary interface, not merely a wrapper around text-based dialogue.

This is a curation, not a collection. Only resources that meaningfully advance spoken dialogue systems toward that goal are included.

---

## Contents
- [Surveys](#surveys)
- [Papers](#papers)
- [Benchmarks](#benchmarks)
- [Toolkits](#toolkits)
- [Related Awesome Lists](#related-awesome-lists)
- [Contributing](#contributing)
- [License](#license)

---

## Surveys

- **[A Comprehensive Survey on Full-Duplex Communication: Current Solutions, Future Trends, and Open Issues (IEEE ComST'23)](https://ieeexplore.ieee.org/document/10258345)**
- **[WavChat: A Survey of Spoken Dialogue Models (arXiv'24)](https://arxiv.org/abs/2411.13577)**
- **[From Turn-Taking to Synchronous Dialogue: A Survey of Full-Duplex Spoken Language Models (arXiv'25)](https://arxiv.org/abs/2509.14515)**
- **[A Survey of Recent Advances on Turn-taking Modeling in Spoken Dialogue Systems (IWSDS'25)](https://aclanthology.org/2025.iwsds-1.27/)**
- **[On The Landscape of Spoken Language Models: A Comprehensive Survey (arXiv'25)](https://arxiv.org/abs/2504.08528)**
- **[Recent Advances in Speech Language Models: A Survey (ACL'25)](https://aclanthology.org/2025.acl-long.682/)**

---

## Papers

### 2023
- **[Generative Spoken Dialogue Language Modeling (TACL'23)](https://arxiv.org/abs/2203.16502)**  
   The first "textless" model able to generate audio samples of naturalistic spoken dialogues.
- **[VioLA: Unified Codec Language Models for Speech Recognition, Synthesis, and Translation (TACL'23)](https://arxiv.org/abs/2305.16107)**  
   A single auto-regressive Transformer decoder-only network that unifies various cross-modal tasks involving speech and text, such as speech-to-text, text-to-text, text-to-speech, and speech-to-speech tasks, as a conditional codec language model task via multi-task learning framework.
  
### 2024
- **[A Full-duplex Speech Dialogue Scheme Based On Large Language Models (NeurIPS'24)](https://arxiv.org/abs/2405.19487)**  
   A dialogue system capable of operating in a full-duplex manner, based on a large language model (LLM) carefully aligned to be aware of a perception module, a motor function module, and the concept of a simple finite state machine (called neural FSM) with two states.
- **[Moshi: a speech-text foundation model for real-time dialogue (arXiv'24)](https://arxiv.org/abs/2410.00037)**  
  Moshi is a speech-text foundation model and full-duplex spoken dialogue framework.
- **[Beyond Turn-Based Interfaces: Synchronous LLMs as Full-Duplex Dialogue Agents (EMNLP'24)](https://arxiv.org/abs/2409.15594v1)**  
  SyncLLM is a novel mechanism to integrate time information into Llama3-8b so that they run synchronously with the real-world clock.
- **[Language Model Can Listen While Speaking
 (AAAI'25)](https://ojs.aaai.org/index.php/AAAI/article/view/34665)**  
   An end-to-end system equipped with both listening and speaking channels.
- **[Beyond the Turn-Based Game: Enabling Real-Time Conversations with Duplex Models (EMNLP'24)](https://arxiv.org/abs/2409.15594v1)**  
  They adapt existing LLMs to duplex models so that they can listen to users while generating output and dynamically adjust themselves to provide instant feedback.
- **[SALMONN-omni: A Codec-free LLM for Full-duplex Speech Understanding and Generation (arXiv'24)](https://arxiv.org/abs/2411.18138)**  
  A codec-free, full-duplex speech understanding and generation model capable of simultaneously listening to its own generated speech and background sounds while speaking.
- **[GLM-4-Voice: Towards Intelligent and Human-Like End-to-End Spoken Chatbot (arXiv'24)](https://arxiv.org/abs/2412.02612)**  
  An intelligent and human-like end-to-end spoken chatbot. It supports both Chinese and English, engages in real-time voice conversations, and varies vocal nuances such as emotion, intonation, speech rate, and dialect according to user instructions.
  
### 2025
- **[Freeze-Omni: A Smart and Low Latency Speech-to-speech Dialogue Model with Frozen LLM (ICML'25)](https://icml.cc/virtual/2025/poster/43854)**  
  The speech input and output modalities can be easily connected to a textual LLM while keeping the LLM's parameters frozen throughout the training process.
- **[FlexDuo: A Pluggable System for Enabling Full-Duplex Capabilities in Speech Dialogue Systemss (arXiv'25)](https://arxiv.org/abs/2502.13472)**  
  A flexible full-duplex control module that decouples duplex control from spoken dialogue systems through a plug-and-play architectural design.
- **[Can Speech LLMs Think while Listening? (arXiv'25)](https://arxiv.org/abs/2510.07497)**  
  Inspired by the human behavior of “thinking while listening,” they propose methods to reduce the additional latency from reasoning by allowing the model to start reasoning before the user query has ended.
- **[STITCH: Simultaneous Thinking and Talking with Chunked Reasoning for Spoken Language Models (arXiv'25)](https://arxiv.org/abs/2507.15375)**  
  A novel generation method that alternates between the generation of unspoken reasoning chunks and spoken response chunks.
- **[DIFFA: Large Language Diffusion Models Can Listen and Understand (AAAI'25)](https://arxiv.org/abs/2507.18452)**  
  The first diffusion-based large audio-language model designed to perform spoken language understanding.
- **[Stream RAG: Instant and Accurate Spoken Dialogue Systems with Streaming Tool Usage (arXiv'25)](https://arxiv.org/abs/2510.02044)**  
  A novel framework that reduces user-perceived latency by predicting tool queries in parallel with user speech, even before the user finishes speaking.
- **[VITA-1.5: Towards GPT-4o Level Real-Time Vision and Speech Interaction (NuerIPS'25)](https://arxiv.org/abs/2409.15594v1)**  
  They proposed a carefully designed multi-stage training methodology that progressively trains LLM to understand both visual and speech information, ultimately enabling fluent vision and speech interaction.
- **[VITA-Audio: Fast Interleaved Cross-Modal Token Generation for Efficient Large Speech-Language Model (NuerIPS'25)](https://arxiv.org/abs/2505.03739)**  
  The first multi-modal large language model capable of generating audio output during the first forward pass, enabling real-time conversational capabilities with minimal latency.
- **[From Turn-Taking to Synchronous Dialogue: A Survey of Full-Duplex Spoken Language Models (arXiv'25)](https://arxiv.org/abs/2505.03739)**  
  This survey comprehensively reviews Full-Duplex Spoken Language Models (FD-SLMs) in the LLM era.
- **[NTPP: Generative Speech Language Modeling for Dual-Channel Spoken Dialogue via Next-Token-Pair Prediction (ICML'25)](https://arxiv.org/abs/2506.00975)**  
  They systematically explore the use of dual-channel speech data in the context of modern large language models, and introduce a novel generative modeling paradigm, Next-Token-Pair Prediction (NTPP), to enable speaker-independent dual-channel spoken dialogue learning using decoder-only architectures for the first time.
- **[SALM-Duplex: Efficient and Direct Duplex Modeling for Speech-to-Speech Language Model (Interspeech'25)](https://arxiv.org/abs/2505.15670)**  
  They propose a novel duplex speech to speech (S2S) architecture featuring continuous user inputs and codec agent outputs with channel fusion that directly models simultaneous user and agent streams.

### Reasoning (Streaming Thinking)
- **[Quiet-STaR: Language Models Can Teach Themselves to Think Before Speaking (CoRR'24)](https://arxiv.org/abs/2403.09629)**  
  A generalization of STaR in which LMs learn to generate rationales at each token to explain future text, improving their predictions.
- **[StreamingThinker: Large Language Models Can Think While Reading (arXiv'25)](https://arxiv.org/abs/2510.17238)**  
  They first design a streaming thinking paradigm for LLMs, where reasoning unfolds in the order of input and further adjusts its depth once reading is complete. 


### Toward natural spoken dialogue modeling (_e.g._ backchanelling, filler)
- **[Attentive listening system with backchanneling, response generation and flexible turn-taking (SIGDIAL'17)](https://aclanthology.org/W17-5516/)**  
  This paper addresses key components of an attentive listening system which encourages users to talk smoothly.
- **[Predicting Turn-Taking and Backchannel in Human-Machine Conversations Using Linguistic, Acoustic, and Visual Signals (ACL'25)](https://arxiv.org/abs/2505.12654)**  
  They addressed the gap in predicting turn-taking and backchannel actions in human-machine conversations using multi-modal signals. They also proposed an automatic data collection pipeline that allows us to collect and annotate over 210 hours of human conversation videos.
- **[FillerSpeech: Towards Human-Like Text-to-Speech Synthesis with Filler Insertion and Filler Style Control (EMNLP'25)](https://aclanthology.org/2025.emnlp-main.1730/)**  
  A novel speech synthesis framework that enables natural filler insertion and control over filler style.
  

---

## Benchmarks

- **[VoiceBench: Benchmarking LLM-Based Voice Assistants (arXiv'24)](https://arxiv.org/abs/2410.17196)**  
  The first benchmark designed to provide a multi-faceted evaluation of LLM-based voice assistants.
- **[SD-Eval: A Benchmark Dataset for Spoken Dialogue Understanding Beyond Words (NeurIPS'24)](https://neurips.cc/virtual/2024/poster/97707)**  
  A benchmark dataset aimed at multidimensional evaluation of spoken dialogue understanding and generation.
- **[FD-Bench: A Full-Duplex Benchmarking Pipeline Designed for Full Duplex Spoken Dialogue Systems (Interspeech'25)](https://github.com/pengyizhou/FD-Bench)**  
  FD-Bench is a comprehensive benchmarking pipeline specifically designed for evaluating Full-Duplex Spoken Dialogue Systems (FD-SDS).
- **[EMO-Reasoning: Benchmarking Emotional Reasoning Capabilities in Spoken Dialogue Systems (ASRU'25)](https://arxiv.org/abs/2508.17623)**  
  A benchmark for assessing emotional coherence in dialogue systems.
- **[Full-Duplex-Bench: A Benchmark to Evaluate Full-duplex Spoken Dialogue Models on Turn-taking Capabilities (ASRU'25)](https://arxiv.org/abs/2503.04721)**  
  They introduce Full-Duplex-Bench, a benchmark that systematically evaluates key interactive behaviors: pause handling, backchanneling, turn-taking, and interruption management. 
- **[Full-Duplex-Bench v1.5: Evaluating Overlap Handling for Full-Duplex Speech Models (arXiv'25)](https://arxiv.org/abs/2507.23159)**  
  They introduce Full-Duplex-Bench v1.5, a modular, fully automated benchmark that simulates four overlap scenarios: user interruption, listener backchannel, side conversation, and ambient speech.
- **[Full-Duplex-Bench-v2: A Multi-Turn Evaluation Framework for Duplex Dialogue Systems with an Automated Examiner (arXiv'25)](https://arxiv.org/abs/2510.07838)**  
  They introduce Full-Duplex-Bench-v2 (FDB-v2), a streaming framework that integrates with an automated examiner that enforces staged goals under two pacing setups (Fast vs. Slow). 
- **[ICASSP2026 HumDial Challenge](https://github.com/ASLP-lab/Hum-Dial?tab=readme-ov-file)**  
  The official GitHub repository for the ICASSP2026 HumDial Challenge. 

---

## Toolkits

- **[Pipecat](https://github.com/pipecat-ai/pipecat)**  
  Pipecat is an open-source Python framework for building real-time voice and multimodal conversational agents.
- **[ESPnet-SDS](https://github.com/espnet/espnet/blob/master/egs2/TEMPLATE/sds1/README.md)**  
  ESPnet-SDS is an open-source toolkit for building unified web interfaces for various cascaded and end-to-end (E2E) spoken dialogue systems, supporting real-time automated evaluation metrics, and human-in-the-loop feedback collection.

---

## Related Awesome Lists

### LLM-based SDS
- **[Awesome Dialogue System Papers](https://github.com/jaromirsalamon/Awesome-Dialogue-System-Papers)** ![GitHub stars](https://img.shields.io/github/stars/jaromirsalamon/Awesome-Dialogue-System-Papers?style=social)
- **[Awesome-Speech-Language-Model](https://github.com/ddlBoJack/Awesome-Speech-Language-Model)** ![GitHub stars](https://img.shields.io/github/stars/ddlBoJack/Awesome-Speech-Language-Model?style=social)
- **[Awesome-SpeechLM-Survey](https://github.com/dreamtheater123/Awesome-SpeechLM-Survey)** ![GitHub stars](https://img.shields.io/github/stars/dreamtheater123/Awesome-SpeechLM-Survey?style=social)
- **[Speech Trident - Awesome Speech LM](https://github.com/ga642381/speech-trident)** ![GitHub stars](https://img.shields.io/github/stars/ga642381/speech-trident?style=social)
- **[AWESOME-Dialogue](https://github.com/thuiar/AWESOME-Dialogue)** ![GitHub stars](https://img.shields.io/github/stars/thuiar/AWESOME-Dialogue?style=social)

### Speech Recognition (ASR)
- **[awesome-speech-recognition-speech-synthesis-papers](https://github.com/zzw922cn/awesome-speech-recognition-speech-synthesis-papers)** ![GitHub stars](https://img.shields.io/github/stars/zzw922cn/awesome-speech-recognition-speech-synthesis-papers?style=social)
- **[Awesome Korean Speech Recognition](https://github.com/rtzr/Awesome-Korean-Speech-Recognition)** ![GitHub stars](https://img.shields.io/github/stars/rtzr/Awesome-Korean-Speech-Recognition?style=social)

### Speech Generation (TTS)
- **[Awesome-Speech-Generation](https://github.com/kuan2jiu99/Awesome-Speech-Generation)** ![GitHub stars](https://img.shields.io/github/stars/kuan2jiu99/Awesome-Speech-Generation?style=social)
- **[Awesome-Text-to-Speech-TTS](https://github.com/TouchSky-Lab/Awesome-Text-to-Speech-TTS)** ![GitHub stars](https://img.shields.io/github/stars/TouchSky-Lab/Awesome-Text-to-Speech-TTS?style=social)

### Speaker Diarization
- **[Awesome Speaker Diarization](https://github.com/wq2012/awesome-diarization)** ![GitHub stars](https://img.shields.io/github/stars/wq2012/awesome-diarization?style=social)

### Audio Understanding
- **[Awesome-Audio-LLM](https://github.com/AudioLLMs/Awesome-Audio-LLM)** ![GitHub stars](https://img.shields.io/github/stars/AudioLLMs/Awesome-Audio-LLM?style=social)

---

## Contributing

Contributions are welcome, but please read carefully before submitting a pull request.

**Guidelines:**

- Only include resources you have **personally used, studied, or can strongly recommend**.
- Each entry **must explain why it is awesome** and how it helps advance spoken dialogue systems toward the goal stated at the top of this list.
- The scope is **spoken dialogue systems**.  
  Both **modular pipelines** and **end-to-end architectures** are welcome, as long as they are designed for spoken interaction.
- Keep descriptions concise and end them with a period.
- Maintain consistent formatting and valid Markdown.

Respect differing opinions. If multiple contributors disagree on an inclusion, reconsider it carefully.

---

## License

[CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the authors have waived all copyright and related rights to this work.
