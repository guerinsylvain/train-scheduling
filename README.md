# train-scheduling  

![](https://github.com/guerinsylvain/train-scheduling/blob/master/docs/flat-land-demo.gif)  


[Setup](#setup)  
&nbsp;&nbsp;&nbsp;[Install and configure Python](#setup-python)  

<a id="setup"></a>
## Setup

<a id="setup-python"></a>
### Install and configure Python 
1.  Install [Python 3.7 or later](https://www.python.org/downloads/).
2.	From the root folder of the project, type 
    ```
    pip install virtualenv
    ```
3.	Then type
    ```
    virtualenv --python="C:\Users\[YOUR USER NAME]\AppData\Local\Programs\Python\Python37\python.exe" venv      
    ```
    This will create a venv subfolder.   
    Note that the path to the python.exe (v3.7) may vary on your machine.
    If python has been installed with visual studio, you may have something similar to this:
    ```
    virtualenv --python="C:\Program Files (x86)\Microsoft Visual Studio\Shared\Python37_64\python.exe" venv
    ```
4.	From the root folder of the project, activate the virtual environment by typing:
    ```
    .\venv\Scripts\activate.bat
    ```
5. Install packages:
    ```
    pip install -r requirements.txt   
    ```
6. Test flatland
    ```
    flatland-demo
    ```  
