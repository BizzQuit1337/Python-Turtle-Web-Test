Brython online interpreter with python turtle
**********************************************
Developer Albert Brown
**********************************************
The main file is turtle.html, this is were all the logic for the interpreter
is placed and handeled. The upload.html is still a work in progress and aims to 
be a popup solution instead of a whole page.

All .js files that are in the folder are for supporting the interpreter
and its functionality 

Please keep all files in the same folder as to ensure the interpreter works properly
**********************************************
This programme is a working online version of python 3 with the imported
module pyturtle, you can either programme fully in basic python 3 with 
its full standard library or using the python turtle module.

The turtle module draws to a div element named turtle-div, moving this element
will alter were the turtles are drawn

for adding additional modules navigate to the turtle.html and add inside 
<script type="text/python"> code goes here </script> the import as 
from browser import document then add import <module name> on the next line
provided the module only uses python files it will be readable, if the module
doesnt use only python files it will not work.
