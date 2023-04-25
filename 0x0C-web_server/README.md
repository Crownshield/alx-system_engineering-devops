# Web server completed a basic
configuration of the server using Nginx.

## Tasks :page_with_curl:

* **0. Transfer a file to your server**
  * [0-transfer_file](./0-transfer_file): Bash script that transfers a file
  from Holberton's client to a server.
  * Accepts four arguments:
    * The path of the file to be transferred.
    * The IP of the server to transfer the file to.
    * The username that `scp` connects with.
    * The path of the SSH privtae key that `scp` uses.
  * `scp` transfers the file to the user home directory `~/`.

* **1. Install nginx web server**
  * [1-install_nginx_web_server](./1-install_nginx_web_server): Bash script
  that configures a new Ubuntu machine with Nginx.
  * Nginx listens on port 80.
  * When querying Nginx at its root `/` with a `curl` GET request,
  it returns a page containing the string `Hello World`.

* **2. Setup a domain name**
 
