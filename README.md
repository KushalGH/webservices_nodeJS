# webservices_nodeJS

I will practicing  NodeJS web services like Empress.JS, Sails.JS and Hapi.JS 

Oh yeah, I am using Ubuntu. So, please check the documentation for for other OS. hoping it will be quite same. 


## ExpressJS
	### STEP 1: Installation
	- Let's start with ExpressJS. 
	- Install Express : [INSTALLATION GUIDE: http://expressjs.com/en/starter/installing.html] 
		- $ mkdir expressjs
		- $ cd expressjs
		- $ npm init
		- Now install Express in the myapp directory and save it in the dependencies list.
			- $ npm install express --save

	### STEP 2: Create the working JS
	- $ touch index.js

	### STEP 3: Create First Hello World app [http://expressjs.com/en/starter/hello-world.html]
	- Copy paste the code in index.js

		```
			const express = require('express')
			const app = express()
			const port = 3000

			app.get('/', (req, res) => res.send('Hello World!'))

			app.listen(port, () => console.log(`Example app listening on port ${port}!`))

		``` 

	### STEP 4: Run the index.js
	- $ node index.js
		- Your first Hello World! will be running at http://localhost:3000/


	### STEP 5: Let's discuss the code [http://expressjs.com/en/guide/writing-middleware.html]
		- ![picture](expressjs/images/initial_code.png)

	### EXPRESS JS DOCUMENTATION
		- https://expressjs.com/en/guide/writing-middleware.html



