# ITU Research Project - Image Reconstruction

## Installing packages

Install required packages by running the following command from the main folder: 

`pip install -r requirements.txt`

Consider [setting up a virtual environment in Python](https://docs.python.org/3/library/venv.html).

## Data


To be able to run all the cells in the Main.ipynb notebook, all three datasets should be downloaded from the links below and placed in the instructed directories within this project.

### ThoughtViz
The project is structured around the classifier from the [ThoughtViz paper](https://www.crcv.ucf.edu/papers/acmmm18/thoughtviz.pdf). The EEG and image data can be found on the [ThoughtViz github](https://github.com/ptirupat/ThoughtViz).

- Place the char data.pkl file in ./eeg/char/
- Place the digit data.pkl file in ./eeg/digit/
- Place the char image.pkl file in ./eeg/image/


### MindBig

We use data from the [MindBig 2022 paper by David Vivancos](https://arxiv.org/ftp/arxiv/papers/2212/2212.14746.pdf). The data from this project can be found on [Hugging Face](https://huggingface.co/datasets/DavidVivancos/MindBigData2022).

- File download should happen automatically, if not try:
    - Place the test.csv and the train.csv files in ./eeg/MindBig/

### PeRCeiVe Lab

We use data from PeRCeiVe Lab, which is based on [this paper](https://arxiv.org/pdf/1810.10974.pdf). The data from this project can be accessed through the [official Github of the project](https://github.com/perceivelab/eeg_visual_classification).

- Place the eeg_5_95_std.pth file in ./eeg/PeRCeiVe/