---
title: Syllabus
author: Jon Reades, Huanfa Chen
bibliography: Readings.bib
csl: harvard-cite-them-right.csl
mainfontoptions:
- Numbers=Lowercase
- Numbers=Proportional
---
# Overview

This year we are 'flipping' the classroom. That means that we expect you to come to 'lecture' (***except*** in Week 1!) having already watched the assigned videos and completed the assigned readings. This means that there is a mix of 'asynchronous' (work that you do in your own time) and 'synchronous' (work that we do during scheduled hours) interaction. For those unable to attend a 'synchronous' activity because of Time Zone issues we *intend* to make a recording available afterwards, but we expect that a 2-hour recording of a group discussion and live coding session will be rather less educational and informative than actually *being there* so recordings should not be used as a substitute for attendance.

### Preparation

The nature and amount of preparation will vary from week to week, but may include:

- Readings from both academic and non-academic sources.
- Recorded lectures from CASA staff.
- Recorded videos from non-CASA staff.
- Short quizzes to test your completion of readings and videos.
- Contributions to a weekly '[Padlet](https://en-gb.padlet.com/)' that will be used to guide the 'synchronous' sessions.

### 'Lecture'

The 'lecture' in your timetable will be used for a mix of discussion and 'live coding' (eeek!) using the following framework:

- We will review questions and issues arising from the previous week's practical session.
- We will use *your* contributions to the week's Padlet to prioritise discussion around concepts and readings with which students are struggling or wish to engage further.
- We will have a 'live coding' session following an 'I do/We do' format: we will employ concepts covered in the week's preparation activities, as well as approaches that will be explored further in the practical, to look a real-world data set *together* using code.

So we're going to call these **workshops** instead!

### Practical

There are two timetabled practical sessions; we will inform you of your assigned session.

# Week 1: Setting Up

### Preparation

There is no preparation for this session, but please ensure that your computer is fully up-to-date with Operating System and application updates. Also, please make a note of the following three things:

