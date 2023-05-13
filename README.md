create env

'''bash
conda create -n wineq python=3.9 -y
'''

activate env
'''bash
conda activate wineq
'''

created a req file

install the req
'''bash
pip install -r requirements.txt
'''
download the dataset from
https://drive.google.com/drive/folders/18zqQiCJVgF7uzXgfbIJ-04zgz1ItNfF5

'''bash
git init
'''
'''bash
dvc init
'''
'''bash
dvc add data_given\winequality.csv
'''
'''bash
git add .
'''
'''bash
git commit -m "first commit"
'''
''' bash
oneliner updates for readme
git add . && git commit -m "update Readme.md"
'''
'''bash
git remote add origin https://github.com/AMadhan1/simple-dvc-demo.git
git branch -M main
git push -u origin main
'''

tox command -
'''bash
tox
'''

for rebuilding -
'''bash
tox -r
'''

pytest command
'''bash
pytest -v
'''
setup commands -
'''bash
pip install -e
'''

build your own package commands-
'''bash
python setup.py sdist bdist wheel
'''