# Comptia recap

# Index
* [General concepts](#general-concepts)  
* [Backups](#backups)
* [Signing methods](#Signing-methods)
* [Enviroments](#enviroments)  
* [Cloud Computing Models](#Cloud-Computing-Models)
    *[Different ways to implement cloud services](#Different-ways-to-implement-cloud-services)   
* [Vpn](#Vpn)
* [Acronyms](#acronyms)
* [Autor](#autor)
* [Licencia](#licencia)


# Documentación técnica
List of concepts that I had answer wrong when I am taking tests.

## General concepts

* **NetFlow** is a network protocol developed by Cisco for collecting IP traffic information and monitoring network flow. By analyzing NetFlow data, you can get a picture of network traffic flow and volume. Netflow is a Cisco propietary solition to monitor traffic thst psddrd through s router.
  
* **Geo-tagging** Verify whether the application is using any geo-tagging features that store geographical identifying information with media such as photos or video. This could be a privacy concern, as physical location could be determined from this geo-
tagged data.

* **Shimming/driver manipulation** There are a few interpretations of shimming. First, shimming is a type of attack on ATMs and self-service gas pumps where the
hacker inserts into the card reader a “shimmer” that can intercept the data transferring to the terminal. As a result, the hacker can copy the card data, including the account number and expiration date. The second scenario for shimming is related to application code and driver manipulation. Following a continuous code-
improvement mindset, we are always looking for better ways to improve our code.
When an application has problems running in an environment, a shim can be created and applied to the application to fix compatibility issues. As it relates to driver manipulation, a shim can be created to allow a driver to run on an OS that the driver had compatibility issues with. From a security point of view, shimming an application could create a new vector for attacks because rewriting functions in a shim and applying the shim to the application or driver could introduce a flaw by accident, or on purpose if the person who created the shim is the hacker.

* **Nic Teaming** es una agrupación de tarjetas de red de un equipo, principalmente utilizado en  sistemas Windows Server con posibilidad de activarse en Windows 10 siempre que el equipo disponga de 2 o más tarjetas de red. Esta función permite agrupar las tarjetas de red físicas o virtuales disponibles en un equipo y  agruparlas para que se produzca un balanceo de carga proporcionando además tolerancia a  fallos y alta disponibilidad. 
## Backups
*  **Full backups** back up every file that is selected and then clear the archive bit. necessitates a large storage capacity and a lot of time.
*  **Incremental backups** back up any files that have changed and then clear the archive bit so that the next backup will not back the file up (unless you do a full backup).
*  **Differential backups** back up any files that have had changes but do not clear the archive bit. Because the archive bit is not cleared, each differential backup will back up all files changed since the last full backup.

## Signing methods
  *  **Single sign on** --> Allows a user to autheticate(SSO) allows a user to authenticate to the network onceand access multiple systems without needingto provide additional credentials.the drawback of SSO is that if a hacker hacks the account, then the hacker can gain access to multiple servers.
  * **Federation** A term used to describe authenticating and authorizing users across organizations and application boundaries.
  
## Type of documents

  * **SLA, service level agreement**, operation agreementswith the cloud provider or third-party company. Agreements such as a  (SLA) specify guaranteed uptime.
  * **BPA, blanket purchase agreement** is needed, which is used to cover repetitive needs for a product or
service.
* **MOU, memorandum of understanding**, sometimes referred
to as memorandum of agreement (MOA), exists. A MOU/MOA is a document that
establishes an agreement between the two parties and specifies their relationship to
one another.
* **NDA, Nondisclosure agreement** The nondisclosure agreement should be read
and signed by employees, contractors, and management personnel to acknowledge
that they understand and accept that they cannot share company sensitive information
that they gain access to while working at the company. The NDA applies not only while
working for the company but also after the work engagement has completed.

### Enviroments
■ Sandboxing Sandboxing is the process of creating separate running environments
for applications and ensuring you restrict communication between these running
environments.
■ Environment You should create different environments for different stages of your
deployment. The following outlines the four environments you should have:
  * Development The development system or systems are used to develop or
  create the design of the solution.
  * Test Once the design is created, it is then tested on a test system or systems.
  * Staging Once the initial testing of the solution is completed, the solution is
  moved to the staging environment where more production-like validation is
  performed to ensure that the solution works.
  * Production After staging, you then place the solution into production.
  
■ Secure baseline A secure baseline is a set of configuration settings that places a
system in a secure state. Each system should have a secure baseline applied to ensure
that it meets the security requirements.
■ Integrity measurement Integrity measurement in computer security is ensuring
that you are aware of any changes that may occur to an environment. To implement
integrity of the system, be sure to use auditing features and hashing technologies to
track changes to the system and files.

### Cloud Computing Models
With different implementations of cloud computing, you need to be familiar with these terms for the Security+ certification exam:
  ■ Software as a Service (SaaS) With SaaS, the application is provided across the
  Internet, which means that you do not need to install the application at your site.
  ■ Platform as a Service (PaaS) Provides the computing platform as a service, which
  includes the hardware and software required to run a specific system such as an
  e-mail server or database server.
  ■ Infrastructure as a Service (IaaS) Provides computers, data centers, and network
  equipment as a service that the customer pays a monthly fee for based on the
  amount of resources used.
  
  #### Different ways to implement cloud services
    ■ Private cloud A private cloud means that you create the cloud services internally
  for your company and your company leverages those services. With a private cloud,
  the data is stored inside the company.
  ■ Public cloud A public cloud is provided by a service provider, and your data stored
  in the cloud would be located on that provider’s servers. It is important to stress that
  many organizations are not allowed to store sensitive data in a public cloud where
  the servers are hosted out of the country. It should be noted that cloud providers are
  creating data centers in different countries to address this concern.
  ■ Hybrid cloud A hybrid cloud is a mix of public and private cloud. The company
  may store nonsensitive data in the public cloud, but keep sensitive data stored in the
  private cloud.
  ■ Community cloud This type of cloud pools computing resources to make IT
  services available to multiple organizations with common needs, such as real-time
  access to a back-end database.

### Vpn
* With a **site-to-site VPN**, the secure tunnel is created
by a central device at each office location. All clients on each network send data through the
central encrypted tunnel, which gives the benefit of not needing to configure VPN software
on each client system. Another scenario where VPN can be used is with wireless networks. Because wireless
security protocols are known to have flaws, you can treat the wireless network as an
untrusted network and have a wireless client create a VPN connection to the server before
allowing the wireless client to access the corporate network.
up).

* The benefit of **always-on VPN** is that there is no reliance on the user; the system
automatically makes the connection and the feature is transparent to the user.

* **Full tunnel** is the traditional implementation in which a user launches VPN software
from a remote network, such as their home network, to create an encrypted tunnel between
their system and the corporate network VPN server. One of the problems users experience
with full tunnel is that they cannot access any resources on the LAN they are connected to
(in this case, the home network); for example, if they want to print to their home printer,
they cannot because technically once the VPN connection is made, the user is on the
corporate network and can access only those resources.

* **Split tunnel** is a VPN feature that allows the user to access the corporate network through
the secure VPN tunnel after the VPN software has been launched, but retain the capability
to access LAN resources. The split tunnel feature can specify which destination systems are
to have their traffic delivered through the tunnel and which traffic stays on the LAN. This is
known as split-include tunnel.



## Acronyms 

  SOC (Security Operations Center) realiza una variedad de operaciones de seguridad para proteger los sistemas y datos de una organizació
  PUP, potentially unwanted program
  CIRT, Computer Incident Response Team.
  RTO, Recovery Time Objective 
  FDE, Full  disk encryption
  UTM, Unified Threat Management
  HSM The Hardware Security Module is a card that is added to a system that contains a crypto-processor to perform asymmetric cryptographic functions at the hardware level. It also contains chips that store the crypto-keys to be used by the system.

---

# Autor
* [Elena María del Río](https://github.com/Elenadr)
# Licencia
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Licencia de Creative Commons" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/80x15.png" /></a><br />Este obra está bajo una <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">licencia de Creative Commons Reconocimiento-CompartirIgual 4.0 Internacional</a>. 
