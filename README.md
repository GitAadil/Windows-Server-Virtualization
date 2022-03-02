# Windows-Server-Virtualization
Requirements
Small Industrial PC spare parts company Called ‘Aadil08’ wants to set up the computing environment for their Finance and Accounting Department with high available services. The design requested will consist of an Application server, Domain Controller and a Storage server. 
The application server primarily focused on running the software and application required for the finance department will be used by Senior 2 accountants in their daily task. End of every week 1 more accountant will be joining them to support the final review done at the end of each week. The server will host two Virtual Machines (aadilVH-1, aadilVH-2) one as a running application server in use and the other as running backup for failover cluster. Both the VMs embedded in one cluster
The Domain controller server here is the main computer that controls our other servers with active directory services. (aadilADC)
The storage server (aadilStorage) is used mainly to store the application servers’ data. It is accessible by 50 Employees in the department for accounting references and repository. Server will consist of two storage disks (mStorage-1, mStorage-2). Both the Main application server and Fail over cluster are connect to the same storage server using it as a shared server.Consists of 3 iSCSI Disks which are shared
The Company’s environment will need the following implementation:
-Application Server 
-Domain Controller
-Storage Server
-Failover cluster with Two Nodes
