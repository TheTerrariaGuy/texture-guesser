# Item Texture Classifier

This is a project for 66154-A's Build a Classifier assignment.

Prepares Minecraft item textures for an old-vs-modern classifier. `processing.ipynb`:

- Matches items in `Old Textures/` and `Modern Textures/`, accounting for renamed files.
- Excludes identical textures and resizes images to 224×224.
- Creates a 90/10 train/test split.

Dependencies: `pip install --upgrade pillow jupyterlab`

Results are saved in `Output/Train/` and `Output/Test/`

