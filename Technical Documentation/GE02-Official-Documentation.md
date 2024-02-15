# GE 02 Technical Documentation
***
###### Logan Lassiter
###### Naomi Rodriguez
###### Irving Reyes Bravo

***
## Table of Contents

[[GE02-Official-Documentation#^5c2d37|Getting Started]]

[[GE02-Official-Documentation#^2f7398 |2.1 Create Virtual Environment and Django Project]] `Logan`

[[GE02-Official-Documentation#^eb2d24|2.2 Create Local Git and Github Repository]] `Logan`

[[GE02-Official-Documentation#^37a45a|2.3 Create Portfolio App]] `Irving`

[[GE02-Official-Documentation#^4bb8fe|2.4 Define URI path and view]] `Irving`

[[GE02-Official-Documentation#^c457bf|2.5 Create HTML Template]] `Naomi`

[[GE02-Official-Documentation#^b92dca|2.6 Add static files]] `Naomi`

***

## Getting Started

^5c2d37

***
## 2.1 Create Virtual Environment and Django Project

^2f7398

<sup>These instructions show examples of working on a Mac for the commands. Note how you must run the commands in your environment.</sup>

#### Activation and Installation of Django 4.2

#### 1. Open the terminal and check your python version.

* Inside of the terminal, enter these commands:

	```bash
	$ python3 --version
	```

	<sup>You should be using python version 3.11</sup>

![[images/Pasted image 20240214114533.png]]

* Inside of the portfolio directory, run commands:
	```bash
	$ source djvenv/bin/activate
	$ pip install Django==4.2
	$ python -m django --version
	```
	<sup>These commands will let you activate the Django virtual environment, install Django version 4.2, and confirm that you have the right version installed</sup>
	
	![[Pasted image 20240214124051.png]]
	![[Pasted image 20240214124114.png]]
***
## 2.2 Create Local Git and Github Repository

^eb2d24
#### 1. Prepare existing local directory to be added to GitHub

* If you do not have an existing local directory to use for your Github repository create one
	```bash
	$ mkdir [directory-name]
	```
	![[Pasted image 20240214125813.png]]
	
	Here is a guide to [create a repo from an existing local directory](https://docs.github.com/en/migrations/importing-source-code/using-the-command-line-to-import-source-code/adding-locally-hosted-code-to-github)
* Use the following commands (if you run into trouble revert to linked guide):
	```bash
	$ cd [your-local-directory]
	$ git init -b main
	$ touch .gitignore
	$ git add .
	$ git commit -m "First commit"
	```
	1. change directory to the local directory you want to use for your repo
	2. initialize the main branch
	3. create .gitignore file (more on .gitignore below)
	4. stage the files for initial commit
	5. commits/saves changes and prepares them to be pushed
	   
	![[Pasted image 20240214130457.png]]
#### 2. Create and link GitHub repo with local directory.
* Create a new repository on GitHub.com
	*  Make the repository private
	*  Do not initialize ReadMe, license, .gitignore files
	* You may need to setup authentication with GitHub, follow the HTTPS guide [here](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/about-authentication-to-github#https)
* Copy the repository URL and open your local project directory in the terminal.
* Use the following commands:
	```bash
	$ git remote add origin [copied-repo-URL]
	$ git remote -v
	```
	1. links local directory to GitHub Repo
	2. verifies link was successful
	
	![[Pasted image 20240214132419.png]]

#### 3. Push changes in local directory to GitHub.com
* Run the following command:
	```bash
	$ git push -u origin main
	```
***
## 2.3 Create Portfolio App

^37a45a

***
## 2.4 Define URI path and view

^4bb8fe

***
## 2.5 Create HTML Template

^c457bf

***
## 2.6 Add static files

^b92dca

***
