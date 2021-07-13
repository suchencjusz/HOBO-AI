# HOBO-AI
Yolov3 trained for hobo detecting!

![HOBO1](Data/Source_Images/Test_Image_Detection_Results/55952395_131899731224288_2004428621272347184_n_catface.jpg)
![HOBO1](Data/Source_Images/Test_Image_Detection_Results/55932476_418338645396572_7530062542719424614_n_catface.jpg)

## How to use:

#### Setting up Virtual Environment [Linux or Mac]

Clone this repo with:
```bash
git clone https://github.com/suchencjusz/HOBO-AI
cd HOBO-AI/
```
Create Virtual **(Linux/Mac)** Environment:
```bash
python3 -m venv env
source env/bin/activate
```
Make sure that, from now on, you **run all commands from within your virtual environment**.

#### Setting up Virtual Environment [Windows]
Use the [Github Desktop GUI](https://desktop.github.com/) to clone this repo to your local machine. Navigate to the `TrainYourOwnYOLO` project folder and open a power shell window by pressing **Shift + Right Click** and selecting `Open PowerShell window here` in the drop-down menu.

Create Virtual **(Windows)** Environment:

```powershell
py -m venv env
.\env\Scripts\activate
```

Probably you will have to enable execution of PowerShell scripts (admin right required) 

```
Set-ExecutionPolicy unrestricted
```

![PowerShell](/Utils/Screenshots/PowerShell.png)
Make sure that, from now on, you **run all commands from within your virtual environment**.

#### Install Required Packages [Windows, Mac or Linux]
Install required packages (from within your virtual environment) via:

```bash
pip install -r requirements.txt
```
If this fails, you may have to upgrade your pip version first with `pip install pip --upgrade`.

Make sure you are using python 3.7.8, you can change this in env config file

```
home = C:\Program Files (x86)\Microsoft Visual Studio\Shared\Python37_64
include-system-site-packages = false
version = 3.7.8
```
(of course you need to install this version https://www.python.org/downloads/release/python-378/)
