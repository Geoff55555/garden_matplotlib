# Local garden.matplotlib 

## What ?
garden.matplotlib fork to use it as a local python lib directly into your main.py directory

## Why ?
Kivy Garden matplotlib integration is not installable with pip command.
This is a simple solution used for a project in order to have garden.matplotlib to work.
As it's done, just wanted to share it. Enjoy :)

## How to use ?
To call the lib, change the '.' (from documentation with original lib) with '_' as in :
from garden_matplotlib.backend_kivyagg import FigureCanvasKivyAgg

Enjoy