# Intro to Socket.io

This project demonstrated a basic knowledge of using node.js, express.js and socket.io. These three technologies are combined to create a basic chartroom that functions in real time with usernames and supports multiple browsers. 

<h1> Node.js </h1>
Node.js is a very powerful JavaScript backend library that provides a wrapper around V8 JavaScript runtime in chrome. It is not an actual web framework. Node is completely non-blocking, which means its able to run different functions in parallel for example, you could upload a file and show the progress of the file upload at the same time- meaning a call from the browser to the server is happening at the same time as a call from the server to the browser. Stream between the client side and the server side allow for this to happen. When we want to read and write on a stream we are able to condense all of our code into a pipe (a single line of code, awesome!)

To make the most of node.js we have to use modules. Using npm (node package manager) we are able to share and have access to a repository of modules. These are kind of like ruby gems. In order to use modules we have to both require them in the js files, and include them in the dependencies of the package.json file. 

<h1>Express.js </h1>
Since node is a backend library, we have to combine it with a frontend framework to make fully-fledged applications. I chose to use express because it's very similarly constructed to Sinatra and was an easy transition for me to make. After installing the express module and including it in my dependencies in my package.json file, I explored and found that I can include an ejs (embedded JavaScript file) or just run an html file. I learned both and dabbled with jade, which is another space-sensitive front-end framework for node, but ultimately chose to use a basic html file for my views. I used jQuery put an event listener on the submit button of the chat form in order to append each message onto the chat box after the submit button was clicked on. 

<h1> Socket.io </h1> 
The relationship between a browser and a traditional server is a send/receive. Now we are able to use web sockets so that information can stream directly back and forth between the browser and server in real time without having to wait for information to flow cyclically. We use the socket.io module as a fallback to ensure we can access sockets on all browsers. Using event listeners and including the socket.io library, we are able to put have the server listen to events on both the client side and the server side simultaneously (thanks to the non-blocking nature of node). 


<h1>Overall </h1>
Issues that came up along the way were package errors with installing npm and xcode correctly on my machine, understanding how the npm dependencies work, and how information is passed or emitted from the browser to the server. 

Overall, I would definitely choose this technology again. It gave me a much stronger understanding of how JavaScript works and how powerful node.js is for performing in real time. I also began to dabble in jade as an alternative front end template engine, ejs for embedded JavaScript files (which are very similar in syntax to Sinatra erb) and ultimately made the transition from Rails/Sinatra to Node an easier one for me. Sockets are extremely powerful and can be used for any collaboration done over the Internet in real time ie. google docs, chartrooms, screen sharing etc.  
