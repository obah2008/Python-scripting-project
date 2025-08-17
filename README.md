# Python-scripting-project
## Objectives
- Create a python script that does the following:
 1. Finds all the game directories from /data directory
 2. Create a new /games directory 
 3. Copy and remove the "game" suffix of all games into the /games directory

- Create a .json file with the information about the games

- Compile all of the game code to a single .py file

- Run the compiled game file 

### Detailed step by step Solution
Watch full detailed guide [here](https://www.youtube.com/watch?v=dQlw1Cdd3pw&t=600s)

Step one: Create a new .py file in Python-Scripting mo
Step two: Import the modules that will be used in the script
```python
import os
import json
import shutil
from subprocess import PIPE, run
import sys
```
