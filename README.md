# Handwritten Bengali Character Recognition

This project focuses on recognizing handwritten Bengali characters using a convolutional neural network (CNN) implemented in TensorFlow. The model is trained on a dataset of handwritten Bengali characters and achieves high accuracy in character recognition.

## Table of Contents

- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Model Overview](#model-overview)
- [Dataset](#dataset)
- [Training](#training)
- [Testing](#testing)
- [Results](#results)
- [Demo](#demo)
- [Acknowledgments](#acknowledgments)
- [License](#license)

## Getting Started

### Prerequisites

- Python 3.x
- Google Colab (optional, for training on GPU)

### Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/handwritten-bengali-recognition.git
cd handwritten-bengali-recognition
```

2. Set up a virtual environment (optional but recommended):

```bash
python3 -m venv env
source env/bin/activate
```

3. Install the required packages:

```bash
pip install -r requirements.txt
```

## Model Overview

The recognition model is implemented using a CNN with multiple convolutional and pooling layers, followed by fully connected layers. The model is trained to classify Bengali characters into different categories.

For more details, refer to Model Overview.

## Dataset

The dataset used for training consists of handwritten Bengali characters collected from various sources. It contains labeled images of characters in different styles and handwriting.

For more details, refer to [Dataset](https://deepai.org/publication/banglalekha-isolated-a-comprehensive-bangla-handwritten-character-dataset).

## Results

The trained model achieves an accuracy of over 94.4% on the test set. For a detailed report on results, refer to Results.

## Acknowledgments

    Special thanks to source_of_dataset for providing the handwritten Bengali character dataset.

## License

This project is licensed under the [Mit License](LICENSE).
