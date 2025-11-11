# Thesis-Code-tiny
Preliminary exploration for my EE thesis

# Requirements
You need **Anaconda** already installed.
```bash
sudo apt install git-lfs
python -m pip install pytorchcv
python -m pip install onnx
python -m pip install tqdm
python -m pip install datasets
python -m pip install torchinfo

```

# Tutorial

#Clone the REPO

```bash
git clone https://github.com/CarlitosTevez10/Thesis-Code-tiny.git
```
to pull SHARDS
```bash
git lfs pull
```
create new conda environment:
```bash
conda env create -f environment.yml
```
Activate your chosen environment es. :
```bash
conda activate training
```
To download shards:
```bash
cd ./datasets
python dataset_generator.py
```



