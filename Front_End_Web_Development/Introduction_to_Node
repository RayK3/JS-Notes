Introduction to Node.js 
  Node.js is an open-source project that lets you write Javascript that runs outside the browser.
  When you write JS for the browser, your code is given access to global objects like the document and window, as well as other API's and libraries.
  With Node, your code can access the hard drive, databases, and the network.
  
  The package.json file
    This is created using npm init, and it acts as your Node project's manifest. It holds your project's name, version number, description,
    and other information. You can create this file by hand, or you can let npm do it for you. 
    
  When starting a new project
    Make a directory, and move into it. Then run npm init in it. This will create a package.json file with pretty sensible defaults. 
    
  One of the keys in package.json is scripts. Here you can add any commands you might need to run again and again. 
  
  When you use the http module, you can create a server using 
    var server = http.createServer(function (req, res) {//something}); 
    - This callback pattern should look a little familiar from browser events, but in this case, it is an event happening on the server. 
    Namely, an http request. 
    
  There is a module called nodemon that automatically stops and restarts your program whenever you save changes. If you 
  save this in the scripts portion of package.json though, you will need to say 'npm run {scriptname}'
  
  You can use the req.url property for access to the url that the request sent. 
  
  Using the path module 
    This allows it easier to manipulate the file path
    
  Creating a custom module:
    You just need to create a separate js file with any of the extra functionality that you are looking for. 
    After declaring any functions, in order to make them available globally, you can use the global variable named module.exports
    ex:
      module.exports = extractFilePath;
      
  Handling errors:
    Node.js callbacks typically have an error argument as their first argument. 
    It is really common to have a dedicated function called handleError to handle errors. It's as easy to write a 404 error response as 
    this:
      res.writeHead(404);
      res.end();
    
    This pattern - "errors first, return early" - is one of the best practices that is a part of the Node ecosystem. 
  
  Mime Types: 
    Have you ever wondered how a computer knows how to open a movie file with a video player and a PDF with a document viewer? Your computer
    keeps a table of file types and the programs associated with those file types. It infers a file's type by looking at the file extension. 
    
  
