

    Create env

````bash
conda create -n wineq python=3.7 -y
````


    activate env

````bash 
conda activate wineq
````
    created a req file

````bash
install the req
````

    istall the req
````bash
    pip install -r requirements.txt
````

    download the data from
````bash
    https://drive.google.com/drive/folders/18zqQiCJVgF7uzXgfbIJ-04zgz1ItNfF5?usp=sharing
    ````

````bash
git init
````
````bash
dvc init 
````
````bash
dvc add data_given/winequality.csv
````
````bash
git add .
````

````bash
git commit -m "first commit"
````


oneliner updates for readme
````bash
git add . && git commit -m "update Readme.md"
````

git remote add origin https://github.com/dhruvthakur2000/winequality.git

git branch -M main

git push origin main

tox command -

tox
for rebuilding -

tox -r 
pytest command

pytest -v
setup commands -

pip install -e . 
build your own package commands-

python setup.py sdist bdist_wheel