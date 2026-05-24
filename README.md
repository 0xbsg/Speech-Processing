# Speech Processing Labs

This repository contains four Jupyter notebooks for speech processing experiments and analysis.

## Notebook Overview

1. speech processing lab1.ipynb
- Introductory speech signal analysis on a sample `.wav` file.
- Covers waveform plotting, spectrogram analysis, short-time energy, zero-crossing rate, and silence detection.
- Focus is on understanding basic speech signal characteristics in time and frequency domains.

2. speech processing_lab2.ipynb
- Phoneme-level analysis using a pre-trained Wav2Vec2 model.
- Loads speech audio, preprocesses it (mono + resampling), performs recognition, and estimates phoneme intervals.
- Extracts and visualizes selected phoneme segments from continuous speech.

3. speech processing_lab3.ipynb
- Applies phoneme segmentation to a recorded custom sentence.
- Labels extracted segments by phoneme category (vowel, plosive, fricative, etc.).
- Compares voiced and unvoiced segments using waveform properties like periodicity and amplitude structure.

4. speech processing_lab4.ipynb
- Frame-wise short-time speech analysis with 25 ms frames and 10 ms shift.
- Computes core time-domain features: STE, STM, ZCR, autocorrelation, AMDF, and AMSDF.
- Studies voiced vs unvoiced behavior using feature trends across frames.

## Notes

- Most notebooks expect local `.wav` input files (for example, LJ Speech samples or recorded voice files).
- Some cells are written for Google Colab and may need path updates before running locally.
