# Object-Detection-Project. 
- Open these two links to follow along: <br/>
![link1](https://www.tensorflow.org/install/pip), ![link2](https://tensorflow-object-detection-api-tutorial.readthedocs.io/en/latest/install.html#general-remarks) 

Step 1 
- Install Ubuntu 18.04 LTS for your VB here: https://ubuntu.com/#download
- Allocate at least 20gb of space.
- Make sure hardware settings in VB are reasonably high.
- During installation, select "minimal installation" and uncheck "Download updates while installing Ubuntu".
- Once finished, open the terminal and run `sudo apt install linux-headers-$(uname -r) build-essential dkms`
- On the top left of your VB menu, select \Devices\Insert Guest Additions CD...\
- Click "Run" when the pop-up comes.
- Once finished, go to the top right corner of Ubuntu and click the on/off symbol, then click "Power Off".
- Now, in your VB, go to \Settings\General\Advanced\ to set "Drag'n'Drop" and "Shared Clipboard" to Bidirectional. 
<br/>
Optional: <br/>
Adjust screen resolution by going to \Settings\Devices\Resolution\. <br/> 
To fit display into screen, set VM to scaled mode.
<br/>
<br/>

  
 Step 2
 - Install "Anaconda Python 3.7" for Linux with https://www.anaconda.com/distribution/
   > Remember to select the right distribution (Linux) because the default download link is for Windows.
 - Verify complete installation by following the instructions in https://docs.anaconda.com/anaconda/install/linux/
   > If the hash code doesn't match, delete everything from Step 2 and try Step 2 again.
 - Check its version by typing `python3 --version`. Python has to be > 3.4.
   > In my case, I had version 3.7.3.
 
***TIP*** 
Instead of typing the entire .sh file one by one, press tab to have everything typed out for you; with the condition that you're in the directory that has that file (In our case, it's in Downloads)

 Step 3
 - Install Tensorflow by following the instructions under "Tensorflow CPU"
   > We didn't choose to go with "Tensorflow GPU" due to hardware limitations.
   
   > The part where it says, "Once you have activated your virtual environment, the name of the environment should be displayed..." doesn't apply to us since we're not using Windows.
 
 - In the midst of  following the guide, you might encounter an error from typing the code below.
 
 ![screenshot_1](sc1.png)
 
 > It's ok. Don't stress out. The error has something to do with compatibility of tensorflow and python. Just proceed to the next step.
 
 - Prior to installing Tensorflow, we need to satisfy several software requirements; that is, we need to install some packages to ensure tensorflow runs.
 
 - Begin by opening/using your terminal window (Ctrl+alt+T) and type `pip install --upgrade pip`. *pip version must be >= 19.0
 > In my case, the latest version of pip is pip-19.2.3. 
 
 - Then, type `pip install tensorflow`. If the terminal tells you that the requirement is already satisfied, good! If not, fix it by installing the required packages by `sudo apt install name-of-missing-package-or-file`.
 
 - Install virtualenv by typing `sudo apt install virtualenv` in your terminal.
 
 - Ensure latest installation by copy/pasting the following the command into your terminal: <br/>
  `sudo apt install python3-dev python3-pip` <br/>
  `sudo pip3 install -U virtualenv` <br/>
  
  Step 4
  - Creating your virtual environment
  
  

   
 
 
 
 
 
 
 
 
 
 
 
   
