#### [SIP]

#### Run

```
python3 -m venv .env
source .env/bin/activate
pip install -r requirements.txt
jupyter notebook
```
For every asg, I will create an env for it because I want to avoid installing dependencies globally on my machine; installing them in a virtual environment would be a good choice (or use docker). so the above commands simply:

- create virtual environment and put it in `.env/` folder
- activate the virtual environment
- install dependencies in virtual environment
- run it with jupyter

To exit the virtual environment, just simply use the command:
```
deactivate
```
