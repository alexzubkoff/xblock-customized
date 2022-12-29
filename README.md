# XBlock: CollapsibleXBlock
## _Customization of new XBlock_


## Installation

XBlock requires Python 3.8+ to run.
Create a Directory for XBlock Work:
```sh
mkdir xblock_development
cd xblock_development
```
Create and Activate the Virtual Environment:
```sh
python -m venv venv
venv\Scripts\activate
```
Clone the XBlock (after Git installation):
```sh
(venv) git clone git@github.com:alexzubkoff/xblock-customized.git .
(venv) cd xblock-sdk
```
Install requirements:
```sh
(venv)  pip install -r requirements/base.txt
(venv)  cd ..
```
Create the SQLite Database:
```sh
(venv) python xblock-sdk/manage.py migrate
```
Run the XBlock SDK Server:
```sh
(venv)  python xblock-sdk/manage.py runserver
```

![1](https://user-images.githubusercontent.com/22620680/209990443-d5e4e1f1-eb5b-41a5-b542-bf8f2bd6b9c1.png)
![2](https://user-images.githubusercontent.com/22620680/209990445-0e321097-5744-4e24-a1e7-1c1860a83250.png)
![3](https://user-images.githubusercontent.com/22620680/209990447-cb1798fb-90bd-42e1-8bdf-c5756b0b400c.png)
![4](https://user-images.githubusercontent.com/22620680/209990448-63119972-d5ca-43e8-99d5-1f351ae49aa0.png)

