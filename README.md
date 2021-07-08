# Link to the Github IO Page
https://suhasbhairav.github.io/orkg-pages-template/

# ORKG Pages Template
This repository is mirrored on GitHub https://github.com/TIBHannover/orkg-pages-template. 


It provides a simple example how to create a React based homepage that communicates with the ORKG backend. 

This example implements simple network functions which provide access to the ORKG backend and retrieve specific results.

If you have suggestions or find issues, please report them on the GitLab repository: https://gitlab.com/TIBHannover/orkg/orkg-pages-template


# How to Use
You can simply fork the project on GitHub.

Then clone your repository to your local machine and run: `npm install`

This will install all dependencies for the example project. 

## Local deployment
You can use `npm start` to start a local server on your machine.

## Necessary modifications (for the Example Project)
Please adjust line 21 in App.js
`this.githubRepoURL = '#CHANGE ME';`

This should point to your GitHub repository.


## GitHub pages deployment

Then run `npm run deploy`

This will build the project and inject it into you repository. 

(It creates a new branch for GitHub pages and enables them)

You can find the link to the deployed page in the settings of the repository (Settings -> Pages). 





# TODO 
- [ ] create wiki/documentation 
