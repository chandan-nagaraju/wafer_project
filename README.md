#wafer project

create env 

```bash
conda create -n wafer python=3.7 -y
```

activate env
```bash
conda activate wafer
```

created a req file

install the req
```bash
pip install -r requirements.txt
```
download the data from 

https://github.com/iNeuron-Pvt-Ltd/wafer-dataset/archive/main.zip

```bash
git init
```
```bash
dvc init 
```
```bash
dvc add data_given/winequality.csv
```
```bash
git add .
```
```bash
git commit -m "first commit"
```

oneliner updates  for readme

```bash
git add . && git commit -m "update Readme.md"
```
```bash
dvc add Training_Batch_Files/*.csv Prediction_Batch_files/*.csv
git branch -M main
git push origin main
```
