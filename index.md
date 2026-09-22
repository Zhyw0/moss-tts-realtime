---
title: "MOSS-TTS-Realtime: Low-Latency and Context-Aware Full-Stream Speech Synthesis"
---

# MOSS-TTS-Realtime

### Context-Aware Speech Synthesis for Real-Time Voice Agents

**Yiwei Zhao<sup>1,2,3,*</sup>, Yaozhou Jiang<sup>1,3,*</sup>, Botian Jiang<sup>1,2,3</sup>, Kexin Huang<sup>1</sup>, Yiyang Zhang<sup>1,2,3</sup>, Zhe Xu<sup>1,2,3</sup>, Yuqian Zhang<sup>1,2,3</sup>, Xiaogui Yang<sup>3</sup>, Qingyuan Cheng<sup>3</sup>, Xipeng Qiu<sup>1,2,3,†</sup>**

<sup>1</sup> Fudan University &nbsp; · &nbsp;
<sup>2</sup> Shanghai Innovation Institute &nbsp; · &nbsp;
<sup>3</sup> MOSI.AI

[![Code](https://img.shields.io/badge/Code-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/OpenMOSS/MOSS-TTS/tree/main/moss_tts_realtime)
[![Hugging Face Model](https://img.shields.io/badge/Hugging_Face-Model-FFD21E?style=flat-square&logo=huggingface&logoColor=FFD21E)](https://huggingface.co/OpenMOSS-Team/MOSS-TTS-Realtime)
[![Demo](https://img.shields.io/badge/%E2%96%B6-Demo-2563EB?style=flat-square)](https://www.mosi.cn/models/moss-tts-streaming)

---

## Overview

We present **MOSS-TTS-Realtime**, a context-aware, full-stream text-to-speech model.

- **Full-stream**: Consumes incrementally arriving text from an LLM and synthesizes speech on the fly, without waiting for the complete response.

- **Context-aware**: Conditions on both textual and acoustic context from preceding dialogue turns to generate speech that stays consistent with the ongoing conversation.

- **Low latency**: Achieves a median time-to-first-audio of **56.4 ms** for TTS alone and **202.8 ms** end-to-end with an online LLM, on an H100 GPU.

- **High quality**: Delivers competitive zero-shot voice cloning and the best subjective naturalness among compared models.

## Architecture

![MOSS-TTS-Realtime model architecture](assets/moss_tts_realtime.png)
