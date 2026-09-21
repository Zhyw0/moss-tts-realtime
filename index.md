# MOSS-TTS-REALTIME

## Context-Aware Streaming Speech Synthesis for Real-Time Voice Agents

**ICASSP 2027 Submission**

Author A · Author B · Author C

[Paper](xxx) | [Code](xxx) | [Demo](xxx)

---

## Overview

MOSS-TTS-REALTIME is a context-aware streaming text-to-speech model
designed for real-time voice agents.

It supports:

- Extremely low-latency streaming synthesis
- Multi-turn conversational context
- Persistent acoustic context
- Incremental LLM text input

![Architecture](assets/architecture.png)

## Demo

### Example 1

**User:** 今天有什么安排？

**Assistant:** 今天下午两点有一个组会。

<audio controls>
  <source src="assets/demo1.wav" type="audio/wav">
</audio>

## Results

| Model | TTFA50 | TTFA95 | RTF |
|---|---:|---:|---:|
| MOSS-TTS-REALTIME | 129.3 ms | 145.3 ms | 0.3515 |

## Citation

```bibtex
@inproceedings{...}
