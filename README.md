Create env
```bash
conda create -n wineq python=3.7 -y
```
activate env
```bash
conda activate wineq
```
Create requirements.txt

Install the requirements
```bash
pip install -r requirements.txt
```

Download the data from 
https://drive.google.com/file/d/1QJdU59cPJ3xCeJ6jpPjxPtt8L3Xp-mLc/view?usp=sharing

```bash
git init
dvc init
dvc add data_given\winequality.csv
git add .
git commit -m "first commit"
```