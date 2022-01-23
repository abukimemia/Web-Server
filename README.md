# How to Create a Web Server in Node.JS with the HTTP Module
## Overview
When viewing a webpage on the browser, a user is making a request to another computer on the internet which will provide a response to the user as a webpage. The computer, the user is talking to via the internet is known as a _web server_. A web server recieves HTTP requests from a client and provides a HTTP response like a HTML page.
This is a step solution on how to build a web server using the `http` module that is included in Node.js. This web server can return static and dynamically generated HTML web pages.

#### Prerequisites
Please ensure that Node.js and NPM is installed on your development machine. Visit [Node](https://nodejs.org/en/download/) for steps on how to install Node.js which will also include npm in your installation process.

### Step 1: Creating a folder for your project
First, we will create a folder in the terminal called `first-servers`:
   ```batchfile 
   $ mkdir first-servers
   ```
then enter that folder:
   ```batchfile
   $ cd first-servers
   ```

### Step 2: Clone this repository
Now clone this repository to your directory. In your terminal, type `git clone`, then paste the URL of this repository i.e.:
   ```shell
   $ git clone https://github.com/abukimemia/Web-Server.git
   ```

### step 3: Install missing dependencies
Once the code has been cloned into your directory, we will install the missing dependencies onto our project so that it can run successfully. Use the following command in your terminal:
  ```shell 
  $ npm install 
  ```
This process should take a while and once all the dependencies are successfully installed, open the project in your code editor of choice. If your code editor is **VS Code**, type the following command in your terminal to open vs code:
  ```shell
  $ code .
  ```
  
  ### Step 4: Run server
In your terminal in the project's directory, type the following command to run the server:
  ```shell
  $ node htmlFile.js
  ```
The server runs on `localhost` or ip address `127.0.0.1` on port `8000`. On your browser enter the following url address to receive a _HTTP reponse_ from the server:
  ```
  http://localhost:8000
  ```

