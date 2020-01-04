# **_DEVELOPMENT CURRICULUM_**

These are the essential skills that every prospective software developer in 2020 must be familiar with. I have built up this resource library by by curating my favorite blog posts, documentation sites and courses from around the web.

Here, you have access to some of my best curated resources which will help you understand the specifics of the various technologies in depth.

# **Setting up the development environment**

## 0. Operating System (For Windows Users only)

_You might want to shift to Linux or MacOS before you start the actual development._

> Unix by design was built for programming and development across the CS domains.
> It is the simplicity and straightforward ways in which you can find every programming environment available on a UNIX based/like OS that makes it better as a “programmer’s OS”.
> This is the reason why top developers and scientists use Linux or MacOS. They share the same terminal.

- ### Choose a Linux Distribution

  - **_Research thoroughly_** before choosing a Linux distribution.
  - 
    _My recommendations are :_
     - Manjaro 
     -  MX Linux 
     -  Linux Mint 
     -  Ubuntu 
     -  For advanced Linux users : Arch Linux. _(my personal favourite and daily driver!)_

    - ***Factors to consider*** before installing a Linux distro:-
        - Stable vs Rolling release
        - Availability of applications
        - Development friendly
        - Security
        - Package Manager and its download speeds
        - Desktop Environment  *(personal favourite: XFCE)*

> NOTE : There is no best Linux distribution. It depends on one's personal preferences.

## **1. Terminal**

It is strongly recommended that Windows users switch to a dual boot Linux configuration.
You might want to get that ugly terminal pumped up before starting development.
- ### **Install terminator**

- ### **Install zsh**
  The commands are 99% same. Zsh is the superior alternative of bash shell.
- ### **Switch to zsh as your default shell**
- ### **Install "Oh My Zsh"**
  It is a **zsh framework** which comes bundled with tons of plugins, helpers, themes, etc.
- ### **Install OhMyZsh extensions, themes, plugins etc.**
  You will need to ***configure .zshrc***
  - zsh-autocomplete
  - git 
  - jump
- ### **Customize the terminal to your liking.**
    #### Some recommendations :
    - Change the colour schemes and the **theme**
    - Try out Powerlevel9k
    - Apply a Powerline Nerd Font to your terminal. Eg : Hack Mono
- ### **Learn all the basic commands**
        - cd
    	- curl
    	- wget
        - ls / ll
        - rm , mkdir
        - pd
  
- ### **Basic Git commands**
  > These are of utmost importantance especially during version control - when working in a team.
  
  Here is a list of important commands, not in any particular order: 
  - clone
  - push
  - pull
  - merge
  - fork
  - revert
  - reset
  - branch
  - checkout
  - remote
  - add
  - status
  - log
  - commit
  - init
  - reset
  - stash 
  - fetch
  
  - ### **Learn GITTTT!!!**
