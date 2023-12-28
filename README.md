# Secure Network Architecture

Repository for secure network architecture projects. 

# About

This repository has been divided into directories - each holding documents related to one specific project regarding designing a secure network architecture.
All documents present in this repository have been made as university assessements. As all Collaborators (see section **Collaborators**) are attending Warsaw University of Technology, all documents have been in written in Polish.

# Collaborators

Collaborators for this repository include:

* Miłosz Kutyła ([GitHub](https://github.com/mkutyla)), Warsaw University of Technology
* Jakub Ossowski ([GitHub](https://github.com/bilevcik)), Warsaw University of Technology
* Patryk Jankowicz, Warsaw University of Technology
* Jan Walczak, Warsaw University of Technology

This group is further refered to as WOJK.

# Repository structure

## **1_A-new-web-app**

This directory contains documents related to a project in which WOJK team was supposed to design a secure network architecture for a new web application. It includes introducing assets such as:
* border firewall,
* web application firewall (blocking: data leaks with GET request and brute force; logging: command injection),
* SIEM,
* application server,
* database servers.

Security requirements included:
* performing network separation and segmentation,
* encrypting the traffic where its necessary,
* collecting logs,
* verifying user input.

Archiecture has been implemented and testes in GNS3 network emulator.

## **2_A-new-office**

This directory contains documents related to a project in which WOJK team was supposed to design a secure network architecture for a new office. It includes introducing solutions such as:
* host-to-site VPN,
* site-to-site VPN,
* NIDS & HIDS,
* log collectors,
* DNS Servers,
* jump server,
* vulnerability scanner,
* SIEM.

Although project's documentation has been written in Polish, diagrams are described in English and could still be informational for non-Polish speakers.

