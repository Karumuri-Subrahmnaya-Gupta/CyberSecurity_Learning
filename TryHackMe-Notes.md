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



