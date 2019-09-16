# Password-Generator
We can generate the password file with social engineering using pycharm and we can use the generated file for crack password.
Password generation using social enginering,


# steps,
## 1. It works in windows, linux.
## 2. Install python 3,
https://www.python.org/ftp/python/3.7.4/python-3.7.4.exe

after installation of python, Check python
### Open Command prompt,


Microsoft Windows [Version 6.1.7601]
Copyright (c) 2009 Microsoft Corporation.  All rights reserved.

:

    C:\Users\Username*-PC>python
    Python 3.7.4 (tags/v3.7.4:e09359112e, Jul  8 2019, 20:34:20) [MSC v.1916 64 bit(AMD64)] on win32
    Type "help", "copyright", "credits" or "license" for more information.
    >>> A=1
    >>> B=2
    >>> C=A+B
    >>> C
    3
    >>> exit()



## 3. Install Pycharm
https://www.jetbrains.com/pycharm/download/download-thanks.html?platform=windows
open this link it will directly redirect you to Pycharm intallation file.

install downloaded file from, (pycharm-professional-2019.2.1)

Open, JetBrains PyCharm 2019.2.1 x64
Click, File-->New Project-->Location (C:\Users\Username*\PycharmProjects\PassGenerator) Project Name: PassGenerator
click Create, Use this windows or New windows
It will create Virtual environment.

after created the PassGenerator project,
Right click the PassGenerator, click new, select Python File,
Give file name (Password) in Python file
it will create the python file name as Password.py in PassGenerator project.

Double click the Password.py file in PassGenerator project.

Type further lines,

:

    from itertools import permutations
    for item in permutations('GOKULgokulSIsiZER0', 15):
    print(''.join(item))

### Note: 
('A to Z, a to z, 0 to 9, any symbols', Password digits if known or <15)
or 


If we already known the social engineer of his/her password like,
#### Name: Princy
#### Surename: Albert
#### NickName: Puppy
#### DOB:19980604
#### Others: Lovely, Cutie, Teady, Qwertyuiop, BoyfriendName and DOB, etc
note,
if we have 2 same letters no need add again but we need to add it both Uppercase and Lowercase like,

For Example,
:

    for item in permutations('PRINCYALBETUOVLDQW198064', 13):

save the project and right click the Password.py in PassGenerator project, then click Run. 
While running project, Automattically passwords will generate., and also it will visible in bottom of the screen.

After completed the generation the password file is stored in PassGenerator project located in 
C:\Users\Username*\PycharmProjects\PassGenerator\venv
