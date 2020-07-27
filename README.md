<a href="https://www.cortex-ia.co.uk/" target="_blank"><img src="https://github.com/CortexIATest/CTXImages/blob/master/Cortex-350-120.png" alt="Welcome to Cortex!" width="350" height="120" border="0"></a>

# CTX-Vista-User-Management
The Vista User Management module allows the user to create and update Vista users, as well as being able to apply ACEs, ACLs, Clients and Groups to a user. 

Provided LivePortal is set up to use Vista authentication, Vista users created using the 'Create-LivePortal-User' flow will be able to login to LivePortal with their Vista credentials.

The module allows users to perform the following functionality:
* Create Vista User
* Change User Password
* Delete User
* Assign ACEs and ACLs to User
* Assign Groups and Clients to User
* Retreive Vista User's Properties
* Validate Vista User's Credentials

## Table of Contents
1) [Dependencies](#dependencies)
    * [Cortex Version](#cortex-version)
    * [OCIs](#ocis)
    * [Files](#files)
    * [Other](#other)
1) [Support and Warranty](#support-and-warranty)
1) [Installation](#installation)
1) [How to use](#how-to-use)
1) [How you can contribute](#how-you-can-contribute)
1) [Versioning](#versioning)
1) [Licensing](#licensing)

## Dependencies
### Cortex Version
This version of the CTX-Vista-User-Management module was developed in Cortex v6.4.0. Some functionality may not be available in other versions of Cortex.

### OCIs
The CTX-Vista-User-Management module requires the following Cortex OCIs:
* Cortex PowerShell OCI


### Files
The CTX-Vista-User-Management module requires the following files:
* [CTX-Vista-User-Management Studio Package](https://github.com/CortexIntelligentAutomation/CTX-Vista-User-Management/releases/download/v1.0/CTX-Vista-User-Management.studiopkg)

### Other Requisites
The CTX-Vista-User-Management module has the following additional requirements which are explained in detail in the [Deployment Plan](https://github.com/CortexIntelligentAutomation/CTX-Vista-User-Management/blob/master/CTX-Vista-User-Management%20-%20Deployment%20Plan.pdf)):
* PowerShell v5 to be installed on the application server
* SMTP Server Set-up

## Support and Warranty 
This module is supplied as a template that you can amend and extend to fit your requirements, as such it is not supported as part of the Cortex Product suite under the Cortex product support agreement.

## Installation
Details of how the module should be imported into Cortex can be found in the [Deployment Plan](https://github.com/CortexIntelligentAutomation/CTX-Vista-User-Management/blob/master/CTX-Vista-User-Management%20-%20Deployment%20Plan.pdf).

## How to use
A detailed User Guide has been provided with instructions on how to use the module, available [here](https://github.com/CortexIntelligentAutomation/CTX-Vista-User-Management/blob/master/CTX-Vista-User-Management%20-%20User%20Guide.pdf ). Configuration of each flow/subtask's inputs and outputs are detailed in notes on the flow/subtask workspace.

## How you can contribute
Unfortunately, we cannot offer pull requests at this time or accept any improvements.

## Versioning
The CTX-Vista-User-Management module has the following versions, starting with the most recent:

Version | Release | Functionality | Notes
------------ | ------------- | ----------- | -----------
v1.0 | 24/10/2018 | Create Vista User | Created 
v1.0 | 24/10/2018 | Change User Password | Created
v1.0 | 24/10/2018 | Delete User | Created
v1.0 | 24/10/2018 | Assign ACEs and ACLs to User | Created
v1.0 | 24/10/2018 | Assign Groups and Clients to User | Created
v1.0 | 24/10/2018 | Retreive Vista User's Properties | Created
v1.0 | 24/10/2018 | Validate Vista User's Credentials | Created
v1.0 | 24/10/2018 | Create LivePortal User | Created
v1.0 | 24/10/2018 | Change Password UI | Created



## Licensing
All functionality within this module is licensed under the [Apache 2.0 License](https://www.apache.org/licenses/LICENSE-2.0).

Copyright 2018 Cortex Limited

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
