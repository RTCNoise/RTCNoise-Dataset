# RTCNoise Dataset (Based on Microsoft Scalable Noisy Speech Dataset (MS-SNSD))
* This dataset contains a large collection of clean speech files and variety of environmental noise files in .wav format sampled at 16 kHz.
* The main application of this dataset is to train Deep Neural Network (DNN) models to suppress background noise. But it can be used for other audio and speech applications.
* We provide the recipe to mix clean speech and noise at various signal to noise ratio (SNR) conditions to generate large noisy speech dataset. 
* The SNR conditions and the number of hours of data required can be configured depending on the application requirements.
* This dataset will continue to grow in size as we encourage researchers and practitioners to contribute to this dataset by adding more clean speech and noise clips. 
* This dataset will immensely help researchers and practitioners in accademia and industry to develop better models. 
* We also provide test set that is different from training set to evaluate the developed models.
* We will provide more types of noise speech in the near future

## Prerequisites
- Python 3.0 and above
- soundfile (pip install soundfile)


## RTCNoise Dataset
# Training and test sets
1. Clean Speech data for training is present in the directory 'clean_train'
2. Noise data for training is present in the directory 'noise_train'
Download the data onto your local machine.

## Usage
1. Clone the repo to your local directory with the link: https://github.com/RTCNoise/RTCNoise-Dataset.git
 
2. Download clean speech and noise datasets into the same directory with scripts


## Dataset licenses
MICROSOFT PROVIDES THE DATASETS ON AN "AS IS" BASIS. MICROSOFT MAKES NO WARRANTIES, EXPRESS OR IMPLIED, GUARANTEES OR CONDITIONS WITH RESPECT TO YOUR USE OF THE DATASETS. TO THE EXTENT PERMITTED UNDER YOUR LOCAL LAW, MICROSOFT DISCLAIMS ALL LIABILITY FOR ANY DAMAGES OR LOSSES, INLCUDING DIRECT, CONSEQUENTIAL, SPECIAL, INDIRECT, INCIDENTAL OR PUNITIVE, RESULTING FROM YOUR USE OF THE DATASETS.

The datasets are provided under the original terms that Microsoft received such datasets. See below for more information about each dataset.