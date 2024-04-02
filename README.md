# Setting up Jupyter Notebooks

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/38/Jupyter_logo.svg/1767px-Jupyter_logo.svg.png" width="250" height="250">

## Install pip

Python's package manager, pip is essential for installing packages and related applications. 

### Windows/MacOS Setup
1. Download the most recent version of Python for either [Windows](https://www.python.org/downloads/) or [Mac](https://www.python.org/downloads/macos/)
2. Upon opening the install wizard, ensure that under "optional features" that, "pip" is checked
   ![pythoninstall](https://github.com/Okanagan-iGEM/drylab-2024-training/assets/77037153/459cfb4e-51a7-471d-8c4f-c324860c4245)

   For those running MacOS, similarly go through each step in the installation file and pip should be included


3. Open the command prompt by running "cmd" after pressing ```Windows + R``` together.   
![cmdrun](https://github.com/Okanagan-iGEM/drylab-2024-training/assets/77037153/50dcbf64-91b3-4ea5-a68b-5b766c6ea7c0)

   For MacOS, type ```terminal``` in the search window
   
4. Double check that pip has successfully been installed by running the following command
   ```
   >pip --version
   ```
5. Your expected output should be as follows. The version of pip will be printed along with the file path where pip was installed.
   ![image](https://github.com/Okanagan-iGEM/drylab-2024-training/assets/77037153/4d28d771-2f54-4fec-8246-3d5cb00d614a)

6. Congrats on installing pip! Next run the following command with pip to install Jupyter Notebook
   ```
   >pip install notebook
   ```
7. Once the files have completed installation, you may run Jupyter Notebook from the command line anytime by simply writing the following
   ```
   >jupyter notebook
   ```
   **Note:** You can cancel this process anytime by pressing ```CTRL + C ``` from the command prompt window
8. Jupyter Notebook will immediately open on your browser. To create a new file, click on ```New``` and ```Python 3(ipykernel)```
   ![newjupyter](https://github.com/Okanagan-iGEM/drylab-2024-training/assets/77037153/e949f8e5-05bd-4116-adc3-5b4b1998a14d)
9. Congrats! You can now officially begin writing Python code!!
    ![image](https://github.com/Okanagan-iGEM/drylab-2024-training/assets/77037153/5320c5f1-b13b-4443-815d-9c6023ffe5c4)

