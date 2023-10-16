
A user is attempting to navigate to a website from inside the company 
network using a desktop. When the user types in the URL, 
https://www.site.com, the user is presented with a certificate mismatch 
warning from the browser. The user does not receive a warning when 
visiting http://www.anothersite.com. Which of the following describes this 
attack?
A. On-path
B. Domain hijacking
C. DNS poisoning
D. Evil twin

The answer is B Domain Hijack because the question discusses certificates. 
If it was a DNS poisoning (affects your system) then it'd be cache related 
or ARP, but since it is certificates with one working and one not then it 
is a hijacking of site.com

https://www.malwarebytes.com/cybersecurity/business/what-is-dns-hijacking#:~:text=DNS%20hijacking%20and%20DNS%20cache,actors%20corrupt%20the%20DNS%20 
"presented with a certificate mismatch warning"
Is the key term, which means that the website is taking the user to 
another website (DNS poisoning)
