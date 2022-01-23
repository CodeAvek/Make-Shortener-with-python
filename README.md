## CodeAx

 - [Telegram](https://t.me/avekgaming)
 - [instagram](https://instagram.com/codeax1?utm_medium=copy_link)
 - [Youtube](https://youtube.com/channel/UC-Q6ZcOtcx1gZ9fI5MDDt3w)


## Features

- Python Url Shortener is for to short long url 
- 6 to 7 line of Code Can Make a Link Shortener from Python
- Small Python Project For Beginners Students
- Cli Run from terminal


## Deployment

```bash
#Need to Installed Python in your Computer 
#Need to Installed Vscode Or Any Code Editor
#Open terminal or cmd Install python library That is - pip insall pyshoteners


# import pyshorteners

# link = input("Enter The Link :")

# s = pyshorteners.Shortener()

# CodeAx = s.tinyurl.short(link)

# print(CodeAx)

import pyshorteners
while (True):
    a = input("Press q To Quit And 1 to Start The Link Shortener:")
    if a.lower() == "q":
        print("Thank You For Using this")
        break
    elif a == "1":
        a = '''    Welcome To Link Shortener
    Here We Short Long Link
    Made by CodeAxAvek'''
        print(a)
    else:
        continue


    link = input("Enter The Link :")
    s = pyshorteners.Shortener()
    print("Your Link has Generated Succesfully")
    print(s.tinyurl.short("Copy Your Link--",link))

```

