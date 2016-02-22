# Network Tinkering

This place is mostly going to be all the research/information dump on network tools that I come across. These could vary from MITM proxy to scapy to other testing tools written by experts.

####Tools

1. [Scapy](http://www.secdev.org/projects/scapy/)
2. [MITM Proxy](https://mitmproxy.org/)
3. Kali Linux 

####Installation
 `pip install mitmproxy`

#####Some Interesting tutorials
1. [How To: Use mitmproxy to read and modify HTTPS traffic](https://blog.heckel.xyz/2013/07/01/how-to-use-mitmproxy-to-read-and-modify-https-traffic-of-your-phone/)

2. [Sniff iPhone HTTP Traffic using mitmproxy](http://blog.just2us.com/2012/05/sniff-iphone-http-traffic-using-mitmproxy/)

3. [Reverse engineering APIs] (http://www.toptal.com/back-end/reverse-engineering-the-private-api-hacking-your-couch)

4. [Use SSLsplit](https://blog.heckel.xyz/2013/08/04/use-sslsplit-to-transparently-sniff-tls-ssl-connections/)


**Kali Linux :**

I have installed it in a VirtualBox. You can download the VB file from the downloads sections. Here is how you unzip it:
`brew install p7zip`
`7z e filName.7z`

The file output is for the virtualbox. Double click on it and it will launch. 
Default values are :
username: root
password : toor

####Tips:

* Use Fn+Option key to select test of the response in the MITM proxy, this is specifically for MITM proxy.
