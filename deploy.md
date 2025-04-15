python setup.py sdist bdist_wheel

pip install twine

twine upload dist/*


pip install --upgrade CodeToClassDiagram

code2class ./HUBLoader/ ./config.json