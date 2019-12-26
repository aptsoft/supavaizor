# SUPAVAIZOR

Aim: automatic checking of milestones set by a developer (literarily, this program supervises development progress)

## Contributors

* [Edicha Joshua](https://github.com/edichaj)
* [Ayuba Ezekiel](https://github.com/ayuba-hub)

> Note: this is the development documentation including all ideas, description of algorithms and specifications

## Table of Contents

- [SUPAVAIZOR](#supavaizor)
  - [Contributors](#contributors)
  - [Table of Contents](#table-of-contents)
  - [Guidelines to working with this file](#guidelines-to-working-with-this-file)
  - [How to Contribute](#how-to-contribute)
    - [1: from git](#1-from-git)
    - [2: from github](#2-from-github)
  - [CURRENT TOPIC:](#current-topic)
  - [Features of the first beta version](#features-of-the-first-beta-version)
    - [#1: What other features could be included?](#1-what-other-features-could-be-included)
  - [Description of each Features](#description-of-each-features)
    - [1: Setting of milestones](#1-setting-of-milestones)
    - [2: Supervising codes written in python language only](#2-supervising-codes-written-in-python-language-only)
    - [3: Manual Progress checking in cmd](#3-manual-progress-checking-in-cmd)

## Guidelines to working with this file

* The contributor must understand markdown language (at least, should understand some basic syntax)
* Contribution can only be made on the current topic
* No repetition of ideas or modification of someone else's idea
* Contribution must be relevant, else, the contributor's changes or contribution to this file will be reverted by another contributor
* Be direct in stating solution, ideas or procedures
* All contributors must be active

## How to Contribute 

### 1: from git
> Note: as a contributor, you should add the repo as a remote locally on your machine
> 
* add this repository as a remote locally on your machine
  
```git

git remote add supavaizor https://github.com/edichaj/supavaizor.git

```

* create a local branch that tracks this current branch only

```git

git checkout --track supavaizor/docTrack

```

* open this file and add your contribution to the respective sections, commit with just a precise sentense
* push the changes back upstream (to the remote)

```git

git push supavaizor

```

> Note: if any issue occurs or probably you insist on using other procedures, you can search for it on [stack overflow](https://stackoverflow.com/) 

### 2: from github

On this current branch, edit this file and add your contributions to the respective sections and commit with a precise sentence on this branch

## CURRENT TOPIC:
> Features suggestion
[click here to navigate to the section](#features-of-the-first-beta-version)

## Features of the first beta version

* Setting of milestones
* Supervising codes written in python language only
* Manual Progress checking in cmd

### #1: What other features could be included?

> All suggestions should be included directly below this section in list format. the suggested features should be described as well

## Description of each Features

### 1: Setting of milestones
Milestones are forms of checkpoints. this checkpoints are defined by functions which perform unittest on the project main file and tries to update the progress of the development process based on the passes of the tests. the developer might be reqeusted to submit functions or methods and their desired output with which the program will import or try to run the functions or methods from the project main file and check if any error occured, if all went well, then, the milestone is reached and the program start running the test for the next milestone on the project main file.

### 2: Supervising codes written in python language only
This is to ease the development of this program because unittest module will be used for this first beta version and only works with python code (literarily)

### 3: Manual Progress checking in cmd
The checking should be done in python interactive mode in cmd

```cmd

python supavaizor.py

```

```python

check_progress(project_name)

```

> Note: all the API stated in this documentation can change, the official API and algorithms for performing the supervision will be in the official documentation of the program on the "master branch"