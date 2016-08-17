# nodeDAV
my WebDAV applications use jsDAV
#### How to use (on Mac/Linux)

	1. clone or download & unzip the source code into an empty folder
		/MyDAV
		
	2. open terminal and type
		cd /MyDAV
		
	3. make sure you have nodejs engine installed
		node --version
		
	4. run the server
		node server.js
		
	5. open the web interface on your browser
		http://localhost:8000/
		
	6. upload file from iOS simulator (you run source code on simulator)
		send a POST request via WebDAV protocol to the URL
		http://localhost:8000/
		with no user name and password (annonymous user)
	
#### About NodeJS

	you can google 'how to install nodejs' if you never run it on your machine before
	or reference their documents:
	
	https://nodejs.org

#### About jsDAV

	the underlying framework is jsDAV. please also refer to their documents:
	
	https://github.com/mikedeboer/jsDAV/wiki
	
	
	
