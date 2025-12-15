# Awesome Spoken Dialogue Systems [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> **“Is this a computer, or a human?”**

A curated list of **awesome spoken dialogue systems**, focusing on speech-first, real-time conversational agents.
This list covers research papers and toolkits that treat speech as the primary interface, not merely a wrapper around text-based dialogue.

This is a curation, not a collection. Only resources that meaningfully advance spoken dialogue systems toward that goal are included.

---

## Contents

- [Papers](#papers)
- [Benchmarks](#benchmarks)
- [Toolkits](#toolkits)
- [Related Awesome Lists](#related-awesome-lists)
- [Contributing](#contributing)
- [License](#license)

---

## Papers

Research papers and research-grade systems that **rethink dialogue systems from a speech-first perspective**.

- **[A Full-duplex Speech Dialogue Scheme Based On Large Language Models (NeurIPS'24)](https://arxiv.org/abs/2405.19487)**  
   A dialogue system capable of operating in a full-duplex manner, based on a large language model (LLM) carefully aligned to be aware of a perception module, a motor function module, and the concept of a simple finite state machine (called neural FSM) with two states.
- **[Moshi: a speech-text foundation model for real-time dialogue](https://arxiv.org/abs/2410.00037)**  
  Moshi is a speech-text foundation model and full-duplex spoken dialogue framework.
- **[Beyond Turn-Based Interfaces: Synchronous LLMs as Full-Duplex Dialogue Agents (EMNLP'24)](https://arxiv.org/abs/2409.15594v1)**  
  SyncLLM is a novel mechanism to integrate time information into Llama3-8b so that they run synchronously with the real-world clock.
  

---

## Benchmarks

Benchmarks and evaluation frameworks designed to measure **spoken dialogue systems beyond text-only metrics**.

- **[FD-Bench](https://github.com/pengyizhou/FD-Bench)**  
  FD-Bench is a comprehensive benchmarking pipeline specifically designed for evaluating Full-Duplex Spoken Dialogue Systems (FD-SDS).

---

## Toolkits

Frameworks and libraries for building **real-world spoken dialogue systems**.

- **[Pipecat](https://github.com/pipecat-ai/pipecat)**  
  Pipecat is an open-source Python framework for building real-time voice and multimodal conversational agents.
- **[ESPnet-SDS](https://github.com/espnet/espnet/blob/master/egs2/TEMPLATE/sds1/README.md)**  
  ESPnet-SDS is an open-source toolkit for building unified web interfaces for various cascaded and end-to-end (E2E) spoken dialogue systems, supporting real-time automated evaluation metrics, and human-in-the-loop feedback collection.

---

## Related Awesome Lists

The following lists already cover adjacent areas well:

- **[Awesome Dialogue System Papers](https://github.com/jaromirsalamon/Awesome-Dialogue-System-Papers)**
- **[Awesome-Speech-Language-Model](https://github.com/ddlBoJack/Awesome-Speech-Language-Model)**
- **[Awesome-SpeechLM-Survey](https://github.com/dreamtheater123/Awesome-SpeechLM-Survey)**
- **[Speech Trident - Awesome Speech LM](https://github.com/ga642381/speech-trident)**
- **[Awesome-Audio-LLM](https://github.com/AudioLLMs/Awesome-Audio-LLM)**
- **[AWESOME-Dialogue](https://github.com/thuiar/AWESOME-Dialogue)**

---

## Contributing

Contributions are welcome, but please read carefully before submitting a pull request.

**Guidelines:**

- Only include resources you have **personally used, studied, or can strongly recommend**.
- Each entry **must explain why it is awesome** and how it helps advance spoken dialogue systems toward the goal stated at the top of this list.
- The scope is **spoken dialogue systems**.  
  Both **modular pipelines** and **end-to-end architectures** are welcome, as long as they are designed for spoken interaction.  
  Pure ASR, TTS, or text-only chat frameworks should be excluded unless they meaningfully change how spoken dialogue is modeled or experienced.
- Keep descriptions concise and end them with a period.
- Maintain consistent formatting and valid Markdown.

Respect differing opinions. If multiple contributors disagree on an inclusion, reconsider it carefully.

---

## License

[CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the authors have waived all copyright and related rights to this work.