- What Operating System and Version is your _main_ computer running? [Help for Windows](https://support.microsoft.com/en-gb/help/13443/windows-which-version-am-i-running). [Help for Mac](https://support.apple.com/en-gb/HT201260).
- How much RAM does your _main_ computer have? [Help for Windows](https://www.howtogeek.com/435644/how-to-see-how-much-ram-is-in-your-pc-and-its-speed/). [Help for Mac](https://www.macworld.co.uk/how-to/mac/much-ram-need-more-3793418/).
- How much free disk space does your _main_ computer have? [Help for Windows](https://www.lifewire.com/how-to-check-free-hard-drive-space-in-windows-2619187). [Help for Mac](https://www.macworld.com/article/2972775/how-to-check-a-mac-free-hard-drive-space.html).

### Workshop

- [Getting Oriented & Getting Help](https://github.com/jreades/i2p/blob/master/lectures/1.1-Getting_Oriented.md)
- Poll Time!
  - **Poll**: Where in the world are you?
  - **Poll**: Hopes, fears, and expectations of this module?
- [Tools of the Trade](https://github.com/jreades/i2p/blob/master/lectures/1.2-Tools_of_the_Trade.md)
- [Writing Code](https://github.com/jreades/i2p/blob/master/lectures/1.3-Writing_Code.md)

### During the Break

- Sign up for and [log in to Slack](https://casa-students-2020.slack.com)
- Sign up for and log into [GitHub](https://github.com/) 

### Practical

#### Task 1: Git and Version Control

Understanding how to use Git and GitHub effectively is a core element of learning to code. So one of the _first_ things that we are going to do is set you up with an account and a new project.

So in order to complete this task you need to:
1. Create a login with [GitHub](https://github.com). You may wish to set it up with your UCL email and then link a personal email address as well. 
2. Using the **#intro-to-programming** channel on [Slack](https://casa-students-2020.slack.com) please share your GitHub acccount handle (*i.e.* [`jreades`](https://github.com/jreades)) by **replying** to Jon's welcome message. This will keep the account names in one place.
3. Create a new **private** project directly on GitHub. You might as well call it `i2p` since that's a lot shorter than `intro_to_programming_for_spatial_analysts`.
4. Edit the `README.md` file with some information about what's in the project (_e.g._ your notes and practicals for the module).
5. Save the changes (this is called a 'commit') and say in a general way what edits you did.
6. Work out how to compare the original and edited versions of `README.md` in your browser.

#### Task 2: Getting Comfortable with Markdown

To get some practice with Markdown let's write up some notes direclty in our GitHub repository (aka 'repo'). In order to complete this task you will need to:
1. Select *one* of today's lectures by visiting [jreades/i2p/lectures](https://github.com/jreades/i2p/tree/master/lectures), selecting one of the files starting `1.` .
2. You will need to click on `Raw` to see the Markdown. 
3. Select and copy all of the raw Markdown.
4. Go back to **your** repository and select `Add File > Create New File`, then paste in the copied text.
5. Once the file has been added successful, edit it by clicking on the 'pencil' icon. 

Add notes incorporating:
- Plain text
- Header levels: `#`, `##`, `###`, etc.
- Emphasis/Italics: `_italics_`, `**bold**`.
- Lists: `- ` and `1. `.
- Links: `[link text](url)`.
- Images: `![Alt text](url)`.
- Code: \``...`\`.

Save your changes (don't forget to add a basic comment outlining what you've done) and then view the difference (aka 'History) to see what you've edited.

#### Task 3: Getting Set Up with Vagrant or Anaconda Python

You may be tempted to leave this for later, but we'd _strongly_ encourage you to try installing the programming environment as soon as possible so that we have as long as possible to help you over any hurdles before we get to week 3 where it will be essential that you are running the environment successfully. In our experience, the students who put off trying to get the environment running end up falling quickly behind as they are unable to complete basic tasks successfully. 

The _majority_ of you will be able to use the [Vagrant](https://www.vagrantup.com/)/[VirtualBox](https://www.virtualbox.org/) solution, but there will be _some_ Windows 10 users whose computers will refuse to run either VirtualBox or Vagrant, in which case will need to run [Anaconda Python](https://anaconda.org/) directly.

##### Installing Vagrant 

I have [produced an installation video](https://web.microsoftstream.com/video/d94bc09d-02c9-45cf-83ed-3badeab3568b) for users on Apple's MacOS that is available on MS Streams (you need to be logged in as a UCL user in order to view this).

<figure class="video_container">
    <iframe width="640" height="360" src="https://web.microsoftstream.com/embed/video/d94bc09d-02c9-45cf-83ed-3badeab3568b?autoplay=false&amp;showinfo=false" allowfullscreen style="border:none;"></iframe>
</figure>

The process for Windows users will be similar, but you will need to install either the [Windows Subsystem for Linux](https://docs.microsoft.com/en-us/windows/wsl/install-win10) or [Git BASH](https://gitforwindows.org/). We are working on a video for this.

You can **follow along** in a [text version of the installation guide on GitHub](https://github.com/jreades/sds_env/tree/master/vagrant).

##### Installing Anaconda Python

If the installation of Vagrant/VirtualBox fails, then you will need to go down this route for installing the programming environment. 

Windows users will need to install either the [Windows Subsystem for Linux](https://docs.microsoft.com/en-us/windows/wsl/install-win10) or [Git BASH](https://gitforwindows.org/).

You can **follow along** in a [text version of the installation guide on GitHub](https://github.com/jreades/sds_env/tree/master/conda).

#### Task 4: Installing Command Line Tools

The final thing that we need to do (because it will be useful next week) is install some command line tools that will allow us to interact with Git from the Terminal/Command Prompt. You only need to do one of these:

1. MacOS: install the Xcode Command Line Tools [directly from the command line](https://osxdaily.com/2014/02/12/install-command-line-tools-mac-os-x/).
2. Windows: install Git Bash by following [these instructions](https://www.stanleyulili.com/git/how-to-install-git-bash-on-windows/).

That's 'it'! You're done. We've had to put a lot of pieces of software in place for the term, but you'll find these useful across multiple modules that are part of your MSc/MRes and you're now set up for the future!

### Other Useful Resources
- [The Programming Historian's Guide](https://programminghistorian.org/en/lessons/sustainable-authorship-in-plain-text-using-pandoc-and-markdown#working-with-bibliographies)
- [GitHub Guide](https://guides.github.com/features/mastering-markdown/)
- [Common Mark](https://commonmark.org/help/)
- [Markdown Guide](https://www.markdownguide.org/basic-syntax/) includes do's and don'ts.
- Finally, these are a bit overkill but the bits about setting up and installing `git`, `bash`/`zsh`, and so on may come in handy later:
  - [Setting Up a New Mac](https://www.taniarascia.com/setting-up-a-brand-new-mac-for-development/)
  - [Beginner's Guide to Setting Up Windows 10](https://medium.com/@mfosullivan/a-beginners-guide-to-setting-up-a-modern-web-development-environment-on-windows-10-4d75cd94cde8)
  - [Setting up Windows without Linux](https://dev.to/jozsefsallai/how-i-ve-set-up-my-windows-machine-as-a-development-environment-without-wsl-2kcl)
  - [Microsoft Python Setup Guide](https://docs.microsoft.com/en-us/windows/python/beginners)

# Week 2: Foundations (Part 1)

### Preparation

#### Installing Vagrant/Anaconda Python

If you didn't get to this during the practical, then the single most important thing you can do as preparation for this week is to install the programming environment:

- Watch: installation video for [Mac](https://web.microsoftstream.com/video/d94bc09d-02c9-45cf-83ed-3badeab3568b) or [Windows]()
- Try [installing Vagrant](https://github.com/jreades/sds_env/tree/master/vagrant)
- *Only* if that doesn't work, try [installing Anaconda Python](https://github.com/jreades/sds_env/tree/master/conda)

#### Installing Command Line Tools 

Again, if you didn't get to this during the practical then please do it before we get to Week 2's sessions! You need to install one of:

- The Xcode Command Line Tools (Mac). You can do this [directly from the command line](https://osxdaily.com/2014/02/12/install-command-line-tools-mac-os-x/).
- Git Bash (Windows). You can follows [these instructions](https://www.stanleyulili.com/git/how-to-install-git-bash-on-windows/).

#### Lectures

As we're working in a 'flipped' environment, you should watch these videos *before* class so that the 'live' (aka. 'synchronous') session can focus on demonstration, discussion, and clarification. 

This week in particular is very busy because we need to cover off the basics for those of you who were unable to engage with [Code Camp](https://kingsgeocomputation.org/teaching/code-camp/code-camp-python/) while recapping only the crucial bits for those of you who were able to do so: 

- Watch: [Python: the Basics]()
- Watch: [Lists](https://github.com/jreades/i2p/blob/master/lectures/2.4-Lists)
- Watch: [Dictionaries](https://github.com/jreades/i2p/blob/master/lectures/2.5-Dictionaries.md)
- Watch: [Iteration](https://github.com/jreades/i2p/blob/master/lectures/2.6-Iteration.md)
- Watch: [The Command Line](https://github.com/jreades/i2p/blob/master/lectures/2.7-The_Command_Line.md)
- Watch: [Getting Stuck Into Git](https://github.com/jreades/i2p/blob/master/lectures/2.8-Git.md)

#### Readings

- [@Burton:1963] [DOI](https://doi.org/10.1111/j.1541-0064.1963.tb00796.x)
- [@ArribasBel:2018] [DOI](https://doi.org/10.1111/gec3.12403)

#### Contribution

- Padlet: **Collaborative Agenda**

### Workshop

- [Geography and Computers](https://github.com/jreades/i2p/blob/master/lectures/2.1-Computers_in_Planning_and_Geography.md)
- [Principles of Programming](https://github.com/jreades/i2p/blob/master/lectures/2.2-Principles_of_Programming.md)

### During the Break

- Make sure you know where to find the [Terminal](https://www.businessinsider.com/how-to-open-terminal-on-mac) (Mac) or AnacondaPrompt (Windows)
- Find and share a useful video on YouTube for [Mac](https://www.youtube.com/results?search_query=terminal+for+beginners+mac) or [Windows](https://www.youtube.com/results?search_query=powershell+for+beginners)

### Practical

#### Task 1: Cloning Your Repository

The first thing that we need to do is to get a clone (i.e. copy) of the repository that you created last week on GitHub on to your own computer. This is surprisingly straightforward provided that you have installed either:

1. The Xcode Command Line Tools (Mac). You can do this [directly from the command line](https://osxdaily.com/2014/02/12/install-command-line-tools-mac-os-x/).
2. Git Bash (Windows). You can follows [these instructions](https://www.stanleyulili.com/git/how-to-install-git-bash-on-windows/).

#### Task 2: Adding Local Files to Your Repository

In order to tie together the different concepts covered above, we now need to add Practicals 1 and 2 from my [i2p repository](https://github.com/jreades/i2p) to your own GitHub repo.

Right now, the easiest way to do this is to open both practicals as Raw text in your browser:

- [Practical 1](https://github.com/jreades/i2p/blob/master/practicals/Practical-01-Getting_Started.ipynb)
- [Practical 2](https://github.com/jreades/i2p/blob/master/practicals/Practical-02-Foundations_1.ipynb)

You will then need to:

1. Save both files to your computer as notebooks (with the extension `.ipynb`). Remember that you need to remove the `.txt` extension for these files to be treated as notebooks, not plain text. You can do this at any point (even once using Jupyter) but it may be easiest when you download them.

#### Task 3: Launch Jupyter Lab

If you are able to run Vagrant, then Jupyter Lab will have started automatically for you when you ran the command `vagrant up`. This means that you should be able to visit: [localhost:8888](http://localhost:8888/lab/) and see the Jupyter Lab interface.

If you were forced to run Anaconda Python directly, then you will need to start Jupyter Lab yourself by launching either the Terminal (Mac) or Anaconda Prompt (Windows) and running:

```bash
conda activate sds2020
jupyter lab
```

Make a note of the working directory where you launched Jupyter Lab since it will only be able to see files _under_ this folder (e.g. only in your Downloads folder).



1. Move the files into your `notebooks` directory (if you are running Vagrant) so that Jupyter can see them. If you are running Anaconda Python directly, then you need to move them to the folder where you typed `jupyter lab`.



### Other Resources