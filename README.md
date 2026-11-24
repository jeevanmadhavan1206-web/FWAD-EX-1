
EX-1 Developing a Simple Webserver

Date:

AIM:

To develop a simple webserver to serve html pages and display the Windows Specifications of your Laptop.

DESIGN STEPS:

Step 1:
HTML content creation.git clone PASTE_YOUR_GITHUB_LINK

Step 2:
Design of webserver workflow.cd REPOSITORY_NAME

Step 3:
Implementation using Python code.from http.server import HTTPServer, SimpleHTTPRequestHandler

server = HTTPServer(("127.0.0.1", 8000), SimpleHTTPRequestHandler)

print("Server Started Successfully")
print("Register Number: 26019416")
print("Name: Jeevan")

server.serve_forever()

Step 4:
Import the necessary modules.<html>
<head>
    <title>TCP IP Protocols</title>
</head>
<body>
    <h1>TCP/IP Protocol Suite</h1>

    <h2>Register Number: 26019416</h2>
    <h2>Name: Jeevan</h2>

    <h3>Protocols List</h3>
    <ol>
        <li>HTTP</li>
        <li>HTTPS</li>
        <li>FTP</li>
        <li>TCP</li>
        <li>UDP</li>
        <li>IP</li>
        <li>DNS</li>
        <li>SMTP</li>
        <li>DHCP</li>
        <li>ICMP</li>
    </ol>
</body>
</html>

Step 5:
Define a custom request handler.python server.py

Step 6:git add .
git commit -m "TCP IP Webserver Experiment"
git push origin main
Start an HTTP server on a specific port.

Step 7:
Run the Python script to serve web pages.git clone YOUR_REPOSITORY_URL

Step 8:
Serve the HTML pages.python server.py

Step 9:
Start the server script and check for errors.git add .
git commit -m "Web Server Experiment"
git push origin main

Step 10:
Open a browser and navigate to http://127.0.0.1:8000 (or the assigned port).
https://github.com/jeevanmadhavan1206-web/FWAD-EX-1/edit/main/README.md
PROGRAM:
<!DOCTYPE html>
<html>
<head>
    <title>TCP/IP Protocol Suite</title>
</head>
<body>
    <h1>TCP/IP Protocol Suite</h1>

    <h2>Student Details</h2>
    <p>Register Number: 26019416</p>
    <p>Name: Jeevan</p>

    <h2>Protocols List</h2>
    <ol>
        <li>HTTP</li>
        <li>HTTPS</li>
        <li>FTP</li>
        <li>TCP</li>
        <li>UDP</li>
        <li>IP</li>
        <li>DNS</li>
        <li>SMTP</li>
        <li>DHCP</li>
        <li>ICMP</li>
    </ol>
</body>
</html>


OUTPUT:python server.py

RESULT:Thus, a simple web server was successfully developed and executed in localhost (127.0.0.1:8000) to display HTML pages and the list of TCP/IP protocols.

The program for implementing simple webserver is executed successfully.
