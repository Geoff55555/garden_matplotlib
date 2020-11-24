# Local garden.matplotlib 

## What ?
garden.matplotlib fork to use it as a local python lib directly into your main.py directory

## Why ?
If Kivy Garden matplotlib integration is not installable with pip command for you as for me.
See : https://stackoverflow.com/questions/57563337/why-cant-i-install-kivy-garden-garden-matplotlib-using-pip

*The graph repo has the necessary code to be installable via pip, while the garden.matplotlib repo does not.

I think the matplotlib one may be waiting to be converted to a new-style garden flower, which is designed to be pip-installable.*

***A workaround would be to just copy the matplotlib one into your app dir and import from there.***

This is a simple solution used for a project in order to have garden.matplotlib to work.
As it's done, just wanted to share it.

## How to use ?
To call the lib, change the '.' (from documentation with original lib) with '_' as in :
from garden_matplotlib.backend_kivyagg import FigureCanvasKivyAgg

Enjoy