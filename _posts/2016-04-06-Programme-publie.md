---
title: "Le programme est en ligne"
layout: "post"
permalink: /programme/
published: true 
ref: program
lang: fr 
---

# Programme du Thème Sécurité RMLL 2016

---

<center>
<h4><i>"Car les Licornes ne sont pas les seules à mériter Sécurité et Logiciels Libres"</i></h4>
</center><br/>
Le programme du Thème Sécurité des RMLL 2016 est désormais en ligne. Nous tenons à **remercier tous les conférenciers ayant soumis une proposition de conférence**, acceptée ou non, pour la confiance mise dans cet événement. Nous allons faire le maximum pour la mériter.  

**Prochaine étape:** pendant le mois de mai, nous mettrons en ligne l'interface de réservation pour réserver une place (La salle chez Mozilla dispose de 100 places maximum). A bientôt !

**Langue :** les conférences sont données en anglais.  

Ce fait a été dicté par deux choix que nous avons faits.   

D'une part, c'est notre volonté de vous proposer la venue de conférenciers non francophones, spécialistes de leur sujet et apportant leur expertise. Cette venue permet aussi la confrontation d'expériences et de points de vue différents.   

Et d'autre part, nous voulions fournir en retour à ces conférenciers une expérience la plus inclusive possible en leur permettant de suivre au mieux la conférence.   

C'est un choix, c'est le notre et nous l'assumons :)

## _Lundi 4 Juillet 2016_

* 14:00-14:40 : [**KEYNOTE: Connecting Communities (with paper)**](#connectingcommunities)  
  by **Ange Albertini** (Corkami/PoC||GTFO)  
* 14:40-15:20 : [**USB armory**: the open source secure flash-drive-sized computer](#usb-armory)  
  by **Andrea Barisani** (Inverse Path)  
* 15:20-16:00 : [**Verified boot and free software**: reconciling freedom and security](#verified-boot)  
  by **Paul Kocialkowski** (Replicant project leader)  
  --------- pause ---------
* 16:20-17:00 : [**Qubes OS**: Improving client systems security with Qubes OS](#qubes)  
  by **Marek Marczykowski-Górecki** (Qubes OS lead developer)    
* 17:00-17:20 : [**Binmap**: scanning file systems with Binmap](#binmap)  
  by **Serge Guelton** (Binmap developer)  

## _Mardi 5 Juillet 2016_

* 09:20-10:00 : [**DNSSEC**](#dnssec)  
  by **Julien Pivotto** (devops & floss enthusiast)   
* 10:00-10:40 : [**Suricata**: mixing IPS/IDS mode](#suricata)  
  by **Giuseppe Longo** (Suricata developer)   
  --------- pause ---------
* 11:00-11:40 : [**BINSEC**: binary-level semantic analysis to the rescue](#binsec)  
  by **Sébastien Bardin** (BINSEC developer)    
* 11:40-12:00 : [**Manalyze**, a static analyzer for PE files](#manalyze)  
  by **Ivan Kwiatkowski** (Manalyze developer)    
  --------- Mid day pause --------
* 14:00-14:40 : [**Let's Encrypt**: the road to encrypting all the things](#letsencrypt)  
  by **J.C. Jones** (Mozilla Firefox Security, Let's Encrypt architect)    
* 14:40-15:20 : [**Continuous Security** in a DevOps world](#ci)  
  by **Julien Vehent** (Mozilla Security)    
  --------- pause --------- 
* 15:20-16:20 : [The wonderful story of **web authentication and Single-Sign On**](#websso)  
  by **Clément Oudot** (LemonLDAP::NG project leader)  
* 16:20-17:00 : [**Ring**: a secure, distributed communication platform](#ring)  
  by **Adrien Béraud** (OpenDHT maintainer, Ring developer)    
* 17:00-18:00 : **Rump session :)**

## _Mercredi 6 Juillet 2016_

* 09:20-10:00 : [**Git**: Speaking about **securing code**, let start with VCS and Git especially](#git)  
  by **Anne Nicolas** (Git trainer and co founder of Hupstream)    
* 10:00-10:40 : [**Bandit**: Python application security auditing with Bandit](#python-bandit)  
  by **Mickael Scherer** (Red Hat)   
  --------- pause ---------
* 11:00-11:40 : [Hands-on **security for DIY projects**](#diy)  
  by **Antoine Cervoise** (IT Security auditor)   
* 11:40-12:20 : [Building A Poor man’s Fir3Ey3 **Mail Scanner**](#poormanmailscanner)  
  by **Xavier Mertens** (rootshell.be)      
  --------- Mid day pause ---------
* 14:00-14:40 : [**MISP**: Using and abusing MISP to track campaigns](#misp)  
  by **Marion Marschalek** (Principal Malware Researcher at G DATA)  
  and **Raphaël Vinot** (MISP/CIRCL)   
* 14:40-15:20 : [Complex **malware & forensics** investigation](#fastir)  
  by **Paul Rascagnères** (Sekoia CERT)  
  and **Sébastien Larinier** (Sekoia CERT)    
  --------- pause ---------
* 15:40-16:20 : [**MIG**: Investigate 1,000 endpoints in 10s](#mig)  
  by **Julien Vehent** (Mozilla Security)  
* 16:20-17:00 : [**MOWR**: a virustotal-like service for web malwares](#mowr)    
  by **Julien Reveret** (MOWR developer)   
  and **Antide Petit** (MOWR developer)   

## Talks List

<a name="python-bandit"></a>
<br>
<h3><u>Python application security auditing with bandit</u></h3> 

> While more and more code is written and connected on the internet,
security have never been so important for software. However, security is
often relegated as a 2nd thought and solution to scale it had to be
found by the industry theses days. A proven strategy is to use automatic static code analysis, a technique
applied by tools such as Coverty or Clang, and mostly used for C code.  
> But not all softwares are written in C, so this talk will present
bandit, a tool to detect dangerous python code, and will explain the
different types of flaws developers have to keep in mind when writing
code, and why static code analysis is not a silver bullet, but just one
of the numerous way we can improve security.  

#### _<a name="mscherer"></a>Mickael Scherer_
![coucou]({{ site.url }}/img/rmll.png)

> Michael Scherer works on the Open Source and Standards team at Red hat,
focusing on infrastructure issues. He lives in Paris, and he often speaks
at events and gives tutorials to help open source communities.

<a name="verified-boot"></a>
<br>
<h3><u>Verified boot and free software: reconciling freedom and
security</u></h3>

> A growing number of modern computers, whether they're traditional x86
desktops and laptops or embedded devices ship with some form of verified
boot mechanism. In practice, it often means that only bootup software
allowed by the manufacturer can run on those computers, causing great
harm to freedom, but also to security. Using asymmetrical cryptographic
algorithms for signing these binaries with a private key kept secret by
the manufacturer and a public key often stored in read-only memory, it
becomes impossible for end users to build, install and run free bootup
software on their devices.  
> However, there are a few examples of devices on which verified boot is
implemented in a way that allows end users to stay in control of their
devices. Namely, Chrome/Chromium OS (CrOS) devices such as Chromebooks
implement reliable verified boot in a way that doesn't conflict with
software freedom, on purpose. Taking things up a notch, verified boot is
implemented with free software, both at the bootup software and embedded
controller firmware levels.    

#### _<a name="pkocialkowski"></a>Paul Kocialkowski_
![pk]({{ site.url }}/img/pk.png)

> Paul Kocialkowski started using free software in 2008 and soon gained
interest in software freedom, with a particular emphasis on running
fully free software. After breaking his  Openmoko FreeRunner, he took at
shot at Replicant, the fully free version of Android. He soon became
involved in active development and has been the lead developer of the
project since 2012.  
> Driven by a growing interest in embedded devices, he
took charge of the single board computers and plug computers freedom
comparisons on the Free Software Foundation's website. Recently, he's
been working on freeing mobile and embedded devices at the lower levels,
contributing to the U-Boot, Flashrom, Coreboot, Libreboot and Linux
projects.  

<a name="usb-armory"></a>
<br>
<h3><u>USB armory: the open source secure flash-drive-sized computer</u></h3> 

> The availability of modern System on a Chip (SoC) parts, having low power consumption and high integration of most computer components in a single chip, empowers the open source community in creating all kind of embedded systems. The USB armory from Inverse Path is an open source hardware design, implementing a flash drive sized computer for security applications.   
> The presentation explores the lessons learned in making a small form factor, high specifications, embedded device with solely open source tools, its architecture and security features such as secure boot and ARM TrustZone implementation.   
> Leveraging on the current maturity of the project, the defensive and offensive uses of the USB armory are also fully explored, covering topics such as the INTERLOCK application, its Genode OS support and its role and usage in identifying new vulnerabilities affecting widely deployed USB stacks.  

#### <a name="abarisani"></a>Andrea Barisani
![ab]({{ site.url }}/img/aba.png)

> Andrea Barisani is an internationally recognized security researcher and founder of Inverse Path information security consultancy firm. Since owning his first Commodore-64 he has never stopped studying new technologies, developing unconventional attack vectors and exploring what makes things tick...and break. 
> His experiences focus on large-scale infrastructure administration and defense, forensic analysis, penetration testing and code auditing with particular focus on safety critical environments, with more than 14 years of professional experience in security consulting. 
> Being an active member of the international Open Source and security community he contributed to several projects, books and open standards. He is the founder of the oCERT effort, the Open Source Computer Security Incident Response Team. 
> He is a well known international speaker, having presented at BlackHat, CanSecWest, Chaos Communication Congress, DEFCON, Hack In The Box, among many other conferences, speaking about innovative research on automotive hacking, side-channel attacks, payment systems, embedded systems security and many other topics.  


<a name="mig"></a>
<br>
<h3><u>Investigate 1,000 endpoints in 10s with MIG</u></h3>
> Mozilla operates thousands of servers that support Firefox and Firefox
OS, and provide functionalities to more than 300 millions users. Systems
are often heterogenous, are catered to the needs of particular services,
and are hosted in various locations around the world.
A few years ago, the number of systems Mozilla operates outgrew the
capabilities of existing forensics and endpoints security tools. Being
able to inspect an entire infrastructure in real-time is the the dream
of any security investigator, and we simply could not achieve that with
our tooling. The MIG project was started to provide better visibility
across the organization, and to remodel the traditional approach to
forensics (manually retrieving and analyzing data from systems) that had
become impractical in Mozilla’s heterogenous environments.  
> MIG is a distributed platform composed of agents deployed across
Mozilla’s servers. The agents provide investigators with remote access
to the file system, network and memory of endpoints. MIG is massively
parallelized. It can run targeted searches on thousands of endpoints in
as short as ten seconds, while allowing for larger scans that take hours
to complete. The architecture of MIG is cross-platform and modular.
Entirely written in Go, agents can run on Windows, MacOS and Linux.
Capabilities can be added via modules that are compiled and shipped with
the agents. During the talk, we will discuss how the use of Go
simplifies the architecture of MIG, and helps build security tools with
minimal cpu and memory footprint.  
> MIG belongs to the growing field of distributed digital forensics, akin
to Google’s Rapid Response, Akamai’s Query and Facebook’s osquery. MIG
takes an approach to investigation that does not rely on retrieving and
storing large amounts of data from endpoints, but instead focuses on
interrogating endpoints locally via distributed agents. By limiting the
amount of data retrieving from endpoints, we reduce MIG’s operating
cost, have a stronger respect for data confidentiality, and ensure that
a platform breach would not expose terabytes of confidential forensics
data to the world. Security is a first-class citizen in MIG. We
guarantee access control by requiring investigators to sign all actions
with their PGP keys. Agents verify signatures prior to running actions
locally. MIG is built to withstand a takeover of its platform without
compromising the security of Mozilla’s servers.  
> This talk will introduce MIG, the problems it solves, its design goals,
capabilities, and security model. We will present its use on thousands
of servers at Mozilla. The audience will learn how indicators of
compromise can be searched across thousands of systems within seconds.
During the talk, attendees will be given elements to install and operate
MIG in their own environments. If permitted, the talk will include a
live demo on Mozilla’s infrastructure.  
> [Website](http://mig.mozilla.org/) | [Github](https://github.com/mozilla/mig/)

#### <a name="jvehent"></a>Julien Vehent
![jv]({{ site.url }}/img/jv.png)

> Julien manages the CloudSec team and is responsible for the security of
Firefox's backend services (Firefox accounts, Sync, addons.mozilla.org,
Push, Hello, ...). Mozilla CloudSec consults with developers and operations
teams on risks and security, and builds security tools for the infrastructure.
Julien is the author of the Mozilla Server Side TLS guidelines, Cipherscan,
Mozilla InvestiGator (MIG), SOPS and many smaller tools to help DevOps integrate
security in the organization.

<a name="ci"></a>
<br>
<h3><u>Continuous Security in a DevOps world</u></h3>

> The Information Security world has yet to embrace the DevOps culture.
The concepts of fast paced, always moving, continuously delivered
software and services still clash with the cautious methods of
information security. The disconnect is accentuated by difficulties
security teams encounter adapting legacy policies to devops and the
cloud.  
> Security policies typically focus on hardening, monitoring and updating
systems and services, which must be done at each level of the stack. The
continuous delivery techniques advocated by DevOps often rely on
third-party infrastructure that do not grant infrastructure-level access
to customers, which forces security teams to rethink controls.  
>  
>    1. The lack of physical, and sometimes virtual, access requires
       forensics and incident response to be approached differently.  
>    2. Scanning for vulnerabilities inside containers is not possible on
       production systems.   
>    3. Logs correlation may become difficult when systems have no names and
       live for only a few hours.  
>    4. And, above all, the approach to network security monitoring (IDS/IPS,
       sniffers, etc…), which security teams spent years perfecting, is useless
       in cloud environments that don’t grant access to network equipments.  
>  
> Mozilla has been operating full devops for several years now. As a
security lead in the Cloud Services organization, integrating security
into devops is a major part of my job, and I want to describe our
approach in this presentation. The talk is focused on three main parts:  
>  
>    1. Implementing and testing security controls: in which we talk about
       Test Driven Security in the CI/CD pipeline.
>    2. Monitoring and responding to attacks: an overview of techniques that
       help increase the security coverage of cloud-based, immutable and
       continously delivered infrastructures.
>    3. Maturing DevOps Security: a discussion on bringing security into the
       culture of the organization
>  
> We will discuss the challenges, both cultural and technical, in adopting
a DevOps culture in security. The audience will be given pointers to
build and test controls into the continuous integration and continuous
delivery pipelines.  

<a name="connectingcommunities"></a>
<br>
<h3><u>KEYNOTE: Connecting Communities (with paper)</u></h3>

> Abstract: %PDF-1.5 ustar PK\3\4 \xFF\xD8

#### <a name="aalbertini"></a>Ange Albertini
![aa]({{ site.url }}/img/aa.png)

> Reverse engineer - author of Corkami

<a name="websso"></a>
<br>
<h3><u>The wonderful story of Web Authentication and Single-Sign On</u></h3>

> Single Sign On is part of the Web history: to secure access to content, authentication has been implemented, from the standard HTTP Basic to very complex protocols like SAML and OpenID Connect. Trough this presentation, we will try to see why all authentication standards seems to work the same way, and what are their differences. 

#### <a name="coudot"></a>Clément Oudot
![aa]({{ site.url }}/img/co.png)

> Clément Oudot works for Savoir-faire Linux, a worldwide FOSS company. He is the leader of LemonLDAP::NG, a free WebSSO and Access Management software. He also works for other LDAP-related projects (OpenLDAP, LDAP Tool Box, LDAP Synchronization Connector).

<a name="diy"></a>
<br>
<h3><u>Hands-on security for DIY projects</u></h3>

> Internet of Things (IoT) is the new trend in IT talks, meetings and magazines. Security communities follow the hype: most of the infosec conferences have already discussed how to break into a doorbell, a car, a toilet... As IoT diffused in the last years, so do DIY projects thanks to Arduino project, Raspberry Pi project and low cost 3D printers. You can easily find books about DIY in a bookstore, magazines are dedicated to this subject, and the web is full of blog about it. We know we must be careful of IoT and all its vulnerabilities... But we should also consider security while making a DIY project.  
> From the Raspberry Pi used as a Media Center in the living room to the DIY Arduino Meteo Station in the garden, all these projects may come with their vulnerabilities. This talk will deal with bad and good examples from magazines and blogs showing how it can be easy (sometimes easier than with an IoT device) to introduce yourself into someone else network.  
> The aim of this presentation is not to find vulnerabilites in Raspian Packages and deduct that DIY is a major source of threats, but to share some thoughts on building safer DIY projects.  

#### <a name="acervoise"></a>Antoine Cervoise
![aa]({{ site.url }}/img/ac.png)

> Antoine is an IT security engineer, skilled in infosec incident handling, pentest and audit. He enjoys I.T., electronics and D.I.Y. beers by night... and he’s fond of cigars!

<a name="suricata"></a>
<br>
<h3><u>Suricata: mixing IPS/IDS mode </u></h3>

> Suricata is an open source network intrusion detection and prevention system.It analyzes the traffic content against a set of signatures
to discover known attacks and also journalize protocol information.  
> With the support of the Netfilter features, it was possible to build an IPS or IDS system, but now a new dynamic IDPS system is available. The purpose of this talk is to introduce the "mixed mode", which permits to combine IPS and IDS. For example, this new approach allows a single Suricata to operate as IDS for traffic that is too critical to send through IPS and act as IPS for the rest of the it.  
> The following point will be covered:
- Motivation about mixing IPS and IDS
- A brief introduction about Netfilter
- How Suricata work as IPS/IDS with Netfilter
- Advanced setup of Suricata and Netfilter in mixed mode 

#### <a name="glongo"></a>Giuseppe Longo
![aa]({{ site.url }}/img/gl.png)

> Giuseppe is a software developer at Stamus Networks focused on the development of open source software for network security, like firewall and intrusion detection system. He started his contribution in the open source world with the Netfilter organization, which he is still a member of, then he joined in the OISF community. He previously worked as independent contractor for Emerging Threats involved in Suricata development. 

<a name="dnssec"></a>
<br>
<h3><u>DNSSEC </u></h3>

> This talk will explain the basics of DNSSec and how you can use them to secure your infrastructure. DNSsec is quite an old technology but it is not adopted everywhere yet. Nowadays however it is quite easy to set that in place.  
> It will also describe DANE and how you can use it to secure your TLS/SSH communication by storing the SSH keys of your servers inside your DNS zones, even in a frequently changing environment.  
> Tools used in this talk will be Bind, the Foreman and Puppet.  

#### <a name="jpivotto"></a>Julien Pivotto
![aa]({{ site.url }}/img/jp.png)

> Julien Pivotto is a young Open-Source consultant at Inuits where he is helping organisations with the deployment of long-term solutions based on Open-Source infrastructure.  
> He is a strong believer in the devops movement and has technical focus towards infrastructure automation, continuous integration, monitoring and high availability  

<a name="poormanmailscanner"></a>
<br>
<h3><u>Building A Poor man’s Fir3Ey3 Mail Scanner</u></h3>
> Today, web surfing and email remain the common vectors of infection. Every day spam campaigns are flooding our mailboxes with tons of malicious attachments trying to lure our beloved users. There exist solutions to automatically analyze emails content like the well-known Fir3Ey3 EX appliance. However, these toys are very expensive.  
> In my talk, I’ll briefly review different methods used by attackers to deliver and execute payloads on the victim computer. In a second phase, I’ll explain how to build a light platform to process malicious attachments on the fly and analyse them using VirusTotal and OLE analysis tools (the process being based on open source source solutions and a self-developed tool).  
> Besides blocking malicious content, the goal is this platform is also to collect IOC’s  to share to improve detection with 3rd party tools.

#### <a name="xmertens"></a>Xavier Mertens
![aa]({{ site.url }}/img/xm.png)

> Xavier Mertens is a freelance security consultant based in Belgium. His job focuses on protection his customer’s assets by applying “offensive” (pentesting) as well as “defensive” security (incident handling, log management, SIEM, security visualisation). Xavier is also a [security blogger](https://blog.rootshell.be), a [ISC SANS handler](https://isc.sans.org) and co-organizer of the [BruCON](http://www.brucon.org) security conference.

<a name="letsencrypt"></a>
<br>
<h3><u>Let’s Encrypt: The Road To Encrypting All The Things</u></h3>
> In 16 months, Let’s Encrypt went from an idea to the 3rd largest Certificate Authority on the public web.  
> J.C. Jones, one of the engineers who worked on Let’s Encrypt, will guide you through many of the challenges, decisions, and trade-offs that occurred along the way. 

#### <a name="jcjones"></a>J.C. Jones
![aa]({{ site.url }}/img/jcj.png)

> J.C. is a security engineer at Mozilla, and spent about a year and a half as a principal on Let's Encrypt. Prior to Mozilla he co-founded a PKI-based startup in America’s Desert Southwest, where he lives. You can reach him on Twitter as [@JamesPugJones](https://twitter.com/JamesPugJones).

<a name="ring"></a>
<br>
<h3><u>Ring: a secure, distributed communication platform</u></h3>
> In this talk, we plan to present and discuss the security design behind Ring, a fully distributed communication platform that protects user security and privacy.

#### <a name="aberaud"></a>Adrien Béraud
![aa]({{ site.url }}/img/ab.png)

> Passionate about distributed networks, Adrien Béraud (OpenDHT and Ring Developer at Savoir-faire Linux) maintains the distributed hash table OpenDHT used for Ring. For Adrien, Ring is more than a communication tool. It is based on the community. Ring belongs to it and strengthens through it.

<a name="git"></a>
<br>
<h3><u>Speaking about securing code, let start with VCS and Git especially</u></h3>
> Use of a VCS is one of the most important best practise regarding development. Still it's also one of the biggest weakness. Based on more than 30 git training sessions and consulting in
companies, we will try to sum up all good (and worst) practices.  
> While technical infrastructure is important, social engineering and training is also essential to get people ready to use git properly and then securing code. Building a git server is also an organizational project especially when code is shared widely and developped by companies, partners, developers, clients.

###<a name="anicolas"></a>Anne Nicolas
![aa]({{ site.url }}/img/an.png)

> After 8 years working for Mandriva as support engineer, release manager, she has founded with some other ex Mandriva guys her own company dedicated to free software integration in companies and administrations. She works on software packaging, industrialization of customized Linux distros,  git training and consulting.   
> Anne organizes every year since now 4 years Kernel Recipes, 3 days talks about the Linux kernel, in Paris. She is also part of the Mageia distribution board.

<a name="misp"></a>
<br>
<h3><u>Using and abusing MISP to track campaigns</u></h3>
> The security landscape evolves very fast and every day comes a new report about a brand new attacker, scarier than the day before and we have short memory so we tend to forget about what happened a few month ago.  
> As of now, MISP is mostly a repository for incident responders where you can easily add new events and correlate them efficiently but not much work has been put into grouping the events together following  different indicators (type of target, technical indicators in the binaries, ...) after the fact.  
> We already presented our initial findings at [Troopers a few month ago](https://www.troopers.de/events/troopers16/599_the_kings_in_your_castle_-_all_the_lame_threats_that_own_you_but_will_never_make_you_famous/). We will investigate further on that topic and present the tools we developed in order to make the life of the analyst easier.  

#### <a name="mmarschalek"></a>Marion Marschalek
![aa]({{ site.url }}/img/rmll.png)

> Marion Marschalek is a Principal Malware Researcher at G DATA Advanced Analytics, focusing on the analysis of emerging threats and exploring novel methods of threat detection. Marion started her career within the anti-virus industry and also worked on advanced threat protection systems where she built a thorough understanding of how threats and protection systems work and how both occasionally fail. Next to that Marion teaches malware analysis at University of Applied Sciences St. Pölten and frequently contributes to articles and papers. She has spoken at international conferences around the globe, among others Blackhat, RSA, SyScan, hack.lu and Troopers. Marion came off as winner of the Female Reverse Engineering Challenge 2013, organized by RE professional Halvar Flake. She practices martial arts and has a vivid passion to take things apart. 

#### <a name="rvinot"></a>Raphaël Vinot
![aa]({{ site.url }}/img/rmll.png)

> Raphaël is a CERT operator at CIRCL, the CERT for the private sector, communes and non-governmental entities in Luxembourg. His main activity is developing or participating to the development of tools (Github [personnal account](https://github.com/Rafiot), [work account](https://github.com/CIRCL/), [MISP account](https://github.com/MISP), [write a MISP module](https://github.com/viper-framework/viper)) to improve and ease the day-to-day incident response capabilities of the CSIRT he works for but also for other teams doing similar activities. Another big part of his activities is to administrate the biggest MISP instance in Europe ([information on how to get access to the platform](https://www.circl.lu/services/misp-malware-information-sharing-platform/)) with >250 companies, 600 users and more than 300.000 attributes. This is the source used in this research project.

<a name="manalyze"></a>
<br>
<h3><u>Manalyze, a static analyzer for PE files</u></h3>
> During this talk, I would like to present a free open-source (GPLv3) tool, written in C++, that I've been working on for two years on my spare time. It was designed as a helper program which speeds-up the job of a malware analyst by automating repetitive tasks. It can also be used for malware triage, in order to determine which files are worth analyzing manually.
It has the following architecture :  
>  
>    * A robust PE parser which was designed with malicious and/or malformed PEs in mind. It is currently being fuzzed by AFL (input files used), with no crashes so far.  
>    * A customized version of Yara which can re-use the project's PE parser, accompanied with a set of handmade rules to detect suspicious files.  
>    * Plugins which use and correlate the information collected by the PE parser to infer the program's behaviour and characteristics.  
>    * An output system which can print out the generated data as text or JSON.  
>  
> The following plugins are already included in the tool:  
>  
> * ClamAV and PEiD signatures - a Python script has been written to convert ClamAV databases into Yara rules.  
> * Compiler detection  
> * Suspicious strings (i.e. "cmd.exe", "CurrentVersion\Run", ...)  
> * Cryptographic algorithms identification  
> * Packer detection (but no automatic unpacking!)  
> * Alerts for dangerous import combinations  
> * Resource analysis and extraction  
> * Authenticode verification (on Windows only so far) with a twist (if the program pretends to come from a well-known company like Microsoft or Oracle in the manifest but isn't signed, flag it as very suspicious)  
> * Submitting file hashes to VirusTotal  
>  
> The plugin system was intended to be easy to use, and it's (supposed to be) easy for anyone to write their own plugins without having to dive deeply into the project's code. Conversely, the PE parser is intended as a buiding block for other security projects and can be taken out from Manalyze and put into other projects with no hassle. A lot of effort was put into writing the [developer documentation](https://docs.manalyzer.org/en/latest/developer.html) in order to minimize the learning curve for people willing to contribute. 
>   
> A [web portal](https://manalyzer.org/) was also written so people can upload samples and see results without having to compile/run the tool.

#### <a name="ikwiatkowski"></a>Ivan Kwiatkowski
![aa]({{ site.url }}/img/rmll.png)

> Ivan Kwiatkowski ([@JusticeRage](https://twitter.com/JusticeRage)) is a 27 year old security researcher from Paris. Noteworthy hobbies include writing fiction and replying to Nigerian scams.

<a name="qubes"></a>
<br>
<h3><u>Improving client systems security with Qubes OS</u></h3>

> A quick introduction to Qubes OS and why it matters, followed by few specific examples of Qubes OS specific use cases.

#### <a name="mmarczykowski"></a>Marek Marczykowski-Górecki
![aa]({{ site.url }}/img/mm.png)

> Marek is the Qubes OS lead developer, experienced Linux administrator and trainer of Linux administration.

<a name="binmap"></a>
<br>
<h3><u>Scanning File systems with Binmap</u></h3>

> Binmap is an Open Source tool designed to quickly scan a file system, gather various information on the binaries it finds and store them for futher processing by third-party tools.  
>  
> It provides handlers for ELF and PE binary formats and can collect usual executable informations:  
>  
>   * imported / exported symbols  
>   * dynamic library dependencies  
>   * hardening features  
>   * version information (using a fuzzy algorithm)  
>   
> These informations are stored as a graph that can be walked through using a Python API.
>  
> So what?  
> You want to check all the executables that use a given, obsolete library? Walk through its successors!  
> You want to see the consequences of a system upgrade? Take the diff of the graph!  
> You want to check if your system is vulnerable to a given CVE? Rely on the collected version information and cross-check information!  
> You want to audit a system image? Use the chroot mode and quickly find out the interesting binaries!  
>   
> The tool is extendible: one can contribute with its own binary analyzer to support more formats or to improve existing information extraction.

#### <a name="sguelton"></a>Serge Guelton
![aa]({{ site.url }}/img/rmll.png)

> Serge is a pure product of the French Far West: He received his Engineering degree and PhD on Compilation near Brest and since then he has been travelling in the marvelous world of computer science, from HPC to submarine acoustic and now the funny interaction between security and compilation as an R&D engineer for Quarkslab.

<a name="mowr"></a>
<br>
<h3><u>MOWR, A virustotal-like service for web malwares</u></h3>

> We're setting up a web service to analyze suspicious files found on web servers to determine whether they're a potential threat to your server or infrastructure. It's called MOWR (More Obvious Web-malware Repository) and aims at becoming as useful as virustotal is for common viruses. Code will be published under free software licence at the time of the RMLL talk. 

#### <a name="jreveret"></a>Julien Reveret
![aa]({{ site.url }}/img/rmll.png)

> Julien Reveret is a senior security consultant at NBS-System, he already talked about Linux web servers forensic in 2015 at the RMLL security track. His skills are mainly rooting customers' servers and baking cookies.

#### <a name="apetit"></a>Antide Petit
![aa]({{ site.url }}/img/rmll.png)

> Antide Petit works as a IT security intern for NBS-System. He is one the MOWR developer.

<a name="binsec"></a>
<br>
<h3><u>BINSEC: Binary-level semantic analysis to the rescue</u></h3>

> Several major classes of security analysis have to be performed on raw executable files, such as vulnerability analysis of mobile code or commercial off-the-shelf, deobfuscation or malware inspection. These analysis are very challenging, due to the very low-level and intricate nature of binary code, and they are still relatively poorly tooled -- essentially syntactic static analysis (disassembly) which is easy to fool, or dynamic analysis (fuzzing, monitoring) which may miss subtle behaviors. On the other hand, source-level program analysis and formal methods have made tremendous progress in the past decade, and they are now an industrial reality for safety-critical applications.  
> 
> The open-source BINSEC platform humbly tries to fulfill part of this gap, by providing state-of-the-art binary-level semantic analyses. The platform is built around a concise and generic Intermediate Representation, making it easy to support new architectures and add new analyses. The main analyses so far include a dynamic symbolic execution engine enabling to discover new subtle behaviours in an executable file, and a semantic static analysis engine able to reason about all paths of a portion of the code under analysis.
>  
> In this this talk, we will present the platform and highlight the key technologies behind the platform, through a few examples taken from deobfuscation and vulnerability  analysis.  
>  
> The BINSEC project is a joint effort involving CEA, INRIA, LORIA, Université de Grenoble-Alpes and Airbus Group. The project is still in its infancy (first release Spring 2016) and under heavy development. While it is primarily a research tool, we want to make it robust enough so that adventurous hackers can take advantage from it.  

#### <a name="sbardin"></a> Sébastien Bardin
![aa]({{ site.url }}/img/sb.png)

> Sébastien Bardin joined CEA LIST, France, in 2006 as a full-time researcher. Since then, its main research interests are the automatic analysis of executable files -- from a safety point of view at first and now from a security point of view, automatic white-box testing through symbolic execution and low-level constraint solving. He is one of the main designers and developers of the binary-level symbolic execution tool OSMOSE (2008), and the Principal Investigator of the ANR projects BINCOA (2009-2012) and BINSEC (2013-2017) about binary-level program analysis, for safety and security. He is now one of the main designers of the (open-source) BINSEC platform for binary-level code analysis, to be released in Spring 2016. Sébastien Bardin obtained his PhD in 2005 at ENS Cachan, France, under the guidance of Pr. Alain Finkel. His doctoral work was centered on the verification of infinite-state systems by means of model checking, symbolic representations and loop acceleration. He also co-developed the infinite-state model-checker FAST.  

<a name="fastir"></a>
<br>
<h3><u>Complex malware & forensics investigation</u></h3>
> This presentation explains how malware analyst and forensic investigator can work together. The purpose is to select several advanced threats (for example, Uroburos, ComRAT, Babar, Casper…) and to show how a reverser and a forensic investigator can be complementary.  
> The presentation is mainly based on the open source tool FastIR Collector developed by SEKOIA and available on [Github](https://github.com/SekoiaLab/Fastir_Collector). The presentation will present what kinds of artifacts the tools is able to collect and how to identify the infection.  

#### <a name="prascagneres"></a>Paul Rascagnères  
![aa]({{ site.url }}/img/rmll.png)  

> Paul Rascagnères is a malware analyst and researcher for the Sekoia’s CERT. He is specialized in Advanced Persistant Threat (APT) and incident response. He worked on several complex cases such as government linked malware or rootkits analysis. He is a worldwide speaker at several security events.

#### <a name="slarinier"></a>Sébastien Larinier  
![aa]({{ site.url }}/img/rmll.png)  

> Sébastien Larinier currently is Senior Researcher and CTO at the CERT Sekoia located in Paris, member of the honeyproject chapter France and co organizer of botconf. Sébastien focused his work for the last 5 years on botnet hunting, early compromission detection, forensic and incident response. Python addict he supports different opensource projects like FastResponder, OSINT Framework, Malcom.  

