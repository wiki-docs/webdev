# Deploy website

To deploy a website to internet you need a web server configured to serve.

## Server

A server is a computer system or program that provides resources or services to other computers or programs, referred to as clients, over a network. It is designed to handle requests from multiple clients and manage access to shared resources, such as files, data, or applications.

Web servers can be categorized based on the software they use to serve web pages and the platform they are deployed on. Here are some common types of web servers:

1. [Apache HTTP Server](https://projects.apache.org/project.html?httpd-http_server): Apache is the most widely used web server software in the world. It is an open-source software that runs on a variety of platforms, including Unix, Linux, and Windows.

2. [Nginx](https://nginx.org/): Nginx is a high-performance web server and reverse proxy server. It is known for its ability to handle high traffic websites and is commonly used as a load balancer to distribute traffic across multiple servers.

3. Microsoft Internet Information Services (IIS): IIS is a web server software developed by Microsoft. It is designed to run on Windows servers and is often used to host websites and web applications built using Microsoft technologies, such as ASP.NET and C#.

4. [Lighttpd](https://www.lighttpd.net/): Lighttpd is a lightweight and fast web server designed for high-performance web applications. It is commonly used for serving static content, such as images and videos.

5. Node.js: Node.js is a server-side JavaScript runtime environment. It is commonly used to build scalable and high-performance web applications, as it allows developers to use JavaScript on both the client and server-side.

6. Google Web Server (GWS): GWS is a proprietary web server software developed by Google. It is used to serve Google's web pages and can handle high traffic websites.

7. Apache Tomcat: Apache Tomcat is a Java-based web server and servlet container. It is commonly used to deploy Java-based web applications and is often used in enterprise environments.

8. [Caddyserver](https://caddyserver.com/): Caddy 2 is a powerful, enterprise-ready, open source web server with automatic HTTPS written in Go 


## Configure your a web server

Configuring your own web server involves setting up and configuring the necessary software, configuring the server and network settings, and uploading your website files to the server. Here are some general steps to follow:

0. First you need a dedicated computer machine locally or remotely, with a hardware and a Operating System. 
    - Hardware: (CPU, GPU, cooling, box, etc)
    - Operating System: FreeBSD, Linux (Ubuntu server, CentOS, Clear OS, Debian Server, Fedora Server, SUSE Server), Windows Server

1. Choose your web server software: Decide on the web server software you want to use. Apache and Nginx are two popular open-source options.

2. Install the web server software: Install the web server software on your server. This may involve using a package manager, such as apt-get or yum, or downloading the software directly from the web server's website.

3. Configure the server settings: Configure the server settings, including the IP address, firewall rules, and network settings. This can be done through the command line interface or using a graphical interface, depending on your server's operating system.

4. Configure the web server software: Configure the web server software by modifying the configuration files. This can include setting up virtual hosts, configuring SSL certificates, and setting up URL redirection.

5. Upload your website files: Upload your website files to the appropriate directory on the server. This can be done using FTP or using a web-based file manager.

6. Test your website: Test your website to make sure it is accessible from a web browser. You can do this by navigating to the IP address or domain name of your server.

7. Configure DNS: Configure your domain name system (DNS) settings to point to the IP address of your web server. This can be done through your domain registrar or DNS provider.

8. Secure your server: Implement security measures, such as installing an SSL certificate, using a firewall, and keeping your software up-to-date, to protect your server from cyber threats.

9. Monitor your server: Monitor your server to make sure it is running smoothly and to identify any issues or potential security threats.

Note: The exact steps for configuring your own web server may vary depending on your server's operating system, the web server software you choose, and your specific needs and requirements. It is important to follow best practices for security and to keep your software up-to-date to ensure a secure and stable web server.


## Use a web hosting service

If you choose a web hosting service you can directly go to step 5, because the web server and the machine is already preconfigured. There are many options available, including shared hosting, VPS hosting, cloud hosting, and dedicated hosting. Choose a hosting service that fits your needs and budget.

- For version control system (with Git): [GitHub](https://github.com/), [GitLab](https://about.gitlab.com/), [Bitbucket](https://bitbucket.com/)
- Platform web service: [Amazon Web Service (AWS)](https://aws.amazon.com/), [Google Cloud](https://cloud.google.com/)

