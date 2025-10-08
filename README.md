# adp-template

## Setup

Setup a virtual environment and install dependencies using:

```bash
pyenv local 3.13.5
python -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
```

Setup .env file, if needed: 

```bash
echo "KEY=value" > .env
```

E.g. with "GOOGLE_API_KEY" or "OPENAI_API_KEY". 
