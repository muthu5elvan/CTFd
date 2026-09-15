# Run

Start Ollama:

`ollama serve`


Pull the model if needed:

`ollama pull ministral-3`


Create Virtual Environment

`python -m venv _venv`

Install the requirement

`pip install -r requirements.txt`

Enable the virtual environment

`(Set-ExecutionPolicy -Scope Process -ExecutionPolicy RemoteSigned) ; (& .\_venv\Scripts\Activate.ps1)`


Launch the challenge:

`python app.py`

Open: http://localhost:5000

