# ADVANCED-CSS-AND-SASS-NATOURS-PROJECT

1. BEM syling of CSS
1. SASS Variables

## Live Server
[CLICK ME](https://diamondabhishek.github.io/ADVANCED-CSS-NATOURS/)

### What is SASS?
- CSS preprocessor, an extension of CSS
- Called preprocessor because a compiler is needed to change it to CSS code
- Two syntax methods, SASS and SCSS, SCSS is used in this course

## Nodejs installation and SASS setup
1. Install nodejs from [here](https://nodejs.org/en/) on your computer.
    
1. Confirm node if installed by typing *node -v* in the terminal. (I did this in the git bash terminal)

1. Navigate into project folder using the terminal commands.

1. To run the downloaded file / clone file.(After the above steps)
```
  npm run start
```
1. Create package.json file by typing *npm init* in the terminal.
    + The prompt will prompt several questions for creating the file. In most cases the fields can be left blank or default values used.
    + If you download/clone project and want to install all dependencies simply run *npm install* in the terminal and 
    all dependencies in the package.json file will be installed. This illustrates the main purpose of this file. Another scenario is working on one project on more than one computer.
    + When uploading a project to a repository don't upload the node_modules file as it is not necessary.

1. Install SASS npm package by typing *npm install node-sass --save-dev* in the terminal.
    + The --save-dev saves the development dependencie in the package.json file.
    + Other packages such as jQuery should be saved as *--save* because they are non-development dependencies.
    + To uninstall a package (jQuery example) type *npm uninstall jquery --save* in the terminal.

  
