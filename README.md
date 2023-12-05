# streetview_cnn
CNN for reading street view images of building addresses.

#### -- Project Status: Active

## Detailed Project Description

This project explores different implementations of convolutional neural networks for the task of reading street view images of building addresses. We used PyTorch to implement an adaptation of the LeNet architecture in addition to a basic exploratory CNN.

## Project Layout

Run `tree streetview_cnn/ -A -L x` in the directory above the project to get the project layout where `-L` is the directory level to go down. An example: 
```
streetview_cnn/
├── README.md
├── Project.ipynb
├── Pipfile
├── Pipfile.lock
├── data
│   ├── test_32x32.mat
│   └── train_32x32.mat
├── models
│   ├── LeNet_cnn.pth
│   └── basic_cnn.pth
└── results
    ├── Confusion_BasicCNN.png
    ├── Confusion_LeNet.png
    ├── Error_Examples_BasicCNN.png
    └── Error_Examples_LeNet.png
```

Add notes for files and directories to keep track of what they contain:
 - `Project.ipynb`: Notebook used for downloading data, training models, and analyzing results.
 - `data`: Directory where the data is stored.
 - `models`: Directory for saved models.
 - `results`: Directory for resulting plots and analysis of model performance.



## Contact Details
* Kevin Tang (kevin.tang513@gmail.com)
* Daniel O'Brien (danobr2001@g.ucla.edu)
* Isha Shah (ishashah146@gmail.com)
* Shayan Saadat (ssaadat91@gmail.com)

<!--

Template Notes: 
 - Markdown documentation and cheatsheets:
   - https://www.markdownguide.org/cheat-sheet/
   - https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet
   
-->
