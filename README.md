# Evaluation of Deep Learning Models in Search by Example using Capsule Endoscopy Images

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

This project aims to evaluate the performance of deep learning models in the task of searching for similar frames in capsule endoscopy videos using a search-by-example approach. The goal is to propose a methodology that can automatically identify annotated frames in wireless capsule endoscopy (WCE) videos, making it easier to develop computer-aided diagnostic (CAD) methods for gastrointestinal examinations.

Wireless capsule endoscopy has revolutionized the field of gastroenterology by providing a non-invasive way to examine the gastrointestinal tract. However, the manual analysis of thousands of frames captured during a WCE session is time-consuming and prone to errors. By leveraging state-of-the-art pre-trained convolutional neural network (CNN) models, this project aims to automate the localization of annotated frames in WCE videos, enabling more efficient analysis and research in CAD methods.


### Built With
- [TensorFlow](https://www.tensorflow.org/) - Open-source machine learning framework
- [Pillow](https://python-pillow.org/) - Python imaging library
- [OpenCV](https://opencv.org/) - Open-source computer vision library



<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running, follow these simple steps:

### Prerequisites

- Python (version 3.6 or higher)
- TensorFlow
- Pillow
- OpenCV

  You can install the required packages by running the following commands:

```shell
pip install tensorflow
pip install Pillow
pip install opencv-python
```

### Acquisition of datadet
The dataset used in this project was private and as such cannot be shared, to use this methodology it is necessary to have a dataset that contains target frames and the corresponding video where this same frame is located.



<!-- USAGE EXAMPLES -->
## Usage
This project provides a methodology to automatically locate annotated frames in wireless capsule endoscopy (WCE) videos using deep learning models. The main utility of this methodology is to enable efficient searching and localization of specific frames within a video, making it valuable for various applications in the field of gastrointestinal examinations and computer-aided diagnostics (CAD).

If the problem is to locate a frame belonging to a video but which has been altered and is not exactly the same as the one present in the video, this methodology is the right one for the approach, the code provided contains the 8 best networks tested in this specific type of problem, all having great accuracy in finding the target frames and having different approaches to feature extraction made having so far when verified in all networks found all the target frames provided.


## Contact

Rodrigo Fernandes - al71226@alunos.utad.pt

Project Link: will be updated once the article is published


