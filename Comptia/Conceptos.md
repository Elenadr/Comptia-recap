
[[Progreso]]

Índice

1. [Race Condiction](#race-condiction)
1. [SSL Stripping](#ssl-stripping)
1. [Replay attack](#replay-attack)
1. [Watering hole](#watering-hole)
1. [Typosquatting](#typosquatting)
1. [Invoice scam](#invoice-scam)
1. [DMARC](#dmarc)
1. [MSSP](#mssp)
1. [Wildcard](#wildcard)
1. [SAN](#san)
1. [Self-signed](#self-signed)
1. [Code signing](#code-signing)
1. [Backup Completo (Full Backup):](#backup-completo-full-backup)
1. [**Backup Incremental:**](#backup-incremental)
1. [**Backup Diferencial:**](#backup-diferencial)
1. [**Password Spraying (Aspersión de Contraseñas):**](#password-spraying-aspersi%C3%B3n-de-contrase%C3%B1as)
1. [**Rainbow Table (Tabla Arcoíris):**](#rainbow-table-tabla-arco%C3%ADris)
1. [**Unified Threat Management (Gestión Unificada de Amenazas):**](#unified-threat-management-gesti%C3%B3n-unificada-de-amenazas)
1. [**Round Robin:**](#round-robin)
1. [**Active-Passive:**](#active-passive)
1. [Staging](#staging)
1. [Dkim](#dkim)
1. [Wids](#wids)


#### A legal hold 
s a process in which an organization is required to preserve all relevant electronically stored information (ESI) and paper documents that may be related to a pending or anticipated legal action. It is typically initiated by law enforcement or legal authorities when there is an investigation, lawsuit, or audit involving the organization. During a legal hold, the organization is prohibited from destroying or altering any potentially relevant data or documents to ensure that evidence is preserved and available for the legal process.
#### Service accounts 
Secure operating systems such as Windows and Linux require
that everything authenticates to the system, whether it is a user or a piece of
software. When software runs on the system, it needs to run as a specific user so that
the software can be assigned permissions. The user account that you associate with
a piece of software is known as a service account because it is a feature that is used
by services running within the operating systems as well. When creating a service
account (the user account that the software application will be configured to use),
you typically configure the service account with a strong password and specify that
the password never expires.
#### Dns Poisoning

domain resolving the wrong IP address.

#### On path - MITM
A very important type of network attack is a man-in-the-middle (MITM) attack. With an
MITM, the hacker inserts himself in the middle of two systems that are communicating.
As shown in Figure 4-6, after the hacker inserts himself between the two parties that arecommunicating, he then passes information back and forth between the two. For example,
when User 1 sends data to User 2, the information is actually sent to the hacker first, who
then forwards the information to User 2.

![](Pasted%20image%2020240209165353.png)
#### Race Condiction

Race Condition es una **vulnerabilidad que ocurre cuando un sistema** que maneja tareas en una secuencia específica **es forzado a realizar dos o más operaciones simultáneamente**. 

Esto permite que los atacantes tomen ventaja del intervalo de tiempo que se da entre el inicio de un servicio y el momento en que un control de seguridad surte efecto. 

Con las Race Condition los atacantes pueden acceder a recursos compartidos como bases de datos, archivos y objetos en código para modificarlos simultáneamente y/o afectar la integridad del recurso.

#### SSL Stripping

existe un ataque al protocolo HTTPS llamado **SSL Stripping**, este ataque consiste en «levantar» el cifrado TLS de la comunicación y que un ciberdelincuente pueda ver todas las comunicaciones en texto plano usando HTTP

#### Replay attack

Un ataque de repetición o «replay attack», es un **ataque en el que un hacker detecta una transmisión de datos y la retrasa o repite de manera fraudulenta**.

#### Watering hole

Un ataque watering hole o **ataque de abrevadero** es un tipo de ataque cibernético, en el que un atacante observa a la víctima de los sitios web o un grupo en particular visita de forma regular e infecta esos sitios con malware. Un ataque watering hole tiene el potencial de infectar a los miembros del grupo de víctimas objetivo

#### Typosquatting
El _**typosquatting**_ es un fenómeno por el cual un usuario acaba en una página web que no es la que estaba buscando por el hecho de teclear mal por error la URL en su navegador.


Endpoint detection and response

Endpoint detection and response refers to **a category of tools used to detect and investigate threats on endpoints**.

#### Invoice scam
The attacker impersonates the vendor and creates a fake invoice that looks identical to a real invoice, and sends it to the target client* T

#### DMARC
DMARC **es un componente fundamental de la estrategia de seguridad de correo electrónico de una organización**, ya que permite a los receptores de correos electrónicos que usan el dominio autenticado, confiar en que los mensajes provienen del propietario del dominio y no de un impostor.

#### MSSP
Los _MSSP_ (_MSSP_: Managed Security Service Provider) sirven para extender y ampliar las capacidades internas y brindar a las organizaciones servicios gestionados
soar, mssp, owa

### Certificate Types

#### Wildcard

Cerificado que s epuede aplicar a m´ltiples urls, dentro del dominio (login.comptia.com, www.comptia.com, mail.comptia.com...)Un certificado Wildcard se emite para un dominio principal y todos sus subdominios.
Si tienes un certificado Wildcard para *.example.com, esto cubre [www.example.com](http://www.example.com/), secure.example.com, blog.example.com, etc.
#### SAN
Un certificado SAN permite asegurar múltiples nombres de dominio o subdominios dentro de un solo certificado.
Puedes asegurar dominios como example.com, [www.example.com](http://www.example.com/), secure.example.com, y otros, todo dentro de un solo certificado SAN.

> Los certificados SAN son comunes en entornos donde se gestionan varios dominios o subdominios, mientras que los certificados Wildcard son eficientes cuando se tienen muchos subdominios bajo un dominio principal.

#### Self-signed
Los certificados auto-firmados son a menudo utilizados en entornos de desarrollo, pruebas o en situaciones donde la seguridad no es crítica y no se necesita la validación de una entidad de confianza externa.

#### Code signing
Code signing es un proceso mediante el cual los desarrolladores firman digitalmente su código para demostrar que proviene de una fuente confiable y no ha sido alterado.
Se aplica comúnmente a archivos ejecutables, scripts y bibliotecas para sistemas operativos como Windows, macOS, Android e iOS.


### Backups
#### Backup Completo (Full Backup):
    
    - **Descripción:**
        - Se realiza una copia de todos los datos seleccionados en el sistema.
    - **Cuándo Usar:**
        - Al inicio de una nueva estrategia de respaldo.
        - Periódicamente para asegurar una copia completa y actualizada de todos los datos.
#### **Backup Incremental:**
    
    - **Descripción:**
        - Solo se respaldan los datos que han cambiado desde el último backup, ya sea completo o incremental.
    - **Cuándo Usar:**
        - Con frecuencia, para respaldar cambios diarios o incluso varias veces al día.
        - Eficiente en términos de almacenamiento, ya que solo se respaldan los cambios desde el último backup.
#### **Backup Diferencial:**
    
    - **Descripción:**
        - Se respaldan todos los datos que han cambiado desde el último backup completo.
    - **Cuándo Usar:**
        - Ideal para respaldar datos diarios.
        - Menos eficiente que los backups incrementales en términos de almacenamiento, pero más rápido al restaurar, ya que solo se necesitan dos conjuntos de backups (el completo y el diferencial más reciente).

**Cómo Combinarlos:**

- **Estrategia Común:**
    
    - **Full + Incremental:**
        
        - Realizar un backup completo al inicio de la semana.
        - Realizar backups incrementales diarios el resto de la semana.
        - Al inicio de la siguiente semana, realizar otro backup completo.
        - Ventajas: Eficiencia en términos de almacenamiento y restauración rápida.
    - **Full + Diferencial:**
        
        - Realizar un backup completo al inicio de la semana.
        - Realizar backups diferenciales diarios el resto de la semana.
        - Ventajas: Restauración rápida utilizando el último backup completo y el último diferencial.
- **Ciclo Completo:**
    
    - **Full + Incremental + Diferencial:**
        - Combinar backups completos, incrementales y diferenciales en una estrategia cíclica.
        - Ejemplo: Full al inicio de la semana, incrementales diarios, diferencial a mitad de semana, y así sucesivamente.
        - Ventajas: Equilibra eficiencia de almacenamiento y rapidez de restauración.
### Passwords attacks

#### **Password Spraying (Aspersión de Contraseñas):**

En lugar de intentar adivinar una única contraseña para un usuario específico, se prueban unas pocas contraseñas comunes en múltiples cuentas.

#### **Rainbow Table (Tabla Arcoíris):**

Es un conjunto precalculado de hash y contraseñas que se utiliza para acelerar el proceso de descifrado.
Los atacantes comparan los hash de las contraseñas cifradas en una base de datos con los valores precalculados en la tabla arcoíris.

>*  **Password Spraying:** Enfocado en probar un pequeño conjunto de contraseñas en múltiples cuentas.
>* **Rainbow Table:** Se basa en comparar hashes precalculados con los de una base de datos.
>* * **Credential Harvesting:** Se centra en la obtención de credenciales mediante engaños, por ejemplo, a través de phishing.
>* **Brute Force:** Prueba todas las combinaciones posibles.


#### **Unified Threat Management (Gestión Unificada de Amenazas):**

- En el ámbito de la seguridad informática, UTM se refiere a "Unified Threat Management" o Gestión Unificada de Amenazas. Es una solución integral que integra diversas funciones de seguridad en una única plataforma. Estas funciones pueden incluir firewall, antivirus, filtrado de contenido, prevención de intrusiones, control de aplicaciones y otras medidas para proteger las redes de las amenazas cibernéticas.
#### **Round Robin:**

- **Definición:** La estrategia Round Robin distribuye equitativamente las solicitudes de los clientes entre varios servidores en un ciclo secuencial.
#### **Active-Passive:**

- **Definición:** En una configuración Active-Passive, se tiene un servidor principal (activo) y uno o más servidores secundarios (pasivos) que están en espera en caso de que el servidor principal falle.

####  Staging
Enviroment in wich patches will be deployed prior to being put in operational status.

**■ Environment** You should create different environments for different stages of your
deployment. The following outlines the four environments you should have:
* **■ Development** The development system or systems are used to develop or
create the design of the solution.
* **■ Test** Once the design is created, it is then tested on a test system or systems.
* **■ Staging** Once the initial testing of the solution is completed, the solution is
moved to the staging environment where more production-like validation is
performed to ensure that the solution works.
* **■ Production** After staging, you then place the solution into production.

#### EAP-FAST 
authenticates by means of a PAC (Protected Access Credential) which can be managed dynamically by the authentication server. EAP-TLS, EAP-TTLS, PEAP are cert based. The question states the company is moving away from client and server side certificates.
#### Dkim
Se agrega un encabezado DKIM al mensaje que contiene la firma digital y una referencia a la clave pública correspondiente. Este encabezado indica que el mensaje ha sido firmado digitalmente utilizando DKIM.

#### Wids
A Wireless Intrusion Detection System (WIDS) is a network security technology that monitors wireless networks for unauthorized or malicious activity. It works by analyzing the traffic on a wireless network and identifying any suspicious behavior or potential security threats. WIDS can help organizations detect and respond to attacks, such as rogue access points, unauthorized devices, or attempts to exploit vulnerabilities in the wireless network.