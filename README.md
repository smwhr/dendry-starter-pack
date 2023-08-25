# Dendry Starter Pack

This is a starter pack for [Dendry](https://github.com/aucchen/dendry) games. It includes a
basic game structure, a sample story, and a few useful extensions.

## Getting Started

First, fork this repository by clicking the "Fork" button in the top right.  

### Running on github pages

*Activate pages*  
In your forked repository, click the "Settings" button, then scroll down to the "GitHub Pages" section.  
In the "Build and deploy" section, select the "github actions" option, then click "Save".

*Edit the story*
Then open the github development environment by pressing the "Open in Github" or just press `.` in the browser.  
It will allow you to modify the files in the repository directly from the browser.  
Each time you're satisfied with your changes, commit them by clicking the "Commit" button in the top right, 

*Publish the game*
Each time you save, it will automatically build the game and publish it on github pages.  
If an error occurs, you can see the logs in the "Actions" tab.

### Running locally

*Install dependencies*
Run `npm install` in the repository folder.

*Build the game*
Run `npm run dendry make-html` in the repository folder.  
This will build the game and put the result in the `out/html` folder.  



