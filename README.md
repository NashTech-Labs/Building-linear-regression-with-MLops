create Enviorment

conda create -n wineq python=3.7 -y

activate env
conda activate wineq

create requirements.txt file
install them

pip install -r requirements.txt

python template.py

downloaded the wine quality dataset

git init

dvc init

dvc add data_given/winequality.csv

git add .

git commit -m "First commit"

git remote add origin https://github.com/PraanavBhowmik/Sample_dvc_demo.git
git branch -M main
git push origin main

made the params file

make get_data file in src/get_data.py

DVC COMMANDS:
dvc repro
dvc metrics show
dvc metrics diff
