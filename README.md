## Pre-Setup

Install NodeJS/NPM: (This manages libraries you probably won't use)
* [Node.JS/NPM](https://nodejs.org/en/)

Install Git Shell: (This helps keep track of your code so you're not passing around a USB or using Google Drive)
* [Windows Git Bash](https://git-for-windows.github.io/)
* [Mac Git Shell](https://git-scm.com/download/mac)
* [Linux Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)

Take a tour of Git: (It's only a _little_ confusing in the beginning)
[Learn Git](https://try.github.io/)

## Instructions:

1. Visit [https://github.com/Meshiest/cs146-example](https://github.com/Meshiest/cs146-example)
2. Fork repo
  ![](http://i.imgur.com/G5sxlFW.png)
3. Open command line
    * Windows: Open Git Bash
    * Mac/Linux: Open a Terminal
4. Clone the repo:
  `git clone https://github.com/[your git username]/cs146-example.git`
5. Change directory to the project folder
  `cd repo-name`
6. Install project dependencies
  `npm install`
7. Copy minified jquery
  `cp node_modules/jquery/dist/jquery.min.js ./`
8. Add and commit changes
    ```
    git add .
    git commit -m "your name CS146A"
    git push
    ```
9. Open a pull requests (Come back to my repo, there will be a notification)
  ![](http://i.imgur.com/YnqPXkb.png)
  ![](http://i.imgur.com/DP84fpb.png)
