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
(venv) git clone git@github.com:alexzubkoff/xblock-customized.git
(venv) cd xblock-customized
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
