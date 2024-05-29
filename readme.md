<img src="https://play-lh.googleusercontent.com/dQbjuW6Jrwzavx7UCwvGzA_sleZe3-Km1KISpMLGVf1Be5N6hN6-tdKxE5RDQvOiGRg" style="width: 100px; height=100px; ">
<p>Step 1: <code>npm init</code></p>
<p>Step 1.1 (optional): Install nodemon</p>
<pre><code>npm i nodemon --save-dev
</code></pre>
<pre><code>"scripts": {
    "start": "nodemon app.js"
  }
</code></pre>
<p>- Paste the code inside quotation marks ("") on the line before the last brace mark ({}).</p>
<p>- To use nodemon, run <code>npm start</code> in the terminal.</p>
<p>- Then the server will be rerun after any change has been made in the code.</p>
<p>Step 2: Install packages</p>
<pre><code>npm i express
npm i axios
npm i body-parser
npm i crypto
</code></pre>
<p>Step 3: Install and SignUp for a ngrok account.</p>
<p>Because we need to connect your localhost with MOMO server via this ngrok application.</p>
<p>You can see that I am using a ngrok-generated link in <code>ipnUrl</code> to do a callback call to see the transaction detail.</p>

<p><strong>Note:</strong></p>
<p>Each time you start the server, you need to run:</p>
<pre><code>ngrok http --domain=[static-domain] [your-assigned-port-number]</code></pre>
<p>in the terminal to assign your ngrok domain to work as your global port online.</p>
<p>Through this global port, you can transfer your data with the MOMO server.</p>
<p>You don't have to do this, but I highly recommend it because you don't want to go and generate a link every time you run your server and then copy that into your code, right?</p>




