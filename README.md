 # Run this in terminal:
 ```
 python -m venv .venv
```
## Install dependencies:
 ```
 pip install fastapi uvicorn requests python-multipart jinja2
```
---
## After you install Ollama:
```
ollama serve
```
---
## Run the model:
```
ollama run smollm2:135m
```
---
## Run the server:
```
uvicorn main:app --reload
```
---
# Open this link In Browser:
```
http://127.0.0.1:8000
```
