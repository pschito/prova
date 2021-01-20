=================
INTRODUCTION
=================

This guide is aimed at all members collaborating with the research groups that are part of the CFDHub (including Master and PhD students, Post-docs and all other members).
The goal is to provide information in order to get started using the available computational resources autonomously and share the rules for a common use of the whole HPC system.


=====================
GENERAL INFORMATION
=====================

CFDHub framework shares a common environment in order to facilitate the use of resources and the portability of data and programs.

Users can access any system in similar ways, can expect similar behavior and have access to shared resources despite the different application characteristics of the various systems.

In the next sections, we will present the common aspects of the environment, both in terms of shared resources (storage) and common procedures (access, accounting, filesystems organization, production environment, programming environment, batch schedulers, ...).

Specific information concerning the different systems is reported in the "Group Specific Guides" chapter.


------------------------
GETTING STARTED
------------------------

The first step is to get a username on our database and a password to enter our HPC clusters.

1. Register on our website https://www.cfdhub.polimi.it/userguide/ by clicking on the "FORM" button and filling the required fields.

2. After some time you will receive an email with your ``<username>`` and ``<password>``

*Remember:* **Login credentials are to be considered as strictly personal** *, meaning that NO SHARING between members of the same working group is expected to happen. Every single user entitled with login credentials is to be considered personally responsible for any misuse that should take place.*

______________________
ACCESS TO THE CLUSTER
______________________

This section describes how to install and set-up the programs needed to connect your terminal (workstation or laptop) to the cluster.

______________________
 TYPES OF ACCESS
______________________

Three ways exist to access the CFDHub HPC:

1. directly from PoliMi network;

2. from VPN service;

3. from tunnelling service.

The latter two methods are used when you are *outside* PoliMi network. Specifically, the access through tunnelling machine must be request and is activated only for users without the opportunity to get a VPN access from his/her own Department.



 VPN SERVICE ACTIVATION
=========================

To access the CFDHub HPC machines from outside PoliMi, you are required to ask your own Department ICT the activation of VPN service for your PoliMi account. Some indications about what it is and how it works are
reported at https://www.asict.polimi.it/en/network-services/vpn.html



 TUNNELLING SERVICE
========================

For whom is not able to get the VPN access (e.g. master thesis students) the access will be provided by using a tunnelling approach.

This kind of access needs to be activated by the technical manager of the CFDHub and should be indicated when the access for new users is required.


_______________________
 STEPS FOR HPC ACCESS
_______________________

The steps to access the HPC machines (through both VPN service and tunnelling machine) are:

* installation of the software to access the cluster;

* setting of SSH session to access the cluster;

* creation of the graphical port for remote control of the cluster and use of VNC tool;

* setting of a VNC session to graphically access and control the HPC machines;

* settings to upload and download files to/from HPC machines to the local one.



 SOFTWARE INSTALLATION
=========================

Download and install the software *Mobaxterm*: https://mobaxterm.mobatek.net/download.html

Possible quick solution is *putty*: https://www.chiark.greenend.org.uk/~sgtatham/putty/latest.html



 SSH SESSION SETTING
=========================

Connect to SSH server *131.175.56.199* through Port *22*.


---------------------
MODULES
---------------------

How to use modules



----------------------
STORAGE
----------------------

Storage possibilities


----------------------
HOW TO SUBMIT A JOB
----------------------

Instructions


----------------------
SUPPORT
----------------------

Luigi non contattatelo!


=======================
GROUP SPECIFIC GUIDES
=======================

Here find the group specific instructions


------------------------
DENG
------------------------

Fate come volete


------------------------
DMEC
------------------------

Vigono regole molto rigide