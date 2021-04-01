# Veremi-dataset-classification
This is an implementation of the thesis research based on Position Falsification attack classification in Vehicular ad-hoc network (VANET).

This misbehaviour detection implementation includes five types of position falsification attack classification which are present in [VeReMi dataset](https://veremi-dataset.github.io/). 

## About the implementation
VeReMi dataset is the benchmark dataset of five types of position falsification attacks misbehaviour in VANET. In this implementation, machine learning approach is utilized to classify the attacks. A novel 2-consecutive BSM approach is introduced and implemented to detect the misbehaviour in the dataset with high correct classification rate. We use four classifier to perform classification:
* K Nearest Neighbor
* Random Forest
* Naive Bayes
* Decision Tree

## Dataset
Originally VeReMi dataset includes simulation log files of all the vehicles and alot of dataset extraction and preparation steps are required to create a dataset which can be used to further classify the attacks by applying machine learning algorithms. [Dataset](https://github.com/aektasharma/Veremi-dataset-classification/tree/main/Dataset) contains all these attacks dataset : 
* [at1](https://github.com/aektasharma/Veremi-dataset-classification/blob/main/Dataset/at1.csv) : Attack type 1 (Constant Attack)
* [at2](https://github.com/aektasharma/Veremi-dataset-classification/blob/main/Dataset/at2.csv) : Attack type 2 (Constant Offset Attack)
* [at4](https://github.com/aektasharma/Veremi-dataset-classification/blob/main/Dataset/at4.csv) : Attack type 4 (Random Attack)
* [at8](https://github.com/aektasharma/Veremi-dataset-classification/blob/main/Dataset/at8.csv) : Attack type 8 (Random Offset Attack)
* [at16](https://github.com/aektasharma/Veremi-dataset-classification/blob/main/Dataset/at16.csv) : Attack type 16 (Eventual stop Attack)
* [modifiedat16](https://github.com/aektasharma/Veremi-dataset-classification/blob/main/Dataset/modifiedat16.csv) : This attack was created in this project as a requirement to consecutive BSM approach to classify the false messages sent by a vehicle.

## Requirements
IPython file is attacked in this project which contains the code to classify the attacks using 2-consecutive BSM approach. 
The code can run in Jupyter notebook IDE. 

### Prerequisites
* Python 3.7+

Python Libraries required in this implementation:
* Numpy
* Scikit-Learn (sklearn)
* Pandas
* Matplotlib

### Installation
1. Clone the repository
```sh
https://github.com/aektasharma/Veremi-dataset-classification.git
```
2. Install Prerequisites
3. Install [Jupyter Notebook](https://jupyter.org/) or any other Python IDE

