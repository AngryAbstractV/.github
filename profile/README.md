## Hi there 👋

<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
# instructions for setting up enviornments to run different portions of the project
there are 3 different repo's in this organization depending on what portion of the project you are trying to access. those portions are
1. ImageProcessingAPI (python API Access)
2. FrontEnd
3. paintingEmotion (backend of image processing algorithms)

please scroll down to see how to set up the correct requirements to run each portion. These instructions are also availible in the readmes for each individual repo.

***

# Python API Access (ImageProcessingAPI):
Must have Python installed

## step 1: clone repo

## step 2: navigate to repo

## step 3: OS specific instructions

### Windows Instruction for Environment-

  pip install virtualenv

  virtualenv myenv

  myenv\Scripts\activate

  pip install -r requirements.txt

### Mac/Linux Instruction for Environment-

  pip install virtualenv

  virtualenv myenv

  source myenv/bin/activate
  
  pip install -r requirements.txt
  
  
## step 4: Turn on server-
  uvicorn --port 5000 --host 127.0.0.1 main:app --reload
  
  Server should be on 127.0.0.1
  
  Documentation for how to use the api can be found at https://54.219.178.171/docs#/

***

# Frontend (AAV-frontend):
Must have Node.js installed - Our version: https://nodejs.org/en/blog/release/v16.17.1/

  npm install
  
  npm start

***
# paintingEmotion:
(if you want to run individual image processing files or tests on your local)

Must have Python installed

## step 1: clone repo

## step 2: navigate to repo

## step 3: OS specific instructions

### Windows Instruction for Environment-

  pip install virtualenv

  virtualenv myenv

  myenv\Scripts\activate

  pip install -r requirements.txt

### Mac/Linux Instruction for Environment-

  pip install virtualenv

  virtualenv myenv

  source myenv/bin/activate
  
  pip install -r requirements.txt

