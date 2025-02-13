# Research Papers
Some research papers that I have read and found interesting.

## Desktop Elements Detection Using Deep Learning

1. [Link to original paper](https://asiffer.github.io/posts/desktop-elements-detection-using-deep-learning/)
2. to detect desktop components on screenshots (specifically for different Linux File Explorer)
3. They made their own dataset by taking screenshots of different file explorers and labeling them using [VGG Image Annotator (VIA)](https://www.robots.ox.ac.uk/~vgg/software/via/).
4. Dataset: several screenshots (about 100) from various [Linux] environments with 10 classes and then exported as a json file.
4. Model used: Region Proposals (Faster-R-CNN) with a ResNet-50 backbone on GPU (GeForce GTX 1660 with 6 GB of RAM).
5. speed of approximately 5fps.
6. Results: [Desker](https://gitlab.com/d3sker/desker) library: aims at implementing several desktop elements detection routines (Their Faster R-CNN model is available through this library).