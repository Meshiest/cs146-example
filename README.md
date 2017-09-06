## Pre-Setup

Install NodeJS/NPM:
* [Node.JS/NPM](https://nodejs.org/en/)

Install Git Shell:
* [Windows Git Bash](https://git-for-windows.github.io/)
* [Mac Git Shell](https://git-scm.com/download/mac)
* [Linux Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)

## Instructions:

1. Visit [https://github.com/Meshiest/cs146-example.git](https://github.com/Meshiest/cs146-example.git)
2. Fork repo
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