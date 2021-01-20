==================
CFDHUB INFORMATION
==================

---------------------
 WHAT IS THE CLUSTER?
---------------------

The *cluster* is a HPC system located in Milan, Bovisa campus, which is at disposal for intensive computations. It is shared by various research groups of the Politecnico di Milano from various departments such as Bio, Chemical, Energy, Environmental and Mechanical Engineering.
The management responsible is Dr. Riccardo Mereu and the technical responsible is Luigi Urbinati.
    	
--------------------------
 *MASTER* AND ACCESS NODES
--------------------------

The master is the machine that manages all the communications between the cluster resources and the login nodes.
Login nodes (nodevg-0-x) are the nodes used to manage the interaction between users and graphical parts and the computing nodes. When you log into the cluster you actually log into the master and then to the login nodes.

**In order to use the computing resources you will have to log into nodevg-0-1 or nodevg-0-2** to successively connect to the selected computing nodes.

**Never launch a computational run from the master!** Always check to be connected to the selected computing nodes before to launch the run!

*All the processes running on the master or the login nodes will be killed without any advice if affecting the functionality of the whole system.*

--------------------------
 DEFINITIONS
--------------------------

In the following sections we will often refer to some keywords that are user specific, some of them are given below:

* ``<username>`` is your username and you have to substitute it in the command or field;

* ``<password>`` is your password and you have to substitute it in the command or field;

* ``<vncport>`` is the port number of your VNC connection;

* ``<node>`` is the name of the computing node you would like to use.


Vocabulary:

* ``alias`` is a command line shortcut for an expression;

* ``bashrc`` is a file that contain instructions that are executed each time a terminal is opened or each time you log into a machine through ssh.


---------------
 HARDWARE
---------------

It is composed of several homogeneous groups of computing units (also called *nodes*):

    1. **Main group 1**: 16 nodes DELL M620 (blade version) with Intel(R) Xeon(R) CPU E5-2650 V2 @ 2.6GHz processors for a total of 256 cores and 1024 Gb RAM
    [*node-0-1 up to node-0-16*]

    2. **Main group 2**: 2 nodes DELL R720 with Intel(R) Xeon(R) CPU E5-2650 V2 @ 2.6GHz processors and GPU NVIDIA K40 unit for a total of 32 cores, 2 GPUs and 128 Gb RAM
    [*nodevg-0-1 and nodevg-0-2*]
    
    3. **Energy group 1**: 6 nodes DELL R410 with Intel(R) Xeon(R) CPU E5670 @ 2.93GHz processors for a total of 72 cores and 192 Gb RAM
    [*nodo10 up to nodo15*]
    
    4. **Mechanical group 1**: 11 nodes
    	1 node DELL R410 with Intel(R) Xeon(R) CPU E5670 @ 2.93GHz processors for a total of 12 cores and 24 Gb RAM
        [*nodo-m01*]
        
    	2 nodes DELL M630 with Intel(R) Xeon(R) CPU E5-2690 v4 @ 2.60GHz processors for a total of 56 cores and 256 Gb RAM
    	[*node-6-14 and 6-15*]
    	
    	8 nodes ??????? with Intel(R) Xeon(R) CPU E5-2690 v4 @ 2.60GHz processors for a total of 56 cores and 256 Gb RAM
    	[*??????*]