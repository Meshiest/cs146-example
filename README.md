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
  ![](https://i.imgur.com/G5sxlFW.png)
3. Open command line
    * Windows: Open Git Bash or Powershell
    * Mac/Linux: Open a Terminal
4. Clone the repo:
    `git clone https://github.com/[your git username]/cs146-example.git`
    * If you get a "Too many arguments" error, remove the brackets from your name
5. Change directory to the project folder
    `cd repo-name`
6. Install project dependencies
    `npm install`
    * If this doesn't work on windows git bash, try running these commands (`cd ...`, `npm install`) in a powershell
7. Copy minified jquery
    `cp node_modules/jquery/dist/jquery.min.js ./`
    * If this doesn't work on windows, try opening Git **Bash** if you're running this in cmd
8. Add and commit changes
    ```
    git add .
    git commit -m "your name CS146A"
    git push
    ```
    * If this wants you to do some weird `git config --global` thing, read those instructions!
    ![](https://i.imgur.com/tu25Bu4.png)
9. Open a pull requests with the same name as your commit message (Come back to my repo, there might be a notification, otherwise click "new pull request" on your repo)
    ![](https://i.imgur.com/YnqPXkb.png)
    ![](https://i.imgur.com/DP84fpb.png)
