---
title: "MOSS-TTS-Realtime: Low-Latency and Context-Aware Full-Stream Speech Synthesis"
---

# MOSS-TTS-Realtime

### Context-Aware Speech Synthesis for Real-Time Voice Agents

**Yiwei Zhao<sup>1,2,3,*</sup>, Yaozhou Jiang<sup>1,3,*</sup>, Botian Jiang<sup>1,2,3</sup>, Kexin Huang<sup>1</sup>, Yiyang Zhang<sup>1,2,3</sup>, Zhe Xu<sup>1,2,3</sup>, Yuqian Zhang<sup>1,2,3</sup>, Xiaogui Yang<sup>3</sup>, Qingyuan Cheng<sup>3</sup>, Xipeng Qiu<sup>1,2,3,†</sup>**

<sup>1</sup> Fudan University &nbsp; · &nbsp;
<sup>2</sup> Shanghai Innovation Institute &nbsp; · &nbsp;
<sup>3</sup> MOSI.AI

<sup>*</sup> Equal contribution &nbsp; · &nbsp;
<sup>†</sup> Corresponding author
<sup>*</sup> Equal contribution &nbsp; · &nbsp;
<sup>†</sup> Corresponding author

[**Code**](https://github.com/OpenMOSS/MOSS-TTS/tree/main/moss_tts_realtime)
&nbsp; | &nbsp;
[**Hugging Face Model**](https://huggingface.co/OpenMOSS-Team/MOSS-TTS-Realtime)
&nbsp; | &nbsp;
[**Demo**](https://www.mosi.cn/models/moss-tts-streaming)

---

## Overview

We present **MOSS-TTS-Realtime**, a context-aware full-stream text-to-speech system designed for real-time voice agents.

- **Full-stream**: Takes incrementally arriving text from an LLM as input and generates speech on the fly, without waiting for the complete response.

- **Low latency**: Achieves **56.4 ms** median TTS time-to-first-audio and **202.8 ms** end-to-end LLM-to-speech latency on an H100 GPU.

- **Context-aware**: Leverages both textual and acoustic context from previous dialogue turns to generate speech that fits the ongoing conversational context.

- **High quality**: Maintains competitive zero-shot voice cloning quality while delivering strong subjective naturalness and contextual appropriateness.

---

## Demo

Try the online demo:

[**MOSS-TTS-Realtime Demo →**](https://www.mosi.cn/models/moss-tts-streaming)

## Model

The pretrained model is available on Hugging Face:

[**OpenMOSS-Team/MOSS-TTS-Realtime →**](https://huggingface.co/OpenMOSS-Team/MOSS-TTS-Realtime)

## Code

The source code is available on GitHub:

[**OpenMOSS/MOSS-TTS →**](https://github.com/OpenMOSS/MOSS-TTS/tree/main/moss_tts_realtime)
