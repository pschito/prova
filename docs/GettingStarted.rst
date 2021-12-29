=================
GETTING STARTED
=================

The first step is to get a username on our database and a password to enter our HPC clusters. 

Please contact the CFDHub contact person of your research group to register to CFDHub. The contact person will give you the instructions to get a CFDHub access.

+------------------------------+-----------------------------+
| CFDHub User Group            | Contact Person              |
+==============================+=============================+
| energia                      | boh                         |
+------------------------------+-----------------------------+
| energia 2                    | boh                         |
+------------------------------+-----------------------------+
| energia 3                    | boh                         |
+------------------------------+-----------------------------+
| chimica                      | boh                         |
+------------------------------+-----------------------------+
|                              | Massimo Fossati             |
| meccanica                    +-----------------------------+
|                              | Paolo Schito                |
+------------------------------+-----------------------------+

As soon as you receive your ``<username>`` and ``<password>`` you will be able to access the cluster.

*Remember:* **Login credentials are to be considered as strictly personal** *, meaning that NO SHARING between members of the same working group is expected to happen. Every single user entitled with login credentials is to be considered personally responsible for any misuse that should take place.* 

=================
ACCESS TO THE CLUSTER
=================

This section describes how to install and set-up the programs needed to connect your terminal (workstation or laptop) to the cluster. 

-----------------
REQUIREMENTS 
-----------------

Three ways exist to access the CFDHub HPC: 

- directly from PoliMi network; 
- from VPN service; 
- from tunnelling service. 

The latter two methods are used when you are *outside* PoliMi network. Specifically, the access through tunnelling machine must be request and is activated only for users without the opportunity to get a VPN access from his/her own Department. 

-----------------
VPN SERVICE ACTIVATION 
-----------------

To access the CFDHub HPC machines from outside PoliMi, you are required to ask your own Department IT staff the activation of VPN service for your PoliMi account. Some indications about what it is and how it works are reported at https://www.asict.polimi.it/en/network-services/vpn.html 

-----------------
TUNNELLING SERVICE 
-----------------

For whom is not able to get the VPN access (e.g. master thesis students) the access will be provided by using a tunnelling approach. 

This kind of access needs to be activated by the technical manager of the CFDHub and should be indicated when the access for new users is required. 

-----------------
STEPS FOR HPC ACCESS 
-----------------

The steps to access the HPC machines (through both VPN service and tunnelling machine) are: 

- installation of the software to access the cluster; 

- setting of SSH session to access the cluster; 

- creation of the graphical port for remote control of the cluster and use of VNC tool; 

- setting of a VNC session to graphically access and control the HPC machines; 

- settings to upload and download files to/from HPC machines to the local one. 

-----------------
ACCESS SOFTWARE INSTALLATION 
-----------------

Download and install the software *Mobaxterm*: https://mobaxterm.mobatek.net/download.html 

Possible quick solution is *putty*: https://www.chiark.greenend.org.uk/~sgtatham/putty/latest.html 

-----------------
SSH SESSION SETTING 
-----------------

Connect to SSH server *131.175.56.199* through Port *22*. 
