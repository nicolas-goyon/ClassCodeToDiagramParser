# ClassCodeToDiagramParser

Currently using able to parse a C# project to either Mermaid or PlantUML.


## Quickstart :
### Install requirements 
```py
pip install -r requirements.txt
```

### Config

Edit the config.json to ensure the options are what you want.
The exclude files and namespaces can be specially usefull for removing the tests functions.

### Starting the parsing
```py
python execution.py ../path/to/project/ ./config.json
```