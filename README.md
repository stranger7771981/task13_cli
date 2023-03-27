#### task13_cli




1. Create another Golang application: it should work as a CLI. Let's call this application just cli.

2. When you run this application in your terminal as follows: cli localhost:80 Andrey it should return as output Hello Andrey!.


3. Internal mechanics: The cli executes GET request containing {"name": "Andrey"} payload  towards our backend application and simply prints the body of    
   the response.  (given by the backend to our GET request ) 