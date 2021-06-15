# SQL and NoSQl


Designing Distributed applications: Points to note

Distributed system stores data on more than one node
# CAP Theorem
stands for Consistency, Availability and Partition Tolerance.
It was proposed in 2000 by Brewer

Consistency:
Consistency means that all clients see the same data at the same time, no matter which node they connect to. For this to happen, whenever data is written to one node, it must be instantly forwarded or replicated to all the other nodes in the system before the write is deemed ‘successful.’

Availability:
Availability means that that any client making a request for data gets a response, even if one or more nodes are down. Another way to state this—all working nodes in the distributed system return a valid response for any request, without exception.

Partition tolerance:
A partition is a communications break within a distributed system—a lost or temporarily delayed connection between two nodes. Partition tolerance means that the cluster must continue to work despite any number of communication breakdowns between nodes in the system.



# References
* https://www.ibm.com/cloud/learn/cap-theorem
