[[Preguntas Falladas]]
[[ ]]
1. A user is attempting to navigate to a website from inside the company 
network using a desktop. When the user types in the URL, 
https://www.site.com, the user is presented with a certificate mismatch 
warning from the browser. The user does not receive a warning when 
visiting http://www.anothersite.com. Which of the following describes this 
attack?
* A. On-path
* **B. Domain hijacking**
* C. DNS poisoning
* D. Evil twin

The answer is B Domain Hijack because the question discusses certificates. 
If it was a DNS poisoning (affects your system) then it'd be cache related 
or ARP, but since it is certificates with one working and one not then it 
is a hijacking of site.com

https://www.malwarebytes.com/cybersecurity/business/what-is-dns-hijacking#:~:text=DNS%20hijacking%20and%20DNS%20cache,actors%20corrupt%20the%20DNS%20 
"presented with a certificate mismatch warning"
Is the key term, which means that the website is taking the user to 
another website (DNS poisoning)

---

2. A Chief Security Officer is looking for a solution that can provide increased scalability and flexibility for back-end infrastructure, allowing it to be updated and modified without disruption to services. The security architect would like the solution selected to reduce the back-end server resources and has highlighted that session persistence is not important for the applications running on the back-end servers. Which of the following would BEST meet the requirements?
* A. Reverse proxy Most Voted
* B. Automated patch management
* **C. Snapshots**
* D. NIC teaming

Because the snapshot takes the configuration of the server and compares it with the other backend servers to ensure that there is no mistakes

---

3. A company recently experienced an inside attack using a corporate machine that resulted in data compromise. Analysis indicated an unauthorized change to the software circumvented technological protection measures. The analyst was tasked with determining the best method to ensure the integrity of the systems remains intact and local and remote boot attestation can take place. Which of the following would provide the BEST solution?
* A. HIPS
* B. FIM
* **C. TPM**
* D. DLP

In this question, an attack has already occurred so preventative measures such as HIPS, FIM, or DLP would not be helpful. Also, the analyst wants to check the integrity of the system, and boot attestation can take place. TPM chips have mechanisms to prevent system tampering and boot attestation can be done with TPM based hardware to verify the state of the firmware, bootloader, etc. TPM is the best option here.

---

