# Audio Podcast Semantic Search Engine Proof of Concept

This proof of concept demonstrates a semantic search engine for audio podcast transcripts, starting with a collection of a16z podcasts.

## Prerequisites

Make sure you have conda (Python environment and package manager) installed. If you don't, follow the installation instructions at:

https://docs.conda.io/en/latest/miniconda.html

## Setup

1. Create the conda environment:
conda env create --name envname --file=environment.yml

2. Activate the conda environment:
conda activate envname

Replace `envname` with the name you chose when creating the environment.

3. Run Jupyter Notebook:
jupyter-notebook

This command will open Jupyter Notebook in your browser.

4. Open the `Ecco POC v0.1` notebook in the browser.

## Usage

You can run the code in the `Ecco POC v0.1` notebook. To try different queries, modify the query in the final cell of the notebook.

## Additional Information

You can find some proof of concepts for transcribing audio using OpenAI's Whisper model in the repository.