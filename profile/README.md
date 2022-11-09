## Hi there 👋

# What is this?
The goal of this project is to predict what emotion a painting will make someone feel.
We have two models for this one which is purely machine learning
and another that's based on algorithms modified from the ones provided in [Exploring Principles-of-Art Features For
Image Emotion Recognition](https://people.computing.clemson.edu/~jzwang/1501863/mm2014/p47-zhao.pdf) by Sicheng Zhao and co. 

### Website Link
To try the product for yourself, acess the website at this location: https://emotion-analyzer-5000.netlify.app/

# Various Repositories
There are 3 different repositories in this organization.
Depending on what portion of the project you are trying to access, click on the respective link to go to it.
1. [ImageProcessingAPI (Python API Access)](https://github.com/AngryAbstractV/ImageProcessingAPI)
2. [aav-frontend (Website/Frontend)](https://github.com/AngryAbstractV/aav-frontend)
3. [paintingEmotion (Backend of Image processing algorithms)](https://github.com/AngryAbstractV/paintingEmotion)

Set up instructions for each project are below.
These instructions are also availible in the readme's for each individual repo.
***

# Python API Access (ImageProcessingAPI):

## Step 1: Clone Repo
If you don't have git installed,
you can download [Git for Windows](https://gitforwindows.org/) if you're using a Windows machine.
Git should come by default with all Mac and Linux machines.

Navigate to wherever you want to have the project located using:

    cd <PATH>

An example is

    mkdir ~/my_git_projects
    cd ~/my_git_projects

Then clone the repository by typing this into your bash:

    git clone https://github.com/AngryAbstractV/ImageProcessingAPI

## Step 2: Install Python3
Open up Windows Powershell or Terminal in Administrator Mode.
If you have python and virtualenv installed already you may skip this step.

Check by typing:

    python --version

If that command doesn't show you your version,
download the latest python version from https://www.python.org/downloads/
and follow instructions to install.

## Step 3: Set up your Enviroment (OS Specfic)
Navigate inside of your repository by using within Windows Powershell or Terminal:

    cd <PATH>/ImageProcessingAPI

Replacing <PATH> with where you choose to store your project.

### Windows

    pip install virtualenv
    virtualenv myenv
    myenv\Scripts\activate
    pip install -r requirements.txt

### Mac/Linux Instruction for Environment

    pip install virtualenv
    virtualenv myenv
    source myenv/bin/activate
    pip install -r requirements.txt

## Step 4: Turn on server

    uvicorn --port 5000 --host 127.0.0.1 main:app --reload

Server should be at 127.0.0.1/5000, access it by placing that in the address bar of your browser.

***

# Frontend (aav-frontend):

## Step 1: Clone Repo
If you don't have git installed you, you can download [Git for Windows](https://gitforwindows.org/)
Navigate to wherever you want to have the project located using:

    cd <PATH>

An example is

    mkdir ~/my_git_projects
    cd ~/my_git_projects

Then clone the repository by typing this into your bash:

    git clone https://github.com/AngryAbstractV/AAV-frontend

## Step 2: Install Node.js Version 16.17.1
Download Node from https://nodejs.org/en/blog/release/v16.17.1/

    npm install
    npm start

## Step 3: Install Python3
Open up Windows Powershell or Terminal in Administrator Mode.
If you have python and virtualenv installed already you may skip this step.

Check by typing:

    python --version

If that command doesn't show you your version,
download the latest python version from https://www.python.org/downloads/
and follow instructions to install.

## Step 4: Set up your Enviroment (OS Specfic)
Navigate inside of your repository by using within Windows Powershell or Terminal:

    cd <PATH>/ImageProcessingAPI

Replacing <PATH> with where you choose to store your project.

### Windows

    pip install virtualenv
    virtualenv myenv
    myenv\Scripts\activate
    pip install -r requirements.txt

### Mac/Linux Instruction for Environment

    pip install virtualenv
    virtualenv myenv
    source myenv/bin/activate
    pip install -r requirements.txt

## Step 5: Turn on server

    uvicorn --port 5000 --host 127.0.0.1 main:app --reload

Server should be at 127.0.0.1/5000, access it by placing that in the address bar of your browser.

***
# paintingEmotion:
This is for if you want to run individual image processing files or tests on your local.

## Step 1: Clone Repo
If you don't have git installed,
you can download [Git for Windows](https://gitforwindows.org/) if you're using a Windows machine.
Git should come by default with all Mac and Linux machines.

Navigate to wherever you want to have the project located using:

    cd <PATH>

An example is

    mkdir ~/my_git_projects
    cd ~/my_git_projects

Then clone the repository by typing this into your bash:

    git clone https://github.com/AngryAbstractV/ImageProcessingAPI

## Step 2: Install Python3
Open up Windows Powershell or Terminal in Administrator Mode.
If you have python and virtualenv installed already you may skip this step.

Check by typing:

    python --version

If that command doesn't show you your version,
download the latest python version from https://www.python.org/downloads/
and follow instructions to install.

## Step 3: Set up your Enviroment (OS Specfic)
Navigate inside of your repository by using within Windows Powershell or Terminal:

    cd <PATH>/ImageProcessingAPI

Replacing <PATH> with where you choose to store your project.

### Windows

    pip install virtualenv
    virtualenv myenv
    myenv\Scripts\activate
    pip install -r requirements.txt

### Mac/Linux Instruction for Environment

    pip install virtualenv
    virtualenv myenv
    source myenv/bin/activate
    pip install -r requirements.txt

## Step 4: Turn on server

    uvicorn --port 5000 --host 127.0.0.1 main:app --reload

Server should be at 127.0.0.1/5000, access it by placing that in the address bar of your browser.

# Refrences
