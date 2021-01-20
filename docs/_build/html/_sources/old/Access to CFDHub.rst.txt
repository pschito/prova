=================
ACCESS TO CFDHUB
=================

This section describes how to install and set-up the programs needed to connect your terminal (workstation or laptop) to the cluster.

---------------------
 TYPES OF ACCESS
---------------------

Three ways exist to access the CFDHub HPC:

1. directly from PoliMi network;

2. from VPN service;

3. from tunnelling service.

The latter two methods are used when you are *outside* PoliMi network. Specifically, the access through tunnelling machine must be request and is activated only for users without the opportunity to get a VPN access from his/her own Department.

^^^^^^^^^^^^^^^^^^^^^^^
 VPN SERVICE ACTIVATION
^^^^^^^^^^^^^^^^^^^^^^^

To access the CFDHub HPC machines from outside PoliMi, you are required to ask your own Department ICT the activation of VPN service for your PoliMi account. Some indications about what it is and how it works are
reported at https://www.asict.polimi.it/en/network-services/vpn.html

^^^^^^^^^^^^^^^^^^^^^^^
 TUNNELLING SERVICE
^^^^^^^^^^^^^^^^^^^^^^^

For whom is not able to get the VPN access (e.g. master thesis students) the access will be provided by using a tunnelling approach.

This kind of access needs to be activated by the technical manager of the CFDHub and should be indicated when the access for new users is required.

---------------------
 STEPS FOR HPC ACCESS
---------------------

The steps to access the HPC machines (through both VPN service and tunnelling machine) are:

* installation of the software to access the cluster;

* setting of SSH session to access the cluster;

* creation of the graphical port for remote control of the cluster and use of VNC tool;

* setting of a VNC session to graphically access and control the HPC machines;

* settings to upload and download files to/from HPC machines to the local one.


^^^^^^^^^^^^^^^^^^^^^^^
 SOFTWARE INSTALLATION
^^^^^^^^^^^^^^^^^^^^^^^

Download and install the software *Mobaxterm*: https://mobaxterm.mobatek.net/download.html

Possible quick solution is *putty*: https://www.chiark.greenend.org.uk/~sgtatham/putty/latest.html

^^^^^^^^^^^^^^^^^^^^^^^
 SSH SESSION SETTING
^^^^^^^^^^^^^^^^^^^^^^^

Connect to SSH server *131.175.56.199* through Port *22*.