---
layout: page
title: Silent Speech
description: Exploring French silent-speech recognition using surface EMG.
permalink: /projects/silent-speech/
importance: 1
---

**June 2026–present · Research prototype**

## Motivation

Silent-speech interfaces explore how articulatory muscle activity
can be used to recognise speech without an audible voice.
My goal is to investigate this approach for French-language
assistive communication.

## My contribution

My work includes reproducing silent-speech research using the
Gaddy dataset and developing a French data-collection pipeline.

I am building a French-language corpus using an eight-channel
OpenBCI Cyton setup, with electrode-placement work inspired
by AlterEgo. The experimental software builds on MONA LISA.

The project covers acquisition protocols, recording metadata,
data preparation and training and evaluation workflows.

## Current status

French data collection and model development are ongoing.
The system remains a research prototype.

## Technical challenges

- Obtaining consistent recordings across sessions.
- Making electrode placement reproducible.
- Separating useful muscle activity from noise and artefacts.
- Evaluating generalisation to recordings not used for training.

## Technologies

Python · Surface EMG · OpenBCI Cyton · Machine learning · SLURM

## Research foundations

This project builds on existing research and open-source tools,
including the Gaddy dataset, MONA LISA and AlterEgo.
These contributions are distinguished from my own implementation
and experiments.