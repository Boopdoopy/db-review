##Summary
*****
So by now you're probably thinking why did I install this git thingy. What
even is a github? So I'll run you through the basics and if you have any 
questions you can shoot them my way or apply [Google fu](../master/googlefu.md).


Something to remember when dealing with the information flood that is computer 
science is that the best mindset to apply is my FAVORITE programming motto 
(which belongs to a team that made a simplified html called slim).
**"what is the minimum necessary to make this work?"**


*There are many of my instructors that just have sticknotes with notes on
how to do stuff because taking the time to remember it wasn't necessary.*
*****

if you want the *tl;dr* jump to part 2

1. ###GIT
*****

Git is an add on for your directories. It puts a tiny file (*.git*) in any folder you
ask it to and will track the various changes and versions that occur within
that folder and all of its contents.

If you ever want to see it use:
  >$ls -A
  
Which shows hidden folders

The git command you need to know are:

1. $git clone <url here>

  *this makes a copy of a whole repository (a bunch of files on github with version tracking)
  and links it to the repo(sitory). This means you can make a new branch and push the changes
  up AND if other people make changes you can update your computers copy too!*

2. $git checkout -b name-of-your-branch
   *this makes a new branch for you to work on*
  
3. $git status
  *this will tell you if you have untracked changes, and what branch you are on

4. $git add <whatever filename.file>  OR  $git add --all
  *this will **stage** a change (or all changes). 
  You can think of it as adding all your saves into a box*

5. $git commit -m "You have to type a msg here"
  *this tapes up the box and puts whatever label you want to put on it about
  its contents*
  
6.$git push origin name-of-your-branch
  *this ships off all of your taped up boxes to Github*
  
Lots of stuff I know, but feel free to just reference this, honestly all you really
need is **git clone** but I figured you'd want some reference incase.
*****


2. ###Github
*****

On the main page of each repo near the top right corner theres a little field that
reads clone or download. Click the clipboard (it will automatically copy to your clipboard)

Open your terminal
  * Navigate to the folder you made to work in (use $cd)
  
  >$git clone <paste the url thats in your clipboard here>

This copies down this whole repo so you can work with it on your computer
You can still reference stuff up here but you'll be working locally

  >$cd db-review

AND SETUP IS FINALLY DONE -> [Back to the main page](README.md)
  
  
