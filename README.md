# Host a travel booking webpage
Host a travel booking webpage using HTML and CSS on an AWS Ubuntu server with the help of Nginx. 
This guide covers setting up an EC2 instance, configuring security groups, installing a web server, and deploying the webpage.
Launch an AWS EC2 instance with Ubuntu 22.04 LTS as the operating system. 
Configure security groups to allow SSH (port 22) and HTTP (port 80) access. 
Select an appropriate key pair for secure SSH access.
Connect to the instance via SSH using a terminal or an SSH client.
Install and configure Nginx as the web server. 
Start and enable the Nginx service to run at startup. 
Allow HTTP traffic through the firewall to make the server publicly accessible.
Navigate to the Nginx web directory where website files are stored. 
Remove the default index page and replace it with a custom webpage.
Create an HTML file for the travel booking page. 
Design the webpage using CSS for styling.
Add a background image to enhance the design
Modify the Nginx configuration to serve the custom webpage.
Ensure the server listens on port 80 for HTTP traffic.
Restart the Nginx service to apply changes. 
Open a browser and visit the public IP address of the instance to view the webpage.
To manage code versions efficiently, create a local Git repository.
This allows tracking changes and updating the hosted webpage as needed.
By following this guide, a fully functional travel booking webpage will be hosted on an AWS EC2 instance running Ubuntu and Nginx.
The website will be accessible via the public IP of the server, allowing users to search for destinations and book trips online.                                        
