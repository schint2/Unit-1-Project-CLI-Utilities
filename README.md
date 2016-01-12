
# Node.js FasTrack


Proxy Server
This is a Proxy Server for Node.js submitted as the pre-work requirement for CodePath.

Time spent: [5 hrs]

Completed:

 Required: Requests to port 8000 are echoed back with the same HTTP headers and body
 Required: Requests/reponses are proxied to/from the destination server
 Required: The destination server is configurable via the --host, --port or --url arguments
 Required: The destination server is configurable via the x-destination-url header
 Required: Client requests and respones are printed to stdout
 Required: The --logfile argument outputs all logs to the file specified instead of stdout


![Video Walkthrough](https://raw.githubusercontent.com/schint2/Unit-1-Project-CLI-Utilities/master/GIF-N.gif)

 Starting the Server

 nodemon --exec babel-node -- -- index.js --logfile /tmp/proxy-server.log

 curl -v http://127.0.0.1:8000 -d "Hello-Sudhir"  -H www.google.com


Configuration:

CLI Arguments:

The following CLI arguments are supported:

--8000

The host of the destination server. Defaults to 127.0.0.1.

--8000 --8001

The port of the destination server. Defaults to 8000 when a host is not specified.

curl http://127.0.0.1:8000

curl -v http://127.0.0.1:8000 -d "Hello-Sudhir"  -H www.google.com

The follow http header(s) are supported:

x-destination-url
=======
# Node.js-Bootcamp
Node.js-Bootcamp
>>>>>>> c4ec1903fd4f6bea59e2a5cb638ac7962c832f78
