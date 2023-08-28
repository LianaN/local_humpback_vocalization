# Local Humpback Whales Vocalization

This repository contains a series of Jupyter notebooks designed to guide through the process of data preparation for building a humpback whale vocalization model. The notebooks cover everything from setting up the development environment to data acquisition, data revision, and data preprocessing.

This repository uses the labeled data of humpback whale vocalizations from [Orcasound's AWS open data repository](https://open.quiltdata.com/b/acoustic-sandbox/tree/humpbacks/Emily-Vierling-Orcasound-data/Em_HW_data/flac_files/). The dataset was prepared by Emily Vierling. It includes ~9,000 labels and is based on ~YY hours of audio data from 3 days during October 03-28, 2021.

## Table of Contents

1. [Introduction](#introduction)
2. [Getting Started](#getting-started)
3. [Notebooks](#notebooks)
4. [Contributing](#contributing)
5. [License](#license)

## Introduction

Humpback whales are known for their complex vocalizations, often referred to as "songs." Understanding these vocalizations can provide valuable insights into their behavior, social structure, and even their emotional states. This project aims to facilitate the building of a machine learning model to predict and retrieve humpback whale vocalizations from raw audio files.

## Getting Started

### Prerequisites

- Python 3.x
- IDE: Jupyter Notebook, Jupyter Lab, Visual Studio Code, web IDE (e.g. Google Colaboratory) or any other

### Installation

If you are using a local development environment, please follow steps below:

1. Clone this repository:
    ```bash
    git clone https://github.com/LianaN/local_humpback_vocalization.git
    ```
2. Navigate to the project directory:
    ```bash
    cd local_humpback_vocalization
    ```
3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```
4. Launch your preferred IDE to access the notebooks

If you are using [Google Colaboratory](https://colab.research.google.com/) as your web IDE, please follow instructions from `notebooks/0_dev_environment_setup.ipynb` to get started.

## Notebooks

### 0_dev_environment_setup.ipynb

**Note**: Execute this notebook only if you are using Google Colaboratory as your development environment.

This notebook guides through setting up the development environment on Google Colaboratory. It includes instructions for installing necessary packages and setting up Google Drive for data storage.

### 1_data_acquisition.ipynb

This notebook covers the steps required to acquire humpback whale vocalization data. It includes code for downloading the datasets (annotation and raw audio files).

### 2_data_revision.ipynb

In this notebook, the starter code for the revision of the acquired data is provided. This includes visualizing audio waveforms, listening to audio samples, and identifying potential issues in the dataset.

### 3_data_preprocessing.ipynb

This notebook focuses on extracting the humpback whales vocalizations from raw audio data to prepare the data for machine learning. 

## Contributing

Contributions are welcome! Please read the [CONTRIBUTING.md](CONTRIBUTING.md) for details on how to contribute to this project.

---

For any questions or concerns, please open an issue or submit a pull request. Happy modeling!