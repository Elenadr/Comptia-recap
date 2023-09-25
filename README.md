# Comptia recap

List of concepts that I had answer wrong when I am taking tests.


* **NetFlow** is a network protocol developed by Cisco for collecting IP traffic information and monitoring network flow. By analyzing NetFlow data, you can get a picture of network traffic flow and volume. Netflow is a Cisco propietary solition to monitor traffic thst psddrd through s router.
  
* **Geo-tagging** Verify whether the application is using any geo-tagging features that store geographical identifying information with media such as photos or video. This could be a privacy concern, as physical location could be determined from this geo-
tagged data.

## Backups
* **Full backups** back up every file that is selected and then clear the archive bit. necessitates a large storage capacity and a lot of time.
*  **Incremental backups** back up any files that have changed and then clear the archive bit so that the next backup will not back the file up (unless you do a full backup).
*  **Differential backups** back up any files that have had changes but do not clear the archive bit. Because the archive bit is not cleared, each differential backup will back up all files changed since the last full backup.

*  **Single sign on** --> Allows a user to autheticate(SSO) allows a user to authenticate to the network onceand access multiple systems without needingto provide additional credentials.the drawback of SSO is that if a hacker hacks the account, then the hacker can gain access to multiple servers.
* **Federation** A term used to describe authenticating and authorizing users across
organizations and application boundaries.
* HSM The Hardware Security Module is a card that is added to a system that
contains a crypto-processor to perform asymmetric cryptographic functions at the
hardware level. It also contains chips that store the crypto-keys to be used by the
system.
* Shimming/driver manipulation There are a few interpretations of shimming.
First, shimming is a type of attack on ATMs and self-service gas pumps where the
hacker inserts into the card reader a “shimmer” that can intercept the data
transferring to the terminal. As a result, the hacker can copy the card data, including
the account number and expiration date. The second scenario for shimming is

related to application code and driver manipulation. Following a continuous code-
improvement mindset, we are always looking for better ways to improve our code.

When an application has problems running in an environment, a shim can be
created and applied to the application to fix compatibility issues. As it relates to
driver manipulation, a shim can be created to allow a driver to run on an OS that
the driver had compatibility issues with. From a security point of view, shimming
an application could create a new vector for attacks because rewriting functions in a
shim and applying the shim to the application or driver could introduce a flaw by
accident, or on purpose if the person who created the shim is the hacker.

* **SLA** operation agreementswith the cloud provider or third-party company. Agreements such as a service level
agreement (SLA) specify guaranteed uptime.
* **BPA blanket purchase agreement ** is needed, which is used to cover repetitive needs for a product or
service.
* **memorandum of understanding (MOU)**, sometimes referred
to as memorandum of agreement (MOA), exists. A MOU/MOA is a document that
establishes an agreement between the two parties and specifies their relationship to
one another.
* **Nondisclosure agreement (NDA)** The nondisclosure agreement should be read
and signed by employees, contractors, and management personnel to acknowledge
that they understand and accept that they cannot share company sensitive information
that they gain access to while working at the company. The NDA applies not only while
working for the company but also after the work engagement has completed.

### eNVIROMENTS
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

## Acronimos 
 Un SOC (Security Operations Center) realiza una variedad de operaciones de seguridad para proteger los sistemas y datos de una organizació



---
Nic Teaming es una agrupación de tarjetas de red de un equipo, principalmente utilizado en  sistemas Windows Server con posibilidad de activarse en Windows 10 siempre que el equipo disponga de 2 o más tarjetas de red. 

Esta función permite agrupar las tarjetas de red físicas o virtuales disponibles en un equipo y  agruparlas para que se produzca un balanceo de carga proporcionando además tolerancia a  fallos y alta disponibilidad. 
