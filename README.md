# Purpose
This Jupyter notebook was developed for Undergraduate Cyber Warfare (UCWT) students to as an optional exercise to accompany instruction for the 17X Block III course, PowerShell

Understanding this code and completion of these exercise does not constitute sufficient preparation for the completion of the 17X course.

# Prerequisites

The most current version of Python (3.11 at the time of commit): https://www.python.org/downloads/

The most current version of PowerShell 7 for Windows (7.3): https://learn.microsoft.com/en-us/powershell/scripting/install/installing-powershell-on-windows?view=powershell-7.3

The most current version of .NET SDK (blocked on AWAKEN): https://dotnet.microsoft.com/en-us/download

# Localhost Setup

1. Open PowerShell
   
2. Install powershell_kernel using the following command:
> pip install powershell_kernel

3. Register the powershell_kernel with the jupyter lab using the folloing command:
> python -m powershell_kernel.install

4. To open a new Jupyter Lab, run:
> jupyter lab

5. The PowerShell Kernel should now be registered and you can make or open a PowerShell Notebook:

![image](https://github.com/gmjohnson17/PowerShell-Lab/assets/146036376/fdbc7cc9-2b06-4663-b160-58129fdd0c3f)

## Troubleshooting

If you cannot get the program "pip" to run, you may need to adjust your Execution path. This can be done with the following command and restarting PowerShell:
> setx PATH "%PATH%;C:\%%\Python\Python311\Scripts\"

Note: the %% represents the path to the Python folder. It may vary based on your install location

If you cannot get "python" to run from PowerShell, you may need to adjust your Execution Path again to:
> setx PATH "%PATH%;C:\%%\Python\Python311\"

# Online Setup

## Google Colab

You can run the Notebook online using Google Colab (Google Account required to edit/run) here: https://colab.research.google.com/?utm_source=scs-index

You can either download the notebook locally and upload it or link directly to this GitHuh: https://github.com/gmjohnson17/PowerShell-Lab/

To link to this GitHub select File > Open > GitHub > Paste the above link > Select the Notebook

![image](https://github.com/gmjohnson17/PowerShell-Lab/assets/146036376/a46357e8-2251-47b7-b485-6bdf47134f43)

# Contributors
Author: Graham Johnson

Reviewer(s): Troy Drabek

I am not accepting any contributions at this time.

# LICENSE

Copyright 2023 Graham Johnson

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
