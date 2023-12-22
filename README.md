First, install Python using Anaconda 

1. 
- Installing Anaconda (Full Version)

--For Both Mac and Windows:
---Go to https://www.anaconda.com/download
---Download Anaconda Installer:
    Run the Installer:
        On Windows:
            Double-click the .exe file and follow the instructions.
        On macOS:
            Double-click the .pkg file and follow the installation prompts.

    Verify Installation:
        Open a new Terminal (macOS) or Command Prompt (Windows).
        Type conda list.

2. 
- Download the code in this repository
--click on the green <> Code button and choose how to dowload the code
--- make note of the directory location of ecn310, in the example below the folder in in your home directory called "YourUsername"
--all the packages you need are in the environment file. Open a terminal in mac or navigate to the command prompt in windows

windows:

cd C:\Users\YourUsername\ecn310

mac:

cd /Users/YourUsernome/ecn310 

type: 

conda env create -f ecn310_environment.yml

now you can open any of the .ipynb files by clicking on them in filebrowser or your can type jupyter notebook in the terminal to get started
