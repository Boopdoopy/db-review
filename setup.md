#Setting up your computer...₳ʕ´ᴥ`ʔ

###THE SHELL

In order to set things up you're going to need to use the shell.
A shell is just a fancy way of saying interface. You've been using
a shell every time you've used a computer it's just been a GUI
which is a **Graphic User Interface**. GUI's are great for keeping 
the computer out of your business but we'll need to get in your 
computer's business to set up so we'll have to use a **command line** shell which is text only.

On Mac you have 2 options:

* You can use mac's built in Terminal (which is already on your computer) which you can find quickly with the spyglass(🔍) and
typing 'terminal' 

    OR 

* You can use the vastly superior (aesthetically) iTerm which you can download [here](https://www.iterm2.com/)

I've made my preferences clear and won't be too sad if you choose
terminal. ・ﾟﾟ₳ʕ>ᴥ<ʔ・ﾟﾟ 
(they're really the same I just hate not having color options lol)


###THE COMMAND LINE

We're going to be working from the command line mostly so anytime
 something begins with a **'$'** that means it's a command you 
 type in the terminal. You don't include the **'$'** that's just 
 the common notation for a **terminal command**.

The language we'll be using is 'Bash' it's one of the oldest
languages and it's the basic system language of MAC and LINUX.

Bash's convention is to succeed silently. This means if a command 
works unless you asked your computer to say something it will only
print out if you get an error. Errors are less scary here and are 
closer to a really lame spellcheck. Most of the time it just won't
understand you or won't find something you're looking for. There
are only a couple things that are more dangerous than dragging
and dropping folders and they are not necessary for our purposes.


******
###FEEL FREE TO IGNORE
if you want to dig in more [here](https://cdn.hashdoc.com/docs/d8c0fa45a6d7cb222e1283ab3ca8432e/images/728x/linux-bash-shell-cheat-sheet-2.png) is the cheatsheet I use sorry
for the poor image quality 

(this may feel overwhelming (it still is to me too) but you don't
 need to remember ANY of this lol no one remembers any of this
  stuff unless they use it everyday. All of my instructors and
 every programmer I've met just have the Library of Alexandria in 
 their chrome bookmarks)
******


#####Right so let's get started

1.  Open up your terminal

2.  First get your bearing type:
    
    >$ls

    This lists out all the files and folders of wherever you are.

3.  Make a folder to work in (you can call it something other than
    'Database' just needed a placeholder)

    >$mkdir Database

    This makes a new folder(aka directory) called Database 
    (because Bash succeeds silently you'll want to use $ls to double check that it worked)

4.  Check out your new folder

    >$cd Database

    This **C**hanges the **D**irectory to the new folder Database
    Check it out with $ls you won't see anything just yet but that
    ok we'll put files in it soon!

5.  Back to the start for the installing process

    >$cd ..

    This brings you back up a level to your start. You can always type $cd by itself to
    quickly get back to your main folder.

6.  First you'll need the xcode command line tools (MAC's 
    developer tools) my understanding is it gives you deeper
    access to your computer because some things (like databases)
    require asking your computer to behave differently (or pretend
     to so you can practice). 

    >$xcode-select --install

7.  Next one's a long one (I just copy and paste it whenever I 
    need to reinstall) This installs **brew** which lets you
    install basically any programming or database language by
    typing "brew install <whatchu want to install>"

    >$ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

    note: you DO need the quotes!

    It'll ask for your password, so be ready to type it in. 
    When you type passwords into your terminal, nothing will
    appear on your screen to indicate that you're typing letters 
    in. This is an intentional security feature, even if it feels 
    a bit odd. Type normally and hit Enter.

8. Install Git (which we'll link to your github account)

    >$brew install git

9. Link it up to Github so you don't have to log in everytime

    >$git config --global user.name "Your github username"
    >$git config --global user.email your-email@gmail.com

10. Last but not least your database adapter sqlite3

    >$brew install sqlite


*****

###And you're ready to get started! -> [GIT](../master/git.md)









