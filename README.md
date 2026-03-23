This isn’t a complete guide to Git and Markdown, but it’ll give you a basic idea and get you doing the bare minimum on GitHub. I might update this later if I’m bored and decide to make it better.

# GIT tutorial for baby programmers
## What is Git?
Git is a version control system (VCS) used by programmers to track changes in their source code and blame people for their their mistakes(you know what I am referring to hehe).

Unlike older systems that rely on a central server, every developer has a complete copy of the project history on their local machine (That's how open source development and remote jobs work)

## How to push code to GitHub?  
Say you somehow managed to write a code locally on your laptop/pc and you want it on Your GitHub profile, follow the following steps

`step-1:` Find a button which says `Create a new repository` and create one (I'm assuming you are capable of figuring this out so I don't need to embed mulitple ss of creating a repo)

`step-2:` Go to Terminal of your IDE/text-editor

`step-3:` Navigate to your project file inside Terminal  
  `cd your-project-folder` this will help you go to that folder (folder name: your-project-folder)

`step-4:` Now initialize Git  
  `git init` this will initialize git on your project

`step-5:` Lets add our files to staging  
  `git add .` This will add all your files. if you want some specific files (for example: the ones that you finished working on and not the ones you are still figuring out) use this `git add file1.py file2.py` 

`step-6:` Commit your changes  
  `git commit -m "write a message for your future self or colleague about what changes you did to the code"` (don't worry almost every programmer gets confused when it comes to writing a commit message)  

`step-7:` Connect your local repository to GitHub  
  `git remote add origin https://github.com/your-username/your-repo.git` copy a link something similar to this from your repo on GitHub

`step-8` Set your branch to main (coz you are a newbie and you don't want to complicate your life)  
  `git branch -M main`  

`step-9` Finallyy! push your code to GitHub (do check whether you are connected to internet because you need it for this step)  
  `git push -u origin main`

  ---

# Markdown for babies
## What is markdown?
Markdown is a lightweight, plain-text markup language designed to be easily readable and convertible to HTML.  
The flie you are looking at right now is written in markdown.  
Strictly speaking with respect to GitHub some of the markdown features don't work here, so you can subistitute their HTML alternatives instead.  
## Basic markdown
### Headings
Headings in Markdown come in six sizes, where the one with one `#` is the biggest and the one with `######` is the smallest  
The format of a heading: `## This is a heading` (don't forget the space between the hashtags and the text)  
### Code blocks
If you want code blocks in your markdown just like how I included them in mine use ` `` ` (the key above Tab key) and write your code in it  
and if you want to include muliple lines of code use ` ```  <code>  ``` ` across multiple lines of code
### Lists
In lists we have two types:
#### Ordered lists
```
1. First
1. Second
 1. Numbers
 2. Does’t matter
```
type this to get this  
1. First
2. Second
   1. First
   2. Doesn't matter  
#### Unordered list
```
* Asterisks
* List
 * Nested

+ Can also use plus sign
- Can also use dash
```   
* Asterisks
* List
  * Nested

+ Can also use plus sign
- Can also use dash
### Links
you can add a link to your markdown using this  
```
format:
[label](https://url.com)
example:
[Markdown tutorial](https://youtu.be/_PPWWRV6gbA?si=DwzCSCrRu9QMutYb)
```
[Markdown tutorial](https://youtu.be/_PPWWRV6gbA?si=DwzCSCrRu9QMutYb)  
This is the video from which I learnt markdown do check it out.
