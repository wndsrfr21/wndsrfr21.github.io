Interested in getting the Kandy SMS API working in Python? Maybe you want to send an SMS from an old laptop or a Raspberry Pi device that is rigged to detect a change in the environment (movement/temperature/light/etc). This Python library will help get you going quickly and with minimal installation requirements.

The file [KandySMSPython.py](https://github.com/wndsrfr21/KandySMSPython/blob/master/kandy_sms_demo.py)(https://github.com/wndsrfr21/KandySMSPython/blob/master/kandy_sms_demo.py) will help get you started with minimal effort as all the necessary code is there and you only need to make a couple of minor modifications. 

Make sure the following three items are taken care of before running the code:
1) Get Your API Keys - Lines 5 & 6 - Create an account on http://developer.kandy.io/ and copy out the "domain api key" and "domain api secret" into lines 5 & 6 within the KandySMSPython.py file
2) Update the destination phone number - Line 29 - Make sure the format of the number is +1xxxYYYzzzz
3) Make sure Python is installed - https://www.python.org/
4) Make sure Python Requests is installed - http://docs.python-requests.org/en/master/

Running the KandySMSPython.py code:
1) Open a Terminal Console (Mac/Linux/Unix) or command prompt (Windows)- press the command button and the space bar and then type "terminal" within the new popup or follow this tutorial for Mac (http://www.wikihow.com/Open-a-Terminal-Window-in-Mac) or this tutorial (http://www.digitalcitizen.life/7-ways-launch-command-prompt-windows-7-windows-8) for Windows
2) Navigate to the folder containing the file called "KandySMSPython.py"
3) Type the command "python kandysmspython.py" and hit enter

The system will think for couple of seconds and then the destination number should get a text message!

<font color=#ffb6c1>Questions? Please setup time via http://www.alexanderdonn.com for help!</font>

