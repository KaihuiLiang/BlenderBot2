# BlenderBot2

## Requirement
`pip install parlai==1.3.0`

## Retriever
Custom retriever defined in `web_retriever.py`
Download `geckodriver` and put it under `usr/local/bin` 
https://github.com/mozilla/geckodriver/releases

## Agent
The main agent: `BlenderBot2FidAgent(opt)`

Load the config with the following:

```python
with open("blenderbot2-3B.json") as f:
    opt = json.load(f)
```
