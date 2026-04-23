# Offensive Security:
-> Focuses on how the hacker thinks. It gives you a better understanding on how the penetration can occur and how it can be avoided.

## dirb :-
  
-> Used to find hidden pages.
  
-> After entering the syntax, every webpage shown with a '+' sign is a hidden page.

Syntax : dirb http://websitename

# Defensive Security:
-> Requires good observation on what is going on  in the website. (like if there is a unusual activity or something that is not seen on a regualar basis.) 

-> Requires you to detect and respond to Attackers. It is helpful in stopping them.

# DNS:

-> Stands for Domain Name System.

-> Used to access a website, because remembering the IP address is not easy.

-> IP Address - it usually has 4 sets of numbers ranging from 0 to 255. Eg :- 104.26.10.229

## Domain Hierarchy :-

### 1.Root domain : "."

### 2.Top Level domain :

-> gTLD - generic Top Level domain

Says the domain name's purpose.
Eg : .com - commertial,
.edu - education, etc

->  ccTLD - Country code Top Level domain

Shows geographical purpose.
Eg : .ca - canada, .in - India, etc

### 3.Second Level Domain :

-> Can have a maximum of 63 charecters

### 4.Subdomain

-> A DNS can have any number of subdomains.

-> The number of charecters all togeather is restricted to 253.

### -> admin.google.com

admin - subdomain

.google - 2nd level domain

.com - TLD

## DNS Record Types : 

### A records :

-> have IPv4 addresses.

Eg : 100.11.232.55

### AAAA record :

-> Have IPv6 addresses.

Eg : 2606:4700:20::681a:be5

### CName record :

-> CName - Canonical Name

-> These records resolve to another domain (Kind of relabeling).

### MX records :

-> MX - Mail Exchange

-> This tells the client in which order to try the servers.

### TXT records :

-> Records that  hold text data.

## DNS Request

1. Checks local cache.

2. Checks internet's root DNS server.

3. Redirects to TLD server.

4. Recursive DNS server.

-> DNS records come with a TTL (Time To Live) value.

# HTTP:

-> HyperText Transfer Protocol

-> It is the set of rules used for commuicating with the web server for transmitting of web page data.

## HTTPS :

-> HTTP Secure

-> secure version of http.

-> it shows weather you are using a correct we server, not a duplicate. 

## URL

-> Stands for Uniform Resource Locator.

->  It is predominatly an instruction to access resouses on the internet.

###  https://user:passwords@tryhackme.com:80/view-room?id=1#task3

Scheme (http) : This instructs on what protocol to use for accessing the resource such as HTTP, HTTPS, FTP (File Transfer Protocol).

User (user:passwords) : Some services require authentication to log in, you can put a username and password into the URL to log in.

Host (tryhackme.com): The domain name or IP address of the server you wish to access.

Port (80) : The Port that you are going to connect to, usually 80 for HTTP and 443 for HTTPS, but this can be hosted on any port between 1 - 65535.

Path (view-room): The file name or location of the resource you are trying to access.

Query String (?id=1): Extra bits of information that can be sent to the requested path. For example, /blog?id=1 would tell the blog path that you wish to receive the blog article with the id of 1.

Fragment (#task3) : This is a reference to a location on the actual page requested. This is commonly used for pages with long content and can have a certain part of the page directly linked to it, so it is viewable to the user as soon as they access the page.

### Making a request :

=> a request can be made using get/http/1.1


## HTTP Methods

-> GET Request

This is used for getting information from a web server.

-> POST Request

This is used for submitting data to the web server and potentially creating new records

-> PUT Request

This is used for submitting data to a web server to update information

-> DELETE Request

This is used for deleting information/records from a web server.

## HTTP Status Codes :

-> 100-199 - Information Response

-> 200-299 - Success	

-> 300-399 - Redirection	

-> 400-499 - Client Errors

-> 500-599 - Server Errors

### Common HTTP status codes  :

-> 200 - OK

-> 201 - created

-> 301 - moved permanently

-> 302 - found

-> 400 - bad request

-> 401 - not authorised

-> 403 - forbidden

-> 405 - method not allowed

-> 404 - page not found

-> 500 - interrnal service error

-> 503 - service unavailable

## Headers






