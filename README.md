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

*Video Tutorial:* [link text](https://youtu.be/AlzMyRC5Ju8)

#Clone the REPO

```bash
GIT_LFS_SKIP_SMUDGE=1 git clone --filter=blob:none --depth=1 \
  https://github.com/CarlitosTevez10/Thesis-Code-tiny.git Thesis-Code-tiny-tutorial
cd Thesis-Code-tiny-tutorial

```

create new conda environment:
```bash
conda env create -f environment.yml
```
Activate your chosen environment es. :
```bash
conda activate training
```
to pull SHARDS
```bash
git lfs pull
```
**Alternatively** to download shards:
```bash
cd ./datasets
python dataset_generator.py
```
to run the finetuner.py with default arguments simply
```bash
python finetuner.py
```

