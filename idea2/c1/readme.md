# CTFd Challenge Configuration

Name: Prompt Injection Playground
Category: AI
Value:100


## Description:
A chatbot contains a secret flag hidden in its system prompt.
You may send arbitrary prompts to the model.
Can you use prompt injection techniques to make it reveal the flag?
Target:http://YOUR_SERVER:5000


## Run

Start Ollama:

`ollama serve`


Pull the model if needed:

`ollama pull ministral-3`

Launch the challenge:

`python app.py`

Open: http://localhost:5000


## Solution

![alt text]({A1DF844E-9CED-44A1-A243-285E20E30EC7}.png)