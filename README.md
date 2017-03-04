# Assignment-8.2


1)Explain the core changes made in Hadoop 2.x?
Ans- Hadoop 2.x
	- hadoop decouples the responsibilities into different components.
	-This is done by YARN(Yet Another Resource Manager)
	-By decoupling component’s responsibilities, it supports multiple namespace, Multi-tenancy, Higher Availability and Higher Scalability.
Hadoop 2.x has following benefits-
1) Highly Scalability.
2)Highly Availability.
3)Supports Multiple Programming Models.
4)Supports Multi-Tenancy.
5)Supports Multiple Namespaces.
6)Improved Cluster Utilization.
7)Supports Horizontal Scalability.

2)Explain the difference between MapReduce 1 and MapReduce 2 / Yarn
Ans- 
Hadoop 1.x also called as hadoop 1 where HDFS (Resource management and scheduling) and MapReduce(Programming Framework) hence non batch 
applications cannot be run on hadoop 1. It can support only single name node. So it does no provide system availability and scalability.

MRv2 (aka Hadoop 2) in this version of hadoop the resource management and scheduling tasks are separated from MapReduce which is separated by 
YARN(Yet Another Resource Negotiator).  The resource management and scheduling layer lies beneath the MapReduce layer. 
It also provides high system availability and scalability as we can create redundant NameNodes. 
The new feature of snapshot through which we can take backup of filesystems which helps disaster recovery.

 
