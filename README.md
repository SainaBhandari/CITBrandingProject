Template Repository for new projects on the CIT Pipeline
This readme is subject to updates at any time.

CIT Frontend 
Clone this repository to open the template. Opening the website will demonstate all the different options to change the font, colors, and feel of the website. 

This template only utilzes HTML and CSS for the frontend. The backend has seperate instructions (see CIT Pipeline Start). 

DO NOT MAKE CHANGES ON THIS REPOSITORY. Doing so will cause errors for future websites. 

CIT PIPELINE START

Projects that will be hosted on the CIT Pipeline must use Python/Flask for any server-side operations, using a WSGI wrapper and Gunicorn to run. Clone this repository to get the starting files that you need.

Immediately change all references to "flasktest" in filenames and in all files to the name of your project. Do not change the name of app.py, script.js, or wsgi.py. Do not change any contents in wsgi.py.
Once you get the "Hello, world!" version of your app running, push the changes to a new GitHub repository in this organization. You will need to request that new repository be created by an org admin.
As you develop your code, you should commit and push frequently, following all branching and version control best practices
You must generate and maintain a requirements.txt file from which a server administrator can install all dependencies using a single command pip install -r requirements.txt
Once version 1 of the app is published and live, you will need to configure GitHub Actions and webhooks to automatically push changes approved and deployed to the main branch. There MUST be a code review/pull request process implemented. No unapproved pushes/merges to main! See below for a reference GitHub Action YML
** Note that the frontend and backend of this repository are not programmed to talk "to eachother." With multiple ways to do this, a standard is not necessarily enforced.
