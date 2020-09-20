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
- Pre-recorded lectures from CASA staff.
- Recorded videos from non-CASA staff.
- Short quizzes to test your completion of readings and videos.
- Contributions to a weekly '[Padlet](https://en-gb.padlet.com/)' that will be used to guide the synchronous sessions.

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
  - [Dropbox](https://bit.ly/32jhdvN)
  - [Slack](https://casa-students-2020.slack.com/)
- [Writing Code](https://github.com/jreades/i2p/blob/master/lectures/1.3-Writing_Code.md)
- Poll Time!
  - **Poll**: why can't we write code the same way that we write an essay?
  - **Poll**: have you ever programmed before?

### During the Break

- Sign up for and [log in to Slack](https://casa-students-2020.slack.com)
- Sign up for and log into [GitHub](https://github.com/) 

### Practical

- Using the **#intro-to-programming** channel on [Slack](https://casa-students-2020.slack.com) please share your GitHub acccount handle (*i.e.* [`jreades`](https://github.com/jreades)) by **replying** to Jon's welcome message. This will keep the account names in one place.
- Git & Version Control
  - Create a new **private** project (e.g. `i2p`)
  - Edit a file directly in GitHub (edit the `README.md`)
  - Save your changes (this is called a 'Commit' and you will need to make a general comment about what you did) 
  - Work out how to compare the original README with the edited one (make two sets of changes and commit after each)
- Write up notes for today in Markdown
  - Select *one* of today's lectures by visiting [jreades/i2p/lectures](https://github.com/jreades/i2p/tree/master/lectures), selecting one of the files starting `1.` , click on `Raw` to see the Markdown and copying all of this.
  - Go back to your new repository and select `Add File > Create New File`, then paste in the copied text.
  - Once the file has been added successful, edit it by clicking on the 'pencil' icon. See if you can successfully deal with:
    - Plain text
    - Header levels: `#`, `##`, `###`, etc.
    - Emphasis/Italics: `_italics_`, `**bold**`.
    - Lists: `- ` and `1. `.
    - Links: `[link text](url)`.
    - Images: `![Alt text](url)`.
    - Code: \``...`\`.

### Other Resources
- [The Programming Historian's Guide](https://programminghistorian.org/en/lessons/sustainable-authorship-in-plain-text-using-pandoc-and-markdown#working-with-bibliographies) [GitHub Guide](https://guides.github.com/features/mastering-markdown/)
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

- Watch: installation video for [Mac]() or [Windows]()
- Try [installing Vagrant](https://github.com/jreades/sds_env/tree/master/vagrant)
- *Only* if that doesn't work, try [installing Anaconda Python](https://github.com/jreades/sds_env/tree/master/conda)

#### Lectures

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

- Padlet: **Collaborative Reflective Agenda**

### Workshop

- [Geography and Computers](https://github.com/jreades/i2p/blob/master/lectures/2.1-Computers_in_Planning_and_Geography.md)
- [Principles of Programming](https://github.com/jreades/i2p/blob/master/lectures/2.2-Principles_of_Programming.md)

### During the Break

- Make sure you know where to find the [Terminal](https://www.businessinsider.com/how-to-open-terminal-on-mac) (Mac) or PowerShell (Windows)
- Find and share a useful video on YouTube for [Mac](https://www.youtube.com/results?search_query=terminal+for+beginners+mac) or [Windows](https://www.youtube.com/results?search_query=powershell+for+beginners)

### Practical

- [Practical 1](https://github.com/jreades/i2p/raw/master/practicals/Practical-02-Foundations_1.ipynb)

### Other Resources