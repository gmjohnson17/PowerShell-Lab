# Purpose
This Jupyter notebook was developed to assist students with learning how to script using PowerShell.

This README contains instructions to setup using VSCode (use the .dib file) or Jupyter notebooks (use the .ipynb file). Both setups are acceptable.

# Prerequisites - All

1. PowerShell 7 for Windows (7.3): https://learn.microsoft.com/en-us/powershell/scripting/install/installing-powershell-on-windows?view=powershell-7.3

2. .NET SDK: https://dotnet.microsoft.com/en-us/download

# Setup

## VSCode Setup

1. Download VSCode from Microsoft or via the Microsoft Store (Windows users): https://code.visualstudio.com/

2. Open VSCode

3. Go to Extensions (CTRL + SHIFT + X)

4. Install the PowerShell Extension

5. Install the .NET Extension Pack (includes Jupyter, Polyglot Notebooks,  and .NET Runtime Kernel)

6. Install the Python Extension

7. Download this repository to a new folder

8. Open this repository: File > Open Folder > Select the Folder you saved this repository to

9. Use the .dib file

You can now create and use .dib files and run the PowerShell 7 terminal in VSCode:

![image](https://github.com/gmjohnson17/PowerShell-Lab/assets/146036376/3c4326ea-addc-4668-9dd8-167b8d0af505)

Note: VSCode does not automatically save your work. Do not forget to save any changes before closing.

## Jupyter Notebook Setup

1. Download Python 3.11 (or later): https://www.python.org/downloads/ 

2. Open PowerShell
   
3. Install powershell_kernel using the following command:
```
pip install powershell_kernel
```

4. Register the powershell_kernel with the jupyter lab using the folloing command:
```
python -m powershell_kernel.install
```

5. Download this repository to a new folder

6. Navigate to the respository folder in PowerShell

7. Open Jupyter Lab:
```
jupyter lab
```

8. The PowerShell Kernel should now be registered and you should be able to open the notebook (.ipynb file). 

![image](https://github.com/gmjohnson17/PowerShell-Lab/assets/146036376/fdbc7cc9-2b06-4663-b160-58129fdd0c3f)

### Troubleshooting Jupyter Notebook Setup

If you cannot get the program "pip" or "python" to run, you may need to adjust your Execution path. This can be done with the following command and restarting PowerShell:
```
setx PATH "%PATH%;C:\Users\graha\AppData\Local\Programs\Python\Python311\Scripts\;C:\Users\graha\AppData\Local\Programs\Python\Python311\"
```

Note: the %% represents the path to the Python folder. It may vary based on your install location and Python version. If you have Anaconda, Miniconda, or another version of Python installed, you may need to have more execution paths.

# Contributors
Author: Graham Johnson

Reviewer(s): Troy Drabek

I am not accepting any contributions at this time.

# LICENSE

Copyright 2023 Graham Johnson

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
