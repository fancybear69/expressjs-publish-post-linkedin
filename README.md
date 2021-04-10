<h1 align="center">Coding Impulse </h1>
<a href="https://hack36.com"> <img src="http://bit.ly/BuiltAtHack36" height=20px> </a>
&nbsp
<p align="center">
    <img width="700" height="350" src="logo.jpeg" alt="App Logo" />
</p>


<h2>Table of Contents</h2>

- [Introduction](#introduction)
- [Features](#features)
- [Technology Stack](#technology-stack)
- [Installation](#installation)
- [Contributors](#contributors)


## Introduction

A Github App for posting the open source contributions on Linkedin for every pull request. The main goal of this project is to boost the motivation of the contributors. It will also help in creating awareness among others regarding the Open source software development. 

## Features

- Provides the diff of the pull requests opened.
- Provides the Organization Url, where the PR was opened.
- Response time for publishing post is negligible. 

## Technology Stack
- NodeJS
- Python3
- HTML/CSS
- EJS

## Installation
1. Clone this Repository.
2. Setup the NodeJS environment for  Linkedin Sign in page by moving to its directory (coding-impulse/linkedin-signin) and then running the following instructions:-
    ```bash
    npm i
    ```
3. Create the linkedin app for your profile and get client the id and secret from the Auth section and enter it in the config.js (coding-impulse/linkedin-signin/config.js) 
   ```bash
    node index
    ```
4. Open localhost:3000 on your browser. 
5. Sign in with your linkedin account and get the access token from the terminal.
6. Put the value of the access token in API.js (coding-impulse/linkedin-signin/lib/API.js) and then click on sign in to get the profile id from the terminal. 
7. Put the values of access token and profile id in the server.py (coding-impulse/Post-to-Linkedin/server.py)
8. Install the requests from Pypi:-
    ```bash
    pip install requests
    ```
9. Install the github [app](https://github.com/apps/post2linkedin) and choose all repositories option when prompted.
10. Make a PR and then check the linkedin post on your profile.  


## Contributors:

Team Name: Noobies
* [Ashish Malik](https://github.com/ashish493)
* [Aniket Prakash](https://github.com/anik31)

### Made at:
<a href="https://hack36.com"> <img src="http://bit.ly/BuiltAtHack36" height=20px> </a>

