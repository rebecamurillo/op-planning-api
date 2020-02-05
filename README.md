# op-planning-api

Python flask API for OpPlanning
Tutorial for Visual Studio Code : https://code.visualstudio.com/docs/python/tutorial-flask
Flask tutorial : https://flask.palletsprojects.com/en/1.1.x/quickstart/


App index is on app.py

To install python and python virtual environment  : 
sudo apt-get install python3   
sudo apt-get install python3-venv   


TO INSTALL PROJECT : 
1. Install virtual environment and dependencies on startup
python3 -m venv .env

2. Install flask 
pip3 install flask 

3. Install dependencies
pip3 install -r requirements.txt


TO START APPLICATION : 
1. Open virtual environment venv .env (if not done by IDE): 
source .env/bin/activate

2. Run application : 
python3 -m flask run


TO ADD A DEPENDENCY : 
1. install new library
pip3 install <lib...>

2. update requirements.txt file
pip3 freeze > requirements.txt

