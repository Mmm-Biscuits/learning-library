# Introduction

## Oracle Database Consolidation ##

Database consolidation involves placing multiple databases onto a single set of computing infrastructure, either on-premise or in
the Oracle Cloud. Database consolidation is similar to but different from server consolidation, which involves consolidating
multiple physical servers into a single physical server running Virtual Machines. The primary purpose of database consolidation
is to reduce the cost of database infrastructure by taking advantage of more powerful servers that have come onto the market that
include dozens of processor cores in a single server. 

***TO AUTHOR: Maybe a Video or something here... optional***

Estimated time: ***TO AUTHOR: x EDIT THIS*** Hours

### About Database Consolidation ###

Databases consolidation may involve any of the following configurations:
- Multiple Databases on a Single Physical Server
- Multiple Databases on a Single Virtual Machine
- Multiple Databases on a Cluster of Physical Servers
- Multiple Databases on a Cluster of Virtual Machines

Database consolidation allows more databases to run on fewer servers, which reduces physical infrastructure requirements and operational
costs. Each physical server represents an Information Technology asset or “Configuration Item” (CI) that must be placed into a
data center rack, connected, secured, and maintained. Each Virtual Machine represents another Configuration Item (CI) that also
must be deployed, connected (virtually), secured, and maintained. Database Consolidation also applies in Cloud environments
such as the Oracle Database Cloud Service and Oracle Exadata Cloud Service.

Oracle databases can also be consolidated into a cluster of physical servers or virtual machines. Oracle Database clustering
capabilities include active/passive clustering, as well as active/active clustering using Oracle Real Application Clusters. Clustering
is used to increase availability of Oracle databases, enable rolling patching, and to provide for scalability across multiple physical
servers or virtual machines.

Oracle databases can also be further consolidated into what are known as Container Databases using the Oracle Multitenant
option that was first introduced in Oracle Database 12c. The Multitenant option allows multiple databases to be managed under
a single Container Database, with a single backup, single disaster recovery configuration, and single clustering configuration.


### Objectives

In this lab, you will:

* Use MV2ABD to consolidate databases on ADB
***TO AUTHOR: What about the ones below, in progress/complete/delete? I've copied the relevant files to the broken paths in your manifest.json, but they don't seem to be suited for the workshop***
* Use Goldengate to Consolidate databases on ADB / DBCS / EXADATA
* Use Data Pump to Consolidate databases on ADB / DBCS / EXADATA


## Consolidation of Database

### **MV2ADB**

You want to move your data from on-premises to an autonomous database to maximum your database uptime, performance, and security, but you're concerned about how to safely and efficiently transfer the data.

The quickest method of data loading is to use Oracle Data Pump to upload the source files from on-premises to a cloud-based object store before loading the data into your autonomous database. One option is to use the Move to Autonomous Database (MV2ADB) tool to perform the entire data load process with a single click.

***TO AUTHOR: What about the ones below, in progress/complete/delete?***

### **Goldengate**
Work in Progress..

### **Data Pump**
Work in Progress..


## Acknowledgements

- **Authors/Contributors** - NA Cloud Custom Apps and DB Engineering team
- **Last Updated By/Date** - Didi Han, Database Product Management, March 2021