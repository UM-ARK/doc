# manual create club 
file name: create_club.py

## Description:
 To create/register new Club
 
# How to use?
enter the below command in terminal
```
> python manage.py shell
>>> exec(open('data/create_club.py').read())
>>> main()
```

# Example for use
in terminal:
```
(venv) PS C:\Users\Tony\Documents\GitHub\UM-All-Backend> python manage.py shell
Python 3.10.5 (tags/v3.10.5:f377153, Jun  6 2022, 16:14:13) [MSC v.1929 64 bit (AMD64)] on win32
Type "help", "copyright", "credits" or "license" for more information.
(InteractiveConsole)
>>> exec(open('data/create_club.py').read())
>>> main()
Sign up for Club now
Please enter the corresponding information one by one when prompted
account:Photography_Society 
=======================================
name:攝影學會                          
=======================================
please only input: N/A / SA / CLUB / SOCIETY / COLLEGE / OFFICIAL / MEDIA / BUSINESS / 
tag:CLUB
=======================================
logo path:C:\Users\Tony\Pictures\umclub\Photography_Society.png
=======================================

Added club successfully.
/------------------------------------------\
|ID:  8a23bcfe-26e6-4fdf-83fb-0130a5f014dd |
|account:  Photography_Society             |
|password:  NqBE9Lry                       |
\------------------------------------------/