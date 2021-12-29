===================
HOW TO SUBMIT A JOB
===================

To perform a calculation on CFDHub there are some information that need to be addressed.

- Access to CFDHub (more information in THIS section)
- :ref:`Data Transfer<Data Transfer>` on the cluster (more information in THIS section)
- Software availability needs to be verified and eventually installed (more information in THIS section)
- Follow the workflow of a hpc facility (more information in THIS section)
- Launch your job (more information in THIS section)

-------------------
DATA TRANSFER
-------------------

In order to transfer files from your terminal to the cluster and vice versa, the FTP the software Filezilla can be used. 

___________________
SOFTWARE INSTALLATION 
___________________

Download and install the software Filezilla:  https://filezilla-project.org/download.php?type=client 

___________________
TUNNELLING SETUP 
___________________

1. In MobaxTerm open 'tools' and then 'MobaSSHTunnel (port forwarding)' 

2. Create a local port forwarding (New SSH Tunnel) with the set-up indicated in the image below. Use your username instead of ‘mereu’, ’10.0.0.121’ instead of ’10.0.0.122’ based on your group category5 

3. Open tab ‘Tunnelling’ and run the symbol play in 'MobaSSHTunnel (port forwarding)' 

.. image:: images/MobaTunnelling.png

4. Open Filezilla or session ‘SFTP’ in mobaxterm and insert host 127.0.0.1, your username, your password and port 22 

Once you inserted your user data and accessed to the cluster, you will see in the left side your terminal and in the right side the cluster folders (/home/energia/mereu in the example above).  

To transfer (copy) data just drag files from one side to the other.  
