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

---

## Papers

### 2023
- **[Generative Spoken Dialogue Language Modeling (TACL'23)](https://arxiv.org/abs/2203.16502)**  
   The first "textless" model able to generate audio samples of naturalistic spoken dialogues.

### 2024
- **[A Full-duplex Speech Dialogue Scheme Based On Large Language Models (NeurIPS'24)](https://arxiv.org/abs/2405.19487)**  
   A dialogue system capable of operating in a full-duplex manner, based on a large language model (LLM) carefully aligned to be aware of a perception module, a motor function module, and the concept of a simple finite state machine (called neural FSM) with two states.
- **[Moshi: a speech-text foundation model for real-time dialogue (arXiv'24)](https://arxiv.org/abs/2410.00037)**  
  Moshi is a speech-text foundation model and full-duplex spoken dialogue framework.
- **[Beyond Turn-Based Interfaces: Synchronous LLMs as Full-Duplex Dialogue Agents (EMNLP'24)](https://arxiv.org/abs/2409.15594v1)**  
  SyncLLM is a novel mechanism to integrate time information into Llama3-8b so that they run synchronously with the real-world clock.

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
- **[Awesome-Speech-Language-Model](https://github.com/ddlBoJack/Awesome-Speech-Language-Model)**
- **[Awesome-SpeechLM-Survey](https://github.com/dreamtheater123/Awesome-SpeechLM-Survey)**
- **[Speech Trident - Awesome Speech LM](https://github.com/ga642381/speech-trident)**
- **[AWESOME-Dialogue](https://github.com/thuiar/AWESOME-Dialogue)**

### Speech Recognition (ASR)
- **[awesome-speech-recognition-speech-synthesis-papers](https://github.com/zzw922cn/awesome-speech-recognition-speech-synthesis-papers)**
- **[Awesome Korean Speech Recognition](https://github.com/rtzr/Awesome-Korean-Speech-Recognition)**

### Speech Generation (TTS)
- **[Awesome-Speech-Generation](https://github.com/kuan2jiu99/Awesome-Speech-Generation)**
- **[Awesome-Text-to-Speech-TTS](https://github.com/TouchSky-Lab/Awesome-Text-to-Speech-TTS)**

###  Speaker Diarization
- **[Awesome Speaker Diarization](https://github.com/wq2012/awesome-diarization)**

### Audio Understanding
- **[Awesome-Audio-LLM](https://github.com/AudioLLMs/Awesome-Audio-LLM)**

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