>As your code gets larger and larger, it becomes important to have different versions, timestamps and more control over the development phase. 
> Git is the industrial standard. Learn how to use it from the command line.

  - [The Coding Train](https://www.youtube.com/playlist?list=PLRqwX-V7Uu6ZF9C0YMKuns9sLDzK6zoiV)
    
  - [Atlassian, yet another excellent resource](https://www.atlassian.com/git)
    
  - Github Pages
  - Github Student Pack for freebies
  
- ### **Basic Vim commands**
      -  Command Mode and Insert Mode
      -  !
      -  wq
      -  dd
      -  dw
      -  %s

- ### **Package managers**
    - Install nodejs and npm
    - yarn
    - homebrew (macOS)
    - Node version manager - nvm
    - ### For Linux users 
       - snap
  
  
## **2. Coding environment**
*A coding environment should be properly configured in order to increase your overall productivity during work.*


My general recommendations are as follows :- 
- ### **Terminal Editors**
   - vim
   - nano
  
- ### **Text Editors** 
  - VSCode *(personal favourite)*
  - Sublime Text 3
  - Atom
  - Brackets
  
  > **Currently VSCode is hands down the best editor cum IDE till date.**

- ### **Integrated Development Environments**
  - Jetbrains : Webstorm / Pycharm / Intellij Idea

>A software engineer's text editor of choice is somewhat just a personal preference. There isn't necessarily one right answer. 

>Visual Studio Code (VSCode) is my current text editor of choice. It is lightweight and easily extendable. It is built and maintained by Microsoft so it has really good native TypeScript support and is updated every month.

- ### **If youre using VSCode, do install tons of extentions and themes!**
    - git lens
    - code runner
    - live server
    - prettier
    - intellisense for all languages
    - intellicode
    - bracket pair colourizer 2
    - css peek
    - auto import
    - emmet
    - themes, icons based on personal preference.


# **_CURRICULUM_**

## No matter which route you take:

## ***Holy trinity of the Web Development***

- ## **1.HTML**
    Learning HTML is of utmost importance. 
    HTML is the standard markup language for Web applications.
    It is very easy to learn. 
    
    - Doctype
    - head and body
    - Block elements vs Inline Elements
    - span vs div
    - Connecting js to HTML file
    - Connecting css to a HTML file
    - Meta tags
    - HTML Canvas

    - Forms
        - Form structure
        - *Form Data Validation*
            - input
            - textarea
            - basic attributes
            - action
            - method
            - required
    - **Important Links for HTML**
        - [w3schools](https://www.w3schools.com/html/default.asp)
        - [mozilla docs for forms](https://developer.mozilla.org/en-US/docs/Learn/HTML/Forms/Your_first_HTML_form)
        - [html, css , js playlist](https://www.youtube.com/playlist?list=PLoYCgNOIyGAB_8_iq1cL8MVeun7cB6eNc)
  
- ## **2. CSS**
CSS is more concerned with the styling of webpages. 
Every CS student or budding developer should know how to create basic and beautiful interfaces, or at least have an idea about the CSS3 Model of the WebPage.
    
  - Box Model
  - Grid Systems
  - Responsiveness
    - Media Queries
    - Fluid Typography
    - Flex-box Model
    - CSS Grid
    - Display Block
    - cons of Hardcoding CSS Properties
    - Alignment - Horizontal, Vertical, Centering
  - Animations and Transitions
  - CSS Preprocessors 
  - Web Pages and User Interfaces
  - Sass/SCSS
      - How to use Sass Mixins
      - Post Processors
  - Autoprefixer
  - CSS Positioning 

 - **Important Links for CSS**

    - [w3schools](https://www.w3schools.com/css/default.asp)
    - [mozilla docs for css](https://developer.mozilla.org/en-US/docs/Web/CSS)
    - [html, css , js playlist](https://www.youtube.com/playlist?list=PLoYCgNOIyGAB_8_iq1cL8MVeun7cB6eNc)
    - [CSS tricks](https://css-tricks.com/)

- ## **HTML AND CSS frameworks and helpers**
   - [Bulma](https://bulma.io/)
   - [Bootstrap 4](https://getbootstrap.com/)
   - [Tachyons](https://tachyons.io/)
   - [PureCSS](https://purecss.io/)
   - [Materialize](https://materializecss.com/)

  

- ## **3. JS**
It does not matter in which domain you are. According to me, Javascript has been and will continue to be the most important programming language of the decade. The community, support and innovation seeping through this language is unparalled. The applications and the pay in JS is far more than other languages and unparallelled.

- Javascript is not JAVA !!
- Syntax
    - decision making
    - Functions 
    - Objects
    - Classes
    - var vs let vs const 
    - alert()
  
- JSON, cloning - deep cloning, shallow cloning
- Industrial functions - reduce, filter, map, entries
- Event Listeners , preventDefault()
- Arrow Functions (=>)
- Form Validation
- DOM - document object model 
- The JS Web Standards
  - ES5
  - ES6
  - ES7
  - ES8
  - ES9
- Promises
  - Async Await
  - AJAX 
  - fetch, then , catch, finally, all

- JQuery - an old school JS framework.

- Advanced front end libraries (any 1) *(industrial standard)*
    - React 
    - Angular
    - Vue
> React has the most stars on GitHub.

- ES5 modules, ES6 modules
    - module.exports
    - import, export -  export default

- Module Bundling
    - Browserify
    - Parcel
    - Webpack


- **Important Links for JS**

    - [w3schools](https://www.w3schools.com/js/default.asp)
    - [mozilla docs for js](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
    - [html, css , js playlist](https://www.youtube.com/playlist?list=PLoYCgNOIyGAB_8_iq1cL8MVeun7cB6eNc)




- # **Important Web Development Resources**

    - [FreeCodeCamp Certifications](https://www.w3schools.com/js/default.asp)
    - [How the internet works](https://www.youtube.com/watch?v=f0No0ZpZC04)
    - [Best Junior Web Dev Course Online](https://www.learningcrux.com/course/the-complete-web-developer-in-2020-zero-to-mastery)


## ***DEEP DIVE INTO BACKEND***


> Javascript at the backend is currently the industrial solution. 
> The same language is used at the client as well as the server side which makes it easier for developers to build fast scalable applications.


- ### *NodeJS and npm - global object*
    - http module, HTTP Requests
    - fs module
    - Node.js is non-blocking I/0 and event driven. Why?
    - Asynchronous behaviour in nodejs
    - Callback hell
    - Solution to callback hell
        - Async/Await and Promises
    - Sending mails using Node.js
        - nodemailer
- ### *Express.js*
    - state of the art most dependant web framework in the industry.
    - Express Routing
    - Middlewares


