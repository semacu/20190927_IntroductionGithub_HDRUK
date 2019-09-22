
# Introduction to GitHub

<img align="right" src=../../../20181003_Intro_git_GitHub/blob/master/images/github_icon.png width="125">

- Date and time: 27th September 2019, 14:00 - 16:00
- Location: Health Data Research UK HQ, Wellcome Trust, London, UK
- Trainer: [Sergio](https://github.com/semacu)
- short course url: https://tinyurl.com/2019HDR



## Overview

The aim for today is to learn the basics of GitHub so that you can use it for your own projects.

- [Background](README.md#background)
- [What is version control? What is Git? What is GitHub?](README.md#what-is-version-control-what-is-git-what-is-github)
- [How can you use GitHub? How can it be useful for your work?](README.md#how-can-you-use-github-how-can-it-be-useful-for-your-work)
- [Practical session: working with GitHub](README.md#practical-session-working-with-github)



## Background

- GitHub was originally developed to manage the development of large-scale software projects e.g. Unix. Today's major user of GitHub is Microsoft, who recently acquired it.

- Although designed for software management at first, it is now used for many other purposes and disciplines. Widely-used by academia, industry and government in different contexts.

- Record and access the history of a project: keep track of versions during project development e.g. *the project status 10 days ago*

- It is a **FAIR** tool:
  - **F**indability: online through www.github.com and with embedded search capabilities
  - **A**ccessibility: access via any internet browser. Public (free) and private (paid) repositories model
  - **I**nteroperability: easy interaction with any operating system (Mac, Linux, Windows)
  - **R**eproducibility



## What is version control? What is Git? What is GitHub?

[**Version control**](https://git-scm.com/book/en/v2/Getting-Started-About-Version-Control) is the management of *changes* (a.k.a. *revisions*) to any types of information
  - In its simplest form, creating copies and changing file names, e.g. adding v1.0, v1.1, v2.0
  - Using tools that (to some extent) incorporate version control functionality, e.g. Google Drive and Dropbox
  - Using dedicated version control tools, e.g. Git

The first version control systems were created by groups writing software and code. Fortunately, they can now be used not only by computer scientists (for developing computer code) but by anyone (for any type of file) :smile:

There are two types of version control systems:

<p align="center">
<img src=../../../20171024_GitHub_Chemistry_Cambridge/blob/master/images/vcs.png width="800">
</p>

<p align="right">
(adapted from http://lhzuigao.com/309note.html)
</p>

Advantages of *distributed* (right) over *centralised* (left) version control systems include:

  - If the central repository (server) crashes, it could be recovered / backed up from any of the local repositories created e.g. by the researcher, collaborator or group leader.
  - Each person can make changes to their local repositories *offline*. Then integrate their individual changes in the central repository (server) when connected *online*.


[**Git**](https://git-scm.com) is a *distributed* version control system to keep track and compare the history of *changes* made to your scripts and files. It allows groups of people to work on the same documents at the same time, and without stepping on each other's toes. It was created by Linus Torvalds in 2005 for the development of the Linux project. It is **free** and **open source** and helps you with:
  - Creating repositories to host your projects using the [command-line](https://en.wikipedia.org/wiki/Command-line_interface)
  - Tracking changes to the files and folders within your repositories


[**GitHub**](https://github.com/) is a platform to share and showcase your work online with collaborators and the wider audience. A tool to help you build projects that are collaborative, well documented, and version-controlled. It provides you with:
  - A place to host and backup your repositories online
  - A nice web interface to your repositories
  - A strategy to collaborate with colleagues

Versions in Git and GitHub are identified by a *revision number*, e.g. 60363b1, also known as *commit*. Each revision is associated with a *timestamp* and the *person* making the change. Revisions can be **compared**, **restored**, and with some types of files, **merged**.

There are other softwares for version control similar to Git, e.g. [svn](https://en.wikipedia.org/wiki/Apache_Subversion). Similarly, there are other online platforms similar to GitHub to share and collaborate code, e.g. [GitLab](https://about.gitlab.com/).



## How can you use GitHub? How can it be useful for your work?

There are two interfaces to GitHub:

- [Online](http://github.com/)

<p align="center">
<img src=../../../20171024_GitHub_Chemistry_Cambridge/blob/master/images/github_online.png width="800">
</p>

- Github [Desktop](https://desktop.github.com/) (available for Mac and Windows)

<p align="center">
<img src=../../../20171024_GitHub_Chemistry_Cambridge/blob/master/images/github_desktop.png width="800">
</p>

<p align="right">
(https://programminghistorian.org/lessons/getting-started-with-github-desktop)
</p>

Today, we will be using GitHub's online interface.


### Examples

- To host and share outputs and software:
  - Laboratories sharing own research e.g. the [Jefferis](https://github.com/jefferislab) or [Balasubramanian](https://github.com/sblab-bioinformatics) groups
  - Software source codes e.g. [BWA](https://github.com/lh3/bwa), a bioinformatics tool to align DNA sequences to reference genomes
  - Or even to share slides - see Bérénice Batut [work](https://bebatut-slides.github.io/backofen_lab_retreat_04_17/#/) and Stephen J. Eglen [slides](https://github.com/sje30/2018-12-07-rmd)

- To create websites using [GitHub pages]((https://pages.github.com/))
  - Personal research websites, e.g. [Mike Love site](http://mikelove.github.io/)
  - Courses and activities, e.g.
    - [A Friendly Introduction to GitHub](https://kirstiejane.github.io/friendly-github-intro/)
    - [Statistics course in the University of British Columbia](http://stat545.com/index.html)

- To share the contents of a book, e.g. [Bioinformatics Data Skills](https://github.com/vsbuffalo/bds-files) or [Happy Git and GitHub for the R user](http://happygitwithr.com/)

- To write a PhD thesis, e.g. [A reasoning framework for C4 photosynthesis research based on high-throughput analysis](http://rik.smith-unna.com/phd/thesis.html)

- Even to change the [law](https://arstechnica.com/tech-policy/2018/11/how-i-changed-the-law-with-a-github-pull-request/?utm_source=The+Week+in+Data+mailing+list&utm_campaign=b629363b0d-TheWeekinData16Feb2018_COPY_01&utm_medium=email&utm_term=0_3391a19d97-b629363b0d-101334857&mc_cid=b629363b0d&mc_eid=56501d149f)


### In the context of our research group

- Communication is key as most projects have both experimental and computational leaders
- Building from the classical ways of sharing - conversations/meetings, email, Dropbox, shared folders ... we want to build an environment where:
  - Computational colleagues can share code, figures and tables. Review others work and get credit from their collaborative work
  - Experimental colleagues can follow computational developments, access results and learn methods of data analysis

- And ideally avoiding situations like ...

<p align="center">
<img src=../../../20171024_GitHub_Chemistry_Cambridge/blob/master/images/reproducibility.gif width="800">
</p>

<p align="right">
(http://phdcomics.com/comics.php?f=1689)
</p>

- Parhaps a happier lifetime for a research project:

<p align="center">
<img src=../../../20171024_GitHub_Chemistry_Cambridge/blob/master/images/project_timeline.png width="800">
</p>

<p align="right">
(https://github.com/semacu/20170703_GitHubintheLab_CRUK-CI)
</p>


### Public (free) and private repositories

If you want to start creating repositories in GitHub, your first need to open an account:

- Public repositories are free, and can be browsed and downloaded by anyone
- Private repositories have associated costs depending on the number of collaborators - see [pricing of plans](https://github.com/pricing). The individual pro and team plans cost $7/month and $9/month respectively but they are free if you are [a student or an academic](https://education.github.com/pack)

Alternatively, [GitLab](https://about.gitlab.com/) uses a different business strategy with free private repositories and cost plans for public ones. There are also other alternatives e.g. [Bitbucket](https://bitbucket.org/).


### Markdown

- GitHub uses Markdown for text edition, a language with plain text formatting syntax (bold, italics, checkboxes, lists, etc.), to render pages online (like HTML but easier). You can use this syntax in text files (file extension: .md), commit messages, issues, blog posts, and more.

- Markdown is important because GitHub automatically renders anything written in Markdown. This can be specific files (eg: README), or your comments and issues.

- Some examples of Markdown syntax are available [here](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).



## Practical session: working with GitHub

We have four possible tutorials:

- [Create a GitHub account](README.md#create-a-github-account) (+)
- [Create your first repository](README.md#create-your-first-repository) (+)
- [Explore your first repository and GitHub account](README.md#explore-your-first-repository-and-github-account) (++)
- [Making changes using Git in the command-line](README.md#making-changes-using-git-in-the-command-line) (+++)
- ... and some [extras](README.md#extras)


### Create a GitHub account

If you don't have a GitHub account already:

- Go to https://github.com
- Fill in your **Username**, **Email** and **Password**. Then click on the green button "Sign up for GitHub".

<p align="center">
<img src=../../../20171024_GitHub_Chemistry_Cambridge/blob/master/images/p1_1.png width="800">
</p>

- Choose your personal plan page. Select "Free plan" and then click on "Continue".

<p align="center">
<img src=../../../20171024_GitHub_Chemistry_Cambridge/blob/master/images/p1_2.png width="800">
</p>

- Tailor your experience page. Choose the boxes that apply to you and click on "Submit". Otherwise, just go to "skip this step".

<p align="center">
<img src=../../../20171024_GitHub_Chemistry_Cambridge/blob/master/images/p1_3.png width="800">
</p>

- You have created a GitHub account! :smile:

********************************************


### Create your first repository

- If you are not already signed in, sign in to GitHub using the **Username/Email** and **Password** created before.
- Click on the top-right "avatar icon" and select "Your profile". Have a quick browse through your page.

<p align="center">
<img src=../../../20171024_GitHub_Chemistry_Cambridge/blob/master/images/p2_1.png width="800">
</p>

- Click on the top-right "+" icon and select "New repository". **Verify your email address**. You should have just received an email from GitHub in the address provided before. Find this email and click on "Verify email address".

<p align="center">
<img src=../../../20171024_GitHub_Chemistry_Cambridge/blob/master/images/p2_2.png width="400"> <img src=../../../20171024_GitHub_Chemistry_Cambridge/blob/master/images/p2_3.png width="400">
</p>

- Create a new repository page. Fill in a "Repository name", e.g. "my_first_repository" or "my_analysis_script". Write a short description of your repository e.g. "This is a test repository". For now choose "Public" and select the box to initialize this repository with a README. Finally, click on "Create repository".

<p align="center">
<img src=../../../20171024_GitHub_Chemistry_Cambridge/blob/master/images/p2_4.png width="800">
</p>

- You created your first repository! :rocket:



### Explore your first repository and GitHub account

#### Your first repository

- Click on **README.md** and go to the right pencil "Edit this file". Type anything to change the file, e.g. "GitHub is fun!".

<p align="center">
<img src=../../../20171024_GitHub_Chemistry_Cambridge/blob/master/images/p3_1.png width="800">
</p>

<p align="center">
<img src=../../../20171024_GitHub_Chemistry_Cambridge/blob/master/images/p3_2.png width="800">
</p>

- Scroll down. Introduce a commit change message, e.g. "My first update", and select the radio button "Commit directly to the master branch". Then click on "Commit changes". Voilá!

<p align="center">
<img src=../../../20171024_GitHub_Chemistry_Cambridge/blob/master/images/p3_3.png width="800">
</p>

- To view your **history of commits** for **README.md**, click on **README.md** and then on the "History" button on the right.
- Alternatively, to view your **history of commits** for your first repository, click on the name of your repository and select the tab depicting a small clock and the number of commits next to it.

Bonus points (5 min):

- Try to create a new file
- In your new repository, have a look at the "Settings" tab, explore "Collaborators" and try to add the person sitting next to you.


#### Your GitHub account

- Click on your top-right "avatar" icon and select "Settings".

<p align="center">
<img src=../../../20171024_GitHub_Chemistry_Cambridge/blob/master/images/p3_4.png width="800">
</p>

- Explore the tabs "Profile", "Account" and "Emails".


**Key glossary:**

- **Repository**: it can be thought of as a project folder. A **repository** contains all of the project files, issues, wikis and more. It also stores the history and versions of each file.

- **Commit**: equivalent to saving your changes to a file. When you **commit** you usually include a brief description of the changes you made so you can identify versions later if you want to undo a change.

- **Branch**: an identical copy of a project at a particular point in time kept separate from the 'master' branch (primary copy). This keeps your code in the 'master' branch safe while you make changes and experiment with code on the new branch. You can merge your new branch back into the 'master' branch when you want to publish your changes.

- **Master**: the default branch in your repository.

- **Collaborator**: someone with read and write privileges to a repository as approved by the repository owner.







