# Train scheduling  

This repo contains some researches in order to solve the [Flatland Challenge](https://www.aicrowd.com/challenges/flatland-challenge).  

![](https://github.com/guerinsylvain/train-scheduling/blob/master/docs/flat-land-demo.gif)  


[Abstract](#abstract)  
[Setup](#setup)  
&nbsp;&nbsp;&nbsp;[Install and configure Python](#setup-python)  

<a id="abstract"></a>
## Abstract
The [Flatland Challenge](https://www.aicrowd.com/challenges/flatland-challenge) is a competition to foster progress in multi-agent reinforcement learning for any re-scheduling problem (RSP). The challenge addresses a real-world problem faced by many transportation and logistics companies around the world (such as the Swiss Federal Railways, SBB. Different tasks related to RSP on a simplified 2D multi-agent railway simulation must be solved. Your contribution may shape the way modern traffic management systems (TMS) are implemented not only in railway but also in other areas of transportation and logistics. This will be the first of a series of challenges related to re-scheduling and complex transportation systems.  

The research group at SBB (Swiss Federal Railways) has developed a high-performance simulator which simulates the dynamics of train traffic as well as the railway infrastructure. Different approaches for automated traffic management systems (TMS) are currently under investigation. The role of the traffic management system is to select routes for all trains and decide on their priorities at switches in order to optimize traffic flow across the network.

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
