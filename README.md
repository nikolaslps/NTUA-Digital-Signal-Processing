# Perceptual Audio Coding - DSP Lab

This repository contains the implementation for **Lab 2: Perceptual Audio Coding**, as part of the **Digital Signal Processing (DSP)** course at NTUA. The project focuses on compressing an audio signal using psychoacoustic models, following principles similar to MP3 encoding.

## Project Overview

The goal of this lab is to implement **Perceptual Audio Coding**, where:
- A **psychoacoustic model** determines the **masking threshold** of an audio signal.
- A **filter bank** splits the signal into frequency bands.
- A **quantization step** reduces bit usage based on perceptual importance.

The input audio file is **music.wav** (16-bit PCM, 44.1 kHz), and the output consists of two compressed versions:
1. Using an **adaptive quantizer** based on the psychoacoustic model.
2. Using a **fixed-bit quantizer** (Bk = 8 bits per sample).

## Setup & Requirements

### Prerequisites
Ensure you have the following installed:
- **Python 3.11+**
- **NumPy** (`pip install numpy`)
- **SciPy** (`pip install scipy`)
- **Matplotlib** (`pip install matplotlib`)

### Installation
Clone this repository:
```sh
git clone https://github.com/your-username/your-repo.git
cd your-repo
```

## Author
- **NIKOLAOS LAPPAS**
- **ECE NTUA**

