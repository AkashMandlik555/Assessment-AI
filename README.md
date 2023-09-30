# Multilingual Language Translation using Facebook's mBART-50 using Hugging Face's transformer
# AI/ML Assesment

## Overview

This repository contains code for language translation using the mBART (Multilingual BART) model. mBART is a pre-trained sequence-to-sequence model designed for various natural language processing tasks, including translation.

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Pre-trained Model](#pre-trained-model)
- [Example](#example)
- [License](#license)

## Introduction

MBART is a sequence-to-sequence denoising auto-encoder pre-trained on large-scale monolingual corpora in many languages using the BART objective. mBART is one of the first methods for pre-training a complete sequence-to-sequence model by denoising full texts in multiple languages, while previous approaches have focused only on the encoder, decoder, or reconstructing parts of the text.

## Installation

```bash
# Example installation commands
pip install -r requirements.txt

## Usage

# Example usage
python translate.py --source-language en --target-language hi --input-text "Definitely share your feedback in the comment section."

## Pre-trained Model
mBART Model: [facebook/mbart-large-50-one-to-many-mmt]

## Example
Input: Definitely share your feedback in the comment section.
Output: निश्चित रूप से अपनी राय टिप्पणी सेक्शन में साझा करें।

## License
MIT Liscence

To know more about This: [https://huggingface.co/vasudevgupta/mbart-iitb-hin-eng]
Google Colab Link: [https://colab.research.google.com/drive/153EnWGAKD1MUXj0qRTOpVmeMt5OsebIy#scrollTo=qVrQLzAtQr_J]

Want to know more about me:
Github: [https://github.com/AkashMandlik555]
Linkedin: [https://www.linkedin.com/in/akash-mandlik/]
Portfolio: [https://akashm-portfolio.up.railway.app/]

Reference: [https://github.com/AkashMandlik555/transformers.git]

Thank You!