# codehelp
AI that helps you write code! 

created by: Dominic Labuguen
# Setup

Make sure you have python3 installed:

```
python3 --version
```

Create a virtual environment and install the dependencies:

### Linux/Mac:

```
python3 -m venv venv
. ./venv/bin/activate
pip install -r requirements.txt
```

### Windows:

```
python -m venv venv
venv\Scripts\activate.bat
pip install -r requirements.txt
```

# Configuration

Copy `env.sample` to `.env` and add your OpenAI API key to the file.

```
OPENAI_API_KEY=<<YOUR_API_KEY>>
```

Edit `main.py` and replace `<<PUT THE PROMPT HERE>>` with your prompt:

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
