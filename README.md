# bpy-workshop


1. uv init
2. uv pip install jupyterlab pandas
3. uv run jupyterlab


4 hours

* .25 Notebooks
* .25 basic objects

Task:

1. make a diagram of 10 random values and add them using bpy
2. now, same idea, but this time, use empty object. Place them to coordinates, and then fill them with data attributes.


Installation instructions:
````py
# Install Blender from https://www.blender.org/download/
# Install uv 
curl -LsSf https://astral.sh/uv/install.sh | sh
mkdir blender_python_workshop && cd blender_python_workshop
uv venv --python 3.11
uv pip install jupyterlab blender_notebook
uv run blender_notebook install --blender-exec="/Applications/Blender.app/Contents/MacOS/Blender"
uv run jupyter lab
``` 