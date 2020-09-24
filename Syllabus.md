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
- We will use ***your*** contributions to the week's Padlet to prioritise discussion around concepts and readings with which students are struggling or wish to engage further.
- We will have a 'live coding' session following an 'I do/We do' format: we will employ concepts covered in the week's preparation activities, as well as approaches that will be explored further in the practical, to look a real-world data set *together* using code.

So we're going to call these **workshops** instead! These will take place on Zoom and can be accessed using the 'activity' specified on the [Lectures and Workshop Material](https://moodle.ucl.ac.uk/course/view.php?id=11291&section=2) page.

### Practical

There are two timetabled practical sessions; we will inform you of your assigned session. These will also take place on Zoom and can *also* be accessed using the 'activity' specified on the [Lectures and Workshop Material](https://moodle.ucl.ac.uk/course/view.php?id=11291&section=2) page of Moodle.

# Week 1: Setting Up

### Preparation

Please ensure that your computer is fully up-to-date with Operating System and application updates. Also, please make a note of the following three things:

- What Operating System and Version is your _main_ computer running? [Help for Windows](https://support.microsoft.com/en-gb/help/13443/windows-which-version-am-i-running). [Help for Mac](https://support.apple.com/en-gb/HT201260).
- How much RAM does your _main_ computer have? [Help for Windows](https://www.howtogeek.com/435644/how-to-see-how-much-ram-is-in-your-pc-and-its-speed/). [Help for Mac](https://www.macworld.co.uk/how-to/mac/much-ram-need-more-3793418/).
- How much free disk space does your _main_ computer have? [Help for Windows](https://www.lifewire.com/how-to-check-free-hard-drive-space-in-windows-2619187). [Help for Mac](https://www.macworld.com/article/2972775/how-to-check-a-mac-free-hard-drive-space.html).

This information will be very useful during the first few weeks when you are most likely to encounter problems with the programming environment. *Generally* speaking, the things to watch out for are:

1. Your operating system is Windows 10 Home, or something older than Windows 10 (*e.g.* Windows 8 or ealier), or MacOS older than 10.13 (High Sierra).
2. Your computer has less than 8GB of RAM.
3. Your computer has less than 15GB of free disk space remaining.

### Workshop

- Poll Time!
  - **Poll**: Where in the world are you?
  - **Poll**: Hopes, fears, and expectations of this module?

- [Getting Oriented & Getting Help](https://github.com/jreades/i2p/blob/master/lectures/1.1-Getting_Oriented.md)
- [Tools of the Trade](https://github.com/jreades/i2p/blob/master/lectures/1.2-Tools_of_the_Trade.md)
- [Writing Code](https://github.com/jreades/i2p/blob/master/lectures/1.3-Writing_Code.md)

### Practical

This week's practical can be completed [entirely online](https://github.com/jreades/i2p/blob/master/practicals/Practical-01-Getting_Started.ipynb) or on your own computer.

# Week 2: Foundations (Part 1)

### Preparation

#### Installing Command Line Tools 

If you didn't get to this during the practical then *please* do it before we get to Week 2's sessions! You need to install one of:

- The Xcode Command Line Tools (Mac). You can do this [directly from the command line](https://osxdaily.com/2014/02/12/install-command-line-tools-mac-os-x/).
- Git Bash (Windows). You can follow [these instructions](https://www.stanleyulili.com/git/how-to-install-git-bash-on-windows/).

#### Installing Vagrant/Anaconda Python

Again, if you didn't get to this during the practical, then the single most important thing you can do as preparation for this week is to install the programming environment:

- Watch: installation video for [Macs](https://web.microsoftstream.com/video/d94bc09d-02c9-45cf-83ed-3badeab3568b) or [Windows]() machines.
- Try [installing Vagrant](https://github.com/jreades/sds_env/tree/master/vagrant) 
- *Only* if that doesn't work, try [installing Anaconda Python](https://github.com/jreades/sds_env/tree/master/conda)

#### Code Camp

If you have *not* completed [Code Camp](https://kingsgeocomputation.org/teaching/code-camp/code-camp-python/), then we would strongly recommend that you tackle Notebooks 3–5 as preparation for the week's class.

#### Lectures

As we're working in a 'flipped' environment, you should watch these videos *before* class so that the 'live' (a.k.a. 'synchronous') session can focus on demonstration, discussion, and clarification. 

This week in particular is very busy because we need to cover off the basics for those of you who were unable to engage with [Code Camp](https://kingsgeocomputation.org/teaching/code-camp/code-camp-python/) while recapping only the crucial bits for those of you who *were* able to do so: 

- Watch: [Python: the Basics]()
- Watch: [Lists](https://github.com/jreades/i2p/blob/master/lectures/2.4-Lists)
- Watch: [Iteration](https://github.com/jreades/i2p/blob/master/lectures/2.6-Iteration.md)
- Watch: [The Command Line](https://github.com/jreades/i2p/blob/master/lectures/2.7-The_Command_Line.md)
- Watch: [Getting Stuck Into Git](https://github.com/jreades/i2p/blob/master/lectures/2.8-Git.md)

#### Readings

- [@Burton:1963] [DOI](https://doi.org/10.1111/j.1541-0064.1963.tb00796.x)
- [@ArribasBel:2018] [DOI](https://doi.org/10.1111/gec3.12403)

#### Contribution

- Padlet: **Collaborative Agenda**

#### Quiz!

- Complete the short quiz associated with this week's activities.

### Workshop

- [Geography and Computers](https://github.com/jreades/i2p/blob/master/lectures/2.1-Computers_in_Planning_and_Geography.md)
- [Principles of Programming](https://github.com/jreades/i2p/blob/master/lectures/2.2-Principles_of_Programming.md)

### Practical

This week's practical requires you to have completed installation of the programming environment. The practical can be downloaded from [GitHub](https://github.com/jreades/i2p/raw/master/practicals/Practical-02-Foundations_1.ipynb).

# Week 3: Foundations (Part 2)

### Preparation

#### Code Camp

*All* students should complete/revisit [Code Camp](https://mybinder.org/v2/gh/kingsgeocomp/code-camp-env/notebook-v1.0?urlpath=git-pull%3Frepo%3Dhttps%253A%252F%252Fgithub.com%252Fkingsgeocomp%252Fcode-camp%26urlpath%3Dtree%252Fcode-camp%252F%26branch%3Dmaster) Notebooks 8–11.

**Note:** there is an issue with the GeoJSON tasks in Notebooks 8 and 9. We can discuss in the Workshop.

#### Lectures

#### Readings

#### Contribution

#### Quiz!

### Workshop

### Practical