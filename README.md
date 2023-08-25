# Dendry Starter Pack

This is a starter pack for [Dendry](https://github.com/aucchen/dendry) games. It includes a
basic game structure, a sample story, and a few useful extensions.

## Getting Started

First, duplicate (fork) this repository by clicking the "Use this template" button in the top right.  
<img width="176" alt="image" src="https://github.com/smwhr/dendry-starter-pack/assets/1090485/425a706a-ec08-49ff-a573-f6a768525ba9">  
and choose "create a new repository".

If you have a working node environment, we recommand running it locally (see below). Otherwise, you can do everything in the browser.

## Running on github pages

### Activate pages

In your forked repository, click the "Settings" button, then scroll down to the "Pages" section.  
In the "Build and deploy" section, select the "Github Actions" option, then click "Save".  
<img height="331" alt="image" src="https://github.com/smwhr/dendry-starter-pack/assets/1090485/322c183f-cb5d-423b-b81a-acd19fb70600">


### Edit the story

To open the github development environment by just pressing `.` in the browser.  
<img width="1030" alt="image" src="https://github.com/smwhr/dendry-starter-pack/assets/1090485/8d41e0cf-06f2-4ffa-a8e1-e164baa52ad6">  

It will allow you to modify the files in the repository directly from the browser.  
Each time you're satisfied with your changes, save (commit) them by clicking the "Commit and push" button in the source control <img height="20" alt="image" src="https://github.com/smwhr/dendry-starter-pack/assets/1090485/5bf0742a-61ad-490e-bc19-7c74a37c88a8"> menu. You'll need to add a "commit message" every time (it'll help you track your changes, but don't sweat it). 

<img width="349" alt="image" src="https://github.com/smwhr/dendry-starter-pack/assets/1090485/15d24de9-cb17-478e-a479-24564303f830">


### Publish the game
Each time you commit, it will automatically build the game and publish it on github pages (at the url https://YOURHANDLE.github.io/YOURREPONAME).  
If an error occurs (because you made a mistake in your code), you can see the logs in the "Actions" tab.

## Running locally

First of all, clone your forked repository.

### Install dependencies
Run `npm install` in the repository folder.

### Build the game
Run `npm run dendry make-html` in the repository folder.  
This will build the game and put the result in the `out/html` folder.  



