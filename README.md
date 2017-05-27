# devops.test

Description
-----------
Build a simple REST API.
This API code needs to run in a Docker container inside a virtual machine.
You need to provision this virtual machine with Ansible.


API Specification
-----------------
GET /user/{id} - Revtrieves a specific user
POST /user - Creates a new user
DELETE /user/{id} - Deletes a specific user

Conditions
----------
 - You can use any language you want for the API
 - You can use any database system you want
 - Everything needs to run from a single command (ex: start/stop/restart)

What we will evaluate
---------------------
 - Reliability
 - Code structure
 - Tool/Libraries usage

Extra points
------------
 - Unit tests
 - Adding cache
 - Documentation

Notes
-----
 - The test needs to run in Mac
