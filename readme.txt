Step 1: npm init
Step 1.1 (optional): #To install nodemon
npm i nodemon --save-dev
"
,
    "scripts": {
    "start": "nodemon app.js"
  }
"
- Paste the code inside quotation marks ("") on the line before the last brace mark ({}).
- To use nodemon, run "npm start" in the terminal.
- Then the server will be rerun after any change has been made in the code.
Step 2: Install packages
npm i express
npm i axios
npm i body-parser
npm i crypto
Step 3: Install and SignUp for a ngrok account.
Because we need to connect your localhost with MOMO server via this ngrok application.
You can see that I am using a ngrok-generated link in ipnUrl to do a callback call to see the transaction detail.

#Note: 
Each time you start the server, you need to run:
ngrok http --domain=[static-domain] [your-assigned-port-number] in the terminal to assign your ngrok domain to work as your global port online.
Through this global port, you can transfer your data with MOMO server.
You dont have to do this but i highly recommend it because you dont want to go and generate a link  every time you run your server then copy that into your code, right?



