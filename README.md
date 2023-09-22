<h1 align="center" id="title">LSTM-music-gen</h1>
 
## Description
This project aims to leverage the vast amount of MIDI files available on the web to train a Long Short-Term Memory (LSTM) neural network and generate new, original compositions. The core components of the project are a web scraper built with Selenium and an LSTM model constructed using Python.

## Project Breakdown
1. The web-scraper (`LSTM-music-gen/midi_extact_bot/midi_scrapper.ipynb`) downloads the MIDI files from a predefined website into a designated folder (`LSTM-music-gen/data/`)
2. After training the model generates the new composition in accordance with specified model parameters and inputs (`LSTM-music-gen/model/lstm.ipynb`). The final outputs are populated in the respective directory (`LSTM-music-gen/generated_output/`).

***A more detailed overview of the project is included in this repository's PowerPoint file (`LSTM-music-gen/LSTM EDM Generation.pptx`). This presentation provides in-depth insights into each phase of the project and can serve as a helpful guide to navigate through the project's progression.***

## Tech Stack
- Python (music21, midi2audio, keras, numpy, pickle, os, glob)
- Selenium (Chrome WebDriver)
