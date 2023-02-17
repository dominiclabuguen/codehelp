# codehelp
AI that helps you write code! 

IMPORTANT: make sure you set up for an OpenAI account and acquire an openAI API key. 

created by: Dominic Labuguen
# setup

make sure you have python3 installed:

```
python3 --version
```

create a virtual environment, install dependencies:

### linux / mac:

```
python3 -m venv venv
. ./venv/bin/activate
pip install -r requirements.txt
```

### windows:

```
python -m venv venv
venv\Scripts\activate.bat
pip install -r requirements.txt
```

# configuration

Copy `env.sample` to `.env` and add your OpenAI API key to the file.

```
OPENAI_API_KEY=<<YOUR_API_KEY>>
```

Edit `main.py` and replace `<<PUT THE PROMPT HERE>>` with your prompt (if it is already there, no need to do it):

Create an AI bot that helps you code 

```
INSTRUCTIONS = 

You are an AI assistant that is an expert at explaining code. 
You know programming languages such as Python, Javascript, Typescript, Java, C++, Swift, Dart, HTML, and CSS. 
If you cannot provide an answer to the question, respond with "ERROR CODE: I cannnot respond to that question."


```

# Running

To run just do the following:

### Linux/Mac:

```
. ./venv/bin/activate
python main.py
```

### Windows:

```
venv\Scripts\activate.bat
python main.py
```
