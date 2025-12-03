To host a static website on AWS, I launched a Free Tier EC2 instance. I then installed and configured Nginx on the Ubuntu EC2 instance. After that, I uploaded my resume HTML file and placed it in the Nginx default web directory (/var/www/html) so it could be served as a website.

To make the site publicly accessible, I updated the Security Group to allow HTTP traffic on port 80 from anywhere and ensured the EC2 instance had a public IP address.

This setup allows my resume website to be viewed by anyone using the EC2 instance’s public IP on port 80.
