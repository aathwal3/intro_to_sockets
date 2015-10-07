# Intro to Socket.io

This project demonstrated a basic knowledge of using node.js, express.js and socket.io. These three technologies are combined to create a basic chatroom that functions in realtime with usernames and supports multiple browsers. 

<h1> Node.js </h1>
Node.js is a very powerful javascript backend library that providesa wrapper aruond V8 javascript runtime in chrome. It is not an actual web framework. Node is completely non-blocking, which means its able to run different functions in parallel for example, you could upload a file and show the progress of the file upload at the same time- meaning a call from the browser to the server is happening at the same time as a call from the server to the browser. Stream between the client side and the server side allow for this to happen. When we want to read and write on a stream we are able to condense all of our code into a pipe (a single line of code, awesome!)

To make the most of node.js we have to use modules. Using npm (node package manager) we are able to share and have access to a repository of modules. These are kind of like ruby gems. In order to use modules we have to both require them in the js files, and include them in the dependencies of the package.json file. 

Since node is a backend library, we have to combine it with a frontend framework to make fully fledged applications. 



Issues that came up along the way were package errors with installing npm and xcode correctly on my machine, understanding how the npm dependencies work, and how information is passed or emitted from the browser to the server. 

Overall, I would definitely choose this technology again. It gave me a much stronger understanding of how javascript works and how powerful node.js is for performing in real time. I also began to dabble in jade as an alternative front end template engine, ejs for embedded javascript files (which are very similar in syntax to sinatra erb) and ultimately made the transition from Rails/Sinatra to Node an easier one for me. 



