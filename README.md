# Data Mining Final Report
## Spatio-Temporal Graph Few-Shot Learning with Cross-City Knowledge Transfer

## Environment
- python 3.10.13

## Requirements
- torch >= 1.8.1
- numpy >= 1.20.3
- scikit-learn >= 0.24.2
- pytorch geometric >= 1.7.2
- pyaml
- scipy
- tqdm

## How to run
1. Download the data folder
2. Excute the program in the notebook my_main.ipynb

- set predict target dataset in my_main.ipynb
- set reference source datasets in config.yaml 2nd row, the 'data_keys' key

## Data
- Download the data from [google drive](https://drive.google.com/file/d/1M3-lcySjAl4h5AfjtZCfO2NanZakLg2V/view?usp=sharing)   
  and unzip as thr path :  
  Data-Mining-Final-Report/data/pems-bay  
  Data-Mining-Final-Report/data/metr-la

## Data Source
- [google drive from the source repository](https://drive.google.com/file/d/16xbiRvh5jJx2A4Swv9dEMEz_Y0AEoQTM/view)
- https://github.com/Davidham3/ASTGCN/tree/master/data (before preprocess)


## Citation
This repository is modified from  
https://github.com/RobinLu1209/ST-GFSL#spatio-temporal-graph-few-shot-learning-with-cross-city-knowledge-transfer  
to run it on the jupyter notebook, for my data mining lecture final report
```
@inproceedings{DBLP:conf/KDD/CrossCityTransfer22,
  author    = {Bin Lu and
               Xiaoying Gan and
               Weinan Zhang and
               Huaxiu Yao and
               Luoyi Fu and
               Xinbing Wang},
  title     = {Spatio-Temporal Graph Few-Shot Learning with Cross-City Knowledge Transfer},
  booktitle = {{KDD} '22: The 28th {ACM} SIGKDD Conference on Knowledge Discovery and Data Mining,
              Washington, DC, USA, August 14--18, 2022},
  publisher = {{ACM}},
  year      = {2022}
}
```
