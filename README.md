# DLthon_1
Repository for 1st DLthon team3

---

## Envirionments
---
- Linux Ubuntu
- CUDA version: 12.1
- Python version: 3.10.20

## Installation
---
```
conda create -p ./venv/dlthon1 python=3.10.20
conda activate ./venv/dlthon1
which pip # pip 설치 위치 확인 ./venv/dlthon1
pip install torch==2.5.1 torchvision==0.20.1 torchaudio==2.5.1 --index-url https://download.pytorch.org/whl/cu121
git clone https://github.com/mk-jeong/dlthon-1st-dktc.git
cd dlthon-1st-dktc
pip install -r requirements.txt
```
