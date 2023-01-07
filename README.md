# python-file-converter-exe
do you ever think what if I send some of my python projects to a person that doesn't have python install on their pc . what will happen? 


HOW IT IS WORK :
1- first of all you need to install "pyinstaller" library , you can install it with the below commands :
        Mac OS : pip3 install pyinstaller
        Linux : ppython3 -m pip install pyinstaller   
        Windows : pip install pyinstaller 
2- after that open up terminal/CMD
3- then go to your python file directory that you want to convert , for that execute this command in your terminal/CMD:
        cd User/YourName/Desktop/Project-Folder
4- replace User with your pc username , replace YourName with your name and ...
5- and after that type this command in your terminal to convert the file to .exe file :
        pyinstaller -F file-name.py
6- then you should see a succesful message in terminal if you see that close terminal
7- and as you can see pyinstaller created a folder in your project directory named "dist".
8- open that and you will see your .exe file waiting fo you :D 
