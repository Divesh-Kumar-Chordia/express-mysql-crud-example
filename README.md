<h1>Express-MySQL CRUD Example</h1>

<p>This repository demonstrates how to perform CRUD (Create, Read, Update, and Delete) operations on a MySQL database using the Express framework and the mysql library.</p>

<h2>Usage</h2>

<p>1. Clone the repository</p>
<pre>git clone https://github.com/Divesh-Kumar-Chordia/express-mysql-crud-example.git</pre>

<p>2. Install the dependencies</p>
<pre>npm install</pre>

<p>3. Edit the MySQL connection details in app.js file to match your MySQL setup</p>

<p>4. Start the server</p>
<pre>nodemon app.js</pre>

<p>5. Test the different endpoints on your browser</p>
<pre>http://localhost:3000/createdb</pre>
<pre>http://localhost:3000/createpoststable</pre>
<pre>http://localhost:3000/addpost1</pre>
<pre>http://localhost:3000/addpost2</pre>
<pre>http://localhost:3000/getposts</pre>
<pre>http://localhost:3000/getpost/1</pre>
<pre>http://localhost:3000/updatepost/1</pre>
<pre>http://localhost:3000/deletepost/1</pre>

<p>Note: Make sure to have MySQL service running on your machine before starting the server</p>

<h2>Description</h2>

<p>This repository includes examples for:</p>
<ul>
  <li>Creating a database and table</li>
  <li>Inserting data into the table</li>
  <li>Querying data from the table</li>
  <li>Updating data in the table</li>
  <li>Deleting data from the table</li>
</ul>

<h2>Dependencies</h2>
<ul>
  <li>express</li>
  <li>mysql</li>
</ul>
