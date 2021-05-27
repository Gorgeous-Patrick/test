# How to be a qualified SilverFOCSer
Don't Cry, it's easy.

Your manager just asked you to modify the homepage of the SilverFOCS Official website... Yeah.. indeed, it is ugly.. 

## Get your toolbox ready!
The manager will be ANGRY if you don't get them ready.. You will be fired!!

WHAT!!! You haven't installed git extensions on VSCode?? you dare you don't!

Use VSCode or WebStorm to view all the files in this workshop.

## READY? Let's GO

Maybe.. Just maybe, your managers have created a place, a repository? Then you just need to 
```bash
git clone <URL of the repo>
```
BUT! BUT!! Managers are unhappy! You need to create the git repo yourself (CRY):
```bash
mkdir "i_love_SFOCS"
cd "i_love_SFOCS"
git init
```
Let's move this file into the repo directory. Then, run :
```bash
git add task1.md
git commit -m "The start of a hard journey"
```

YAAAY! You got a place to store your code on your computer! But!! Your disappointing managers just yelled at you that THEY WANT TO SEE THE CODE TOOOO!(CRYYY)

Luckily, you can create a repo on gitea... But.. it is empty?

By Asking ~~Baidu~~ Google, you found this:
```bash
git remote add origin <URL of the repo>
git push -u origin master
```

As a new SilverFOCSer, you might not understand what does those weird commands mean ;-<. But don't worry, you will understand it.

[Go to the next task!]