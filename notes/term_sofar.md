## some of the key terminology that we have covered in class so far

###web server
a web server is software that exists on a hardware server and is responsible for actually sending, serving web pages.  

here are a few popular web servers:

[apache](https://httpd.apache.org/)  
[nginx](https://www.nginx.com/)  
[lighttpd](https://www.lighttpd.net/)

###HTTP
hypertext transfer protocol
HTTP is a stateless protocol based on a request response model.  
your browser(the client) sends a *request* for data from a web server.  
the server *responds* by sending the data formated as an HTML document.

###URL
a Uniform Resource Locator is a specific type of URI(Uniform Resource Identifier).  
a URL specifies the location of a web resource on a network.

###DNS
Domain Name System is the system used to convert IP Addresses to more easily remember domain names.

###deployment technology

**"bare metal" servers**  
the term bare metal refers to the actual hardware. you either own, or rent your own physical server. this option offers the most control over the server configuration.

[scaleway](https://www.scaleway.com/)

**VPS, virtualized servers**  
a VPS, virtual private server is a bare metal server running virtualization software such as Xen. This allows the server to affectively be divided up into smaller virtual servers. one of the downsides to this method is that the virtualization layer adds additional overhead, it is a program running on your server using up memory. one of the primary advantages is of course cost, most bare metal server options are quite expensive.

[how to select a VPS](https://redfern.me/choosing-a-low-cost-vps/)


some popular VPS providers:  
[digitalocean](https://www.digitalocean.com/)  
[linode](https://www.linode.com/)  
[prgmr](https://prgmr.com/xen/)

**IaaS infrastructure as a service**  
IaaS, often referred to as 'Cloud Computing' is similar to a VPS. the largest difference is that while with a VPS you rent fixed resources at a fixed monthly rate, with IaaS you rent flexible resources and generally pay for what you use. think of it like a cell phone bill vs an electricity bill.

[AWS](https://aws.amazon.com/)

**PaaS platform as a service**  
sometimes referred to as 'cloud platform services' offer an additional layer of abstraction. hardware resources, servers and middleware are all administered by the provider. Many developers prefer this model because it requires that they spend less time working on the under lying infrastructure.  

[Google App Engine](https://cloud.google.com/appengine/)  
[Heroku](https://www.heroku.com/home)

###REST

Representation State Transfer
RESTful services are designed to be lightweight, maintainable and scalable. 


###API 
Application Programming Interface
A set of protocols, tools for building software to interface with other software.
describes operations and input and output, allowing software developers to write scripts to for example retrieve data from twitter.

###CGI  
Common Gateway Interface  
cgi is a method by which scripts residing on a hardware server can communicate with a web server.

###WSGI  
Web Server Gateway Interface  
WSGI is an interface specification that allows for a python script to communicate with a web server.  
[learn more](http://wsgi.readthedocs.io/en/latest/index.html)
