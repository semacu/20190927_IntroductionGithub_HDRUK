
# Introduction to GitHub

<img align="right" src=../../../20181003_Intro_git_GitHub/blob/master/images/github_icon.png width="125">

- Date and time: 27th September 2019, 14:00 - 15:30
- Location: Health Data Research UK, Wellcome Trust, London, UK
- Trainer: [Sergio](https://github.com/semacu)
- course url: https://tinyurl.com/2019HDR



## Overview

The aim for today is to learn the basics of GitHub so that you can use it for your own projects.

- [Background](README.md#background)
- [What is version control? What is Git? What is GitHub?](README.md#what-is-version-control-what-is-git-what-is-github)
- [How can you use GitHub? How can it be useful for your work?](README.md#how-can-you-use-github-how-can-it-be-useful-for-your-work)
- [Practical session: working with GitHub](README.md#practical-session-working-with-github)



## Background

- GitHub was originally developed to manage the development of large-scale software projects e.g. Unix. Today's major user of GitHub is Microsoft, who recently acquired it.

- Although designed for software management at first, it is now used for many other purposes and disciplines. Widely-used in academia, industry and government in different contexts.

- Record and access the history of a project: keep track of versions during project development e.g. *the project status 10 days ago*

- It is **findable** (repositories available online through www.github.com and with embedded search capabilities), **accessible** (via any internet browser) and **interoperable** (easy interaction with any operating system - Mac, Linux, Windows).



## What is version control? What is Git? What is GitHub?

[**Version control**](https://git-scm.com/book/en/v2/Getting-Started-About-Version-Control) is the management of *changes* (a.k.a. *revisions*) to any types of information
  - Effectively "save" your work at important points in time and come back to any of the saved points. You may lose information but can recover and go back from the mistakes as it provides offsite backup in a remote server
  - In its simplest form, creating copies and changing file names, e.g. adding v1.0, v1.1, v2.0
  - It makes collaboration much easier:
    - Using tools that (to some extent) incorporate version control functionality, e.g. Google Drive and Dropbox
    - Using dedicated version control tools, e.g. Git

<p align="center">
<img src=images/phd052810s.gif width="600">
</p>

<p align="right">
(http://phdcomics.com/comics/archive.php?comicid=1323)
</p>

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


[**GitHub**](https://github.com/) is an online platform to share and showcase your work with collaborators and the wider audience. A tool to help you build projects that are collaborative, well documented, and version-controlled. It provides you with:
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
- Private repositories have associated costs depending on the number of collaborators - see [pricing of plans](https://github.com/pricing). The individual pro and team plans cost $7/month and $9/month respectively but they are free if you are [a student or an academic](https://education.github.com/pack).

Alternatively, [GitLab](https://about.gitlab.com/) uses a different business strategy with free private repositories and cost plans for public ones. There are also other alternatives e.g. [Bitbucket](https://bitbucket.org/).


### Markdown

- GitHub uses Markdown for text edition, a language with plain text formatting syntax (bold, italics, checkboxes, lists, etc.), to render pages online (like HTML but easier). You can use this syntax in text files (file extension: .md), commit messages, issues, blog posts, and more.

- Markdown is important because GitHub automatically renders anything written in Markdown. This can be specific files (eg: README), or your comments and issues.

- Some examples of Markdown syntax are available [here](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).



## Practical session: working with GitHub

We have several tutorials:

- [Create a GitHub account](README.md#create-a-github-account) (+)
- [Create your first repository](README.md#create-your-first-repository) (+)
- [Explore your GitHub account and first repository](README.md#explore-your-github-account-and-first-repository) (++)
- [Create an issue and a branch](README.md#create-an-issue-and-a-branch) (++)
- [My first pull request](README.md#my-first-pull-request) (+++)
- [Additional tutorials](README.md#additional-tutorials)


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

********************************************



### Explore your GitHub account and first repository

#### Your GitHub account

- Click on your top-right "avatar" icon and select "Settings".

<p align="center">
<img src=../../../20171024_GitHub_Chemistry_Cambridge/blob/master/images/p3_4.png width="800">
</p>

- Explore the tabs "Profile", "Account" and "Emails".


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

Bonus points:

- Try to create a second new file and add some content to it
- In your new repository, have a look at the "Settings" tab, explore "Collaborators" and try adding one of your colleagues

**Key glossary:**

- **Repository**: it can be thought of as a project folder. A **repository** contains all of the project files, issues, wikis and more. It also stores the history and versions of each file.

- **Commit**: equivalent to saving your changes to a file. When you **commit** you usually include a brief description of the changes you made so you can identify versions later if you want to undo a change.

- **Branch**: an identical copy of a project at a particular point in time kept separate from the 'master' branch (primary copy). This keeps your code in the 'master' branch safe while you make changes and experiment with code on the new branch. You can merge your new branch back into the 'master' branch when you want to publish your changes.

- **Master**: the default branch in your repository.

- **Collaborator**: someone with read and write privileges to a repository as approved by the repository owner.

********************************************



### Create an issue and a branch

Follow steps 5-8 in the [following page](https://kirstiejane.github.io/friendly-github-intro/exercises/my-first-repo/)



### My first pull request

Follow steps 1-7 in the [following page](https://kirstiejane.github.io/friendly-github-intro/exercises/my-first-pullrequest/)



### Additional tutorials

If you are more interested, try the following later:

- Working locally using [GitHub Desktop](https://kirstiejane.github.io/friendly-github-intro/exercises/working-locally/)
- Using GitHub to make [a webpage](https://open-source-for-researchers.github.io/open-source-workshop/practicalexercises/github/git-03-websites-with-github-pages)
- Markdown [tutorial](https://www.markdowntutorial.com)




## The End

Many Thanks for your attention! Enjoy Git and GitHub! :octocat:

Any questions/suggestions about this workshop or the materials? Just email me at: sermarcue@gmail.com



## References and materials

Blogs:
- [Beyond Basic R - Version Control with Git](https://owi.usgs.gov/blog/beyond-basic-git/)

Books:
- [Happy Git and GitHub for the R user](http://happygitwithr.com/)
- [Git book](https://git-scm.com/book/en/v2)

Courses:
- [Open Scientific Code using Git and GitHub](https://open-source-for-researchers.github.io/open-source-workshop/) by Yo Yehudi
- [A Friendly Introduction to GitHub](https://kirstiejane.github.io/friendly-github-intro/)
- [Software Carpentry: Version Control with Git](http://swcarpentry.github.io/git-novice/)
- [Resources to learn Git](http://try.github.io/)
- [GitHub On Demand Training](https://services.github.com/on-demand/)
- [A quick introduction to Git and GitHub](http://www.datacarpentry.org/semester-biology/materials/git-in-30-minutes/)

Help:
- GitHub [Help](https://help.github.com/)

Papers:
- Nature Methods 2018 editorial, [Easing the burden of code review](https://www.nature.com/articles/s41592-018-0137-5)
- Perkel 2018:
  - [When it comes to reproducible science, Git is code for success](https://www.natureindex.com/news-blog/when-it-comes-to-reproducible-science-git-is-code-for-success)
  - [TechBlog: Git: The reproducibility tool scientists love to hate](http://blogs.nature.com/naturejobs/2018/06/11/git-the-reproducibility-tool-scientists-love-to-hate/)
- Silver 2018 [Microsoft’s purchase of GitHub leaves some scientists uneasy](https://www.nature.com/articles/d41586-018-05426-0)
- Russell et *al.* 2018 [A large-scale analysis of bioinformatics code on GitHub](https://www.biorxiv.org/content/early/2018/05/14/321919)
- Perez-Riverol et *al.* 2016 [Ten Simple Rules for Taking Advantage of Git and GitHub](http://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1004947)
- Perkel 2016 [Democratic databases: science on GitHub](https://www.nature.com/news/democratic-databases-science-on-github-1.20719)
- Markowetz 2015 [Five selfish reasons to work reproducibly](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-015-0850-7)

Videos:
- [GitHub Training & Guides](https://www.youtube.com/githubguides)
- [Git & GitHub tutorial for Beginners](https://www.youtube.com/watch?v=3RjQznt-8kE&list=PL4cUxeGkcC9goXbgTDQ0n_4TBzOO0ocPR)

Websites:
- [git](https://git-scm.com/)
- [Mastering Markdown](https://guides.github.com/features/mastering-markdown/)



## Acknowledgements

<p align="center">
<img src=../../../20171024_GitHub_Chemistry_Cambridge/blob/master/images/UniversityCambridge_logo.png height="50"> <img src=../../../20171024_GitHub_Chemistry_Cambridge/blob/master/images/CRUKCI_logo.jpg height="50">
</p>
