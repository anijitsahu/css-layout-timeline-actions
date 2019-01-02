# css-layout-timeline-actions
A Simple Chat Application using [React JS](https://reactjs.org/docs/getting-started.html), a JavaScript library to make awesome UI by Facebook, [Node JS](https://nodejs.org/docs/latest-v8.x/api/), [Express JS](https://expressjs.com/en/api.html) and [MongoDB](https://docs.mongodb.com/).

This application uses [React JS](https://reactjs.org/docs/getting-started.html) component oriented UI creation paradigm. All components are written in [JSX](https://reactjs.org/docs/jsx-in-depth.html) and ES6 style and are
combined to get a single build for production purpose using [Webpack 4](https://webpack.js.org/concepts/). 

ES6 `module` creation along with `import /export` is used. [Babel](https://babeljs.io/docs/en/babel-preset-react) is used to *transpile* all [JSX](https://reactjs.org/docs/jsx-in-depth.html) code to vanilla JavaScript code. To install all the dependecies `npm` is used.

Back end is implemented using [Node JS](https://nodejs.org/docs/latest-v8.x/api/), [Express JS](https://expressjs.com/en/api.html) and [MongoDB](https://docs.mongodb.com/). [Atlas](https://www.mongodb.com/cloud/atlas), the *Cloud* version of [MongoDB](https://docs.mongodb.com/) is used. Real time communication is done using [Socket.io](https://www.npmjs.com/package/socket.io)


For UI creation [HTML5](https://www.w3schools.com/html/html5_intro.asp) and [CSS3](https://www.w3schools.com/css/) are used. [Grid](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout), the new feature of [CSS3](https://www.w3schools.com/css/) is used for layout creation purpose.

This is a *responsive web application* for viewing in both Mobile and Desktop.


## Features
<ul>
 <li> This is Simple Chat Application </li>
 <li> It is a Full Stack Application </li>
</ul>

- All the user details, rooms and conversations are stored in the [MongoDB Atlas](https://www.mongodb.com/cloud/atlas). This is a *free/ shared* account on [Atlas](https://www.mongodb.com/cloud/atlas). **So Please use it wisely** 

<ul>
 <li>Login as well as Logout feature is added </li>
 <li>Error will be shown if the credentials are not correct</li>
</ul>

  - *for simplicity passwords are not encrypted*

<ul>
 <li> Real time communication is supported using <a href="https://www.npmjs.com/package/socket.io">Socket.io</a>
 <li> Rooms with users are supported </li>
 <li> Conversation of a specific rooms will be shown on clicking the corresponding room</li>  
</ul>

  - *for mobile screen user can go to the rooms page by clicking the `<-` icon at the end of the screen*
  - Multiline message can be send by hitting `Ctrl + ENTER`
  - To send a message hit `ENTER` key

<ul>
 <li> Online / Offline status are shown by the <i>violet dot</i> </li>
 <li> Read / Unread status of conversation is supported
 <li> All the conversation are stored in the database i.e. <i>persistant</i>
 <li> All the timestamps are shown in <i>UTC</i> format to taken into cross browser differences
</ul>

## Installation

1. Clone the repository using `git clone https://github.com/anijitsahu/react-app-simple-chat-app.git` from `Git Bash / Command Prompt`
2. Navigate inside the directory by `cd react-app-simple-chat-app`
3. Install all the necessary dependecies by using `npm install` 
4. Navigate to the directory `cd server`
5. Run the server by `node server.js`
6. Open the `2` web browser and type`http://localhost:3000` in the address bar to load the application in each of them
7. In one browser login with username `anijit` and password `anijit123`
8. In another one login with username `jeetm` and password `jeetm76` and enjoy chatting



 
*tested with <img src="screenshots/chrome.png" width="20px" title="Google Chrome">Google Chrome v70 and <img src="screenshots/firefox.png" width="25px" title="Firefox Developer edition">Mozilla Firefox Developer Editon*  

## Screenshots

Some screens of the application is given below for better understanding. 

Desktop as well as Mobile version of the screenshots are given side by side.

<p> Login Screen <br/> 
 <img src="screenshots/desktop 1.png" width="590px" title="Login screen"/>
 <img src="screenshots/mobile 1.png" width="190px" title="Login screen"/> 
</p>
 
