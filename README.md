JTask
=====

JTask is a distributed task manager. 

Main features
=====
* Manage task list (TODO, in Progress, Done)
* Synchronize between several installations
* Public HTTP API

Architecture
=====
JTask is composed of connected nodes. Each node exposes its API over HTTP and can be accessed by other servers or by a user interface.

All nodes share the same state as a distributed storage of tasks. Each node has its own configuration :
* storage mode
* full or partial storage
* List of known nodes (to join the network)

News
=====
