---
title: "CAP Theorm"
date: 2022-01-08T17:11:07-06:00
---

## C - Consistency

Data returned is the latest whenever it is requested.

Ways to achieve consistenty 
 Read after Write Consistency
  - A new data is acknowledged to be written only   when the data is written to all the nodes/subset of nodes in the system.


## A - Availability

Data is returned whenever it is requested for.

Ways to acheive availability
- Have multiple replicas of nodes in the system.

## P - Partition Tolerance
 
The system operates even when messages are dropped/delayed by network between nodes

Ways to achieve partition tolerance
- Have an active/standby setup for networks.

CAP Theorm states that any distributed system can have atmost 2 of the 3 desirable properties

