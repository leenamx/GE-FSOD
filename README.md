# GE-FSOD
This is the official repository for paper "Generalization-Enhanced Few-Shot Object Detection in Remote Sensing".

The relevant data and code will be released here as soon as they are organized!

## 🚀 Quick Start

Clone the epository
```
git clone https://github.com/leenamx/GE-FSOD.git
```

We recommend using Anaconda or Miniconda to create a virtual environment and install the required dependencies. We used Python 3.8 and CUDA 11.8 for development and experiments.
```
conda create -n gefsod python=3.8
conda activate gefsod
```

Install the dependencies
```
pip install -r requirements.txt
```

## 💿Datasets
+ For DIOR dataset, you can download DIOR dataset from its official [website](http://www.escience.cn/people/JunweiHan/DIOR.html) and prepare the data folder like this. Note that the JPEGImages contain all images of JPEGImages-train and JPEGImages-test.

+ For NWPU VHR-10 dataset, you can download it from [here](https://gcheng-nwpu.github.io/).The original dataset was not divided into training and validation sets. As a result, we uploaded our train/val splits in data/NWPU VHR-10 dataset/Main. The final folder layout should look like this. data<br>

+ The few_shot_ann is our few-shot data splits. You can unzip the few_shot_ann.zip in data folder and the final layout will be look like this.
few_shot_ann<br>
├── dior<br>
│   ├── benchmark_10shot<br>
│   ├── benchmark_1shot<br>
│   ├── benchmark_20shot<br>
│   ├── benchmark_2shot<br>
│   ├── benchmark_3shot<br>
│   └── benchmark_5shot<br>
└── vhr10<br>
    ├── benchmark_10shot<br>
    ├── benchmark_20shot<br>
    ├── benchmark_3shot<br>
    └── benchmark_5shot<br>



## 💻 Training
Coming Soon!

## 🔬 Evaluation
Coming Soon!

## 📋 License
This project is released under the [MIT license](https://github.com/ohayonguy/PMRF/blob/main/LICENSE).

## 📧 Contact
If you have any questions or inquiries, please feel free to [contact me](mailto:leenamx@outlook.com).
