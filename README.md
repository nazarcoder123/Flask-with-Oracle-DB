# To Run this repo
 git clone https://github.com/nazarcoder123/Flask-with-Oracle-DB.git

 create python env with python --version == 3.10.0

 pip install -r requirements.txt

 # open your oracle database run the below query

 CREATE TABLE guests (
    id SERIAL PRIMARY KEY,
    name VARCHAR(80),
    email VARCHAR(120)
);

# Then open VS code terminal then run then below command
 flask run