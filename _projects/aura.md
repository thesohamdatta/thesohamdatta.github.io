---
layout: page
title: AURA
description: On-device emotional AI wearable for privacy-first human interaction
img: assets/img/projects/aura.jpg
importance: 1
category:
---

## Overview

Privacy-first, offline AI system for emotional awareness and human-centered interaction.

Runs entirely on Raspberry Pi Zero 2W with no cloud dependency.

## Problem

Most emotional AI systems require cloud processing, raising privacy concerns and adding latency. Users need real-time, private emotional context without data leaving their device.

## Technical Approach

**Hardware:**
- Raspberry Pi Zero 2W (quad-core ARM, 512MB RAM)
- Custom sensor integration
- Sub-500ms inference latency

**AI Stack:**
- Quantized LLMs (4-bit) for on-device reasoning
- CNN-LSTM models for temporal pattern recognition
- Optimized for edge deployment

**Constraints:**
- No internet required
- All processing local
- Battery-efficient inference
- Real-time response

## System Architecture

Edge-first design with three layers:
1. Sensor input processing
2. On-device inference (quantized models)
3. Context-aware response generation

## Outcome

Functional prototype demonstrating:
- Real-time emotional context detection
- Complete privacy (no data transmission)
- Practical edge AI deployment
- Human-centered design principles

## Technical Stack

- **Hardware:** Raspberry Pi Zero 2W
- **ML Framework:** PyTorch, ONNX Runtime
- **Model Optimization:** Quantization (4-bit), pruning
- **Languages:** Python, C++

---

*Focus: Privacy-first AI, edge computing, human-centered systems*
