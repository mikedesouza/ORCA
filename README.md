# Oracle Rapid Clone Automation

**ORCA** is collection of Ansible playbooks which addresses the challenges of Oracle Database Copy Data Management (CDM). 
**ORCA** provides tradtional and modern DevOPS teams a Self Service solution enabling Developers, QA and business teams the abiliy to refresh non-Production databases without impacting Production systems.

**ORCA** utilises standard Ansible and Pure modules to manage Oracle database serices and perform 'Crash Consitent' storage snapshots, enabling end-to-end automation of Oracle databases refreshes across mulitple non-Production databases within the Enterprise. 

## Zero Production Impact
Unlike other Copy Data Management (CDM) solutions **ORCA** has zero Production Impact e.g.
1. No Production configuration changes e.g. OS or databases accounts
1. No Production agents or sofware installs
1. No additional Production backup worload e.g. RMAN jobs
1. No impact to Production database e.g. requirement to put database into Hot Backup mode.

## Modern DevOPS Solution
**ORCA** is designed to be run from RedHat Ansible Tower or the Opens Source AWX Project.

Suggested Automation and Orchestraction features required by CDM tools. 

1. WebUI and Command Line and REST API interfaces
1. The ability to schedule and run job interactivley 
1. Provide runtime variables and parameters 
1. Job notifications - Slack, email...
1. Code configuration management through Git intergration
1. Inventory management
1. Security and encrypted password management
1. User RBAC (RollBack Access Control)
1. Job Audit and reporting

### ORCA Features
1. Refresh Mulitple Oracle 18c Databases
1. Shutdown Oracle 18c Databases

## Getting Started

### Prerequisites

ORCA requires the Pure 

### Installation

Download **ORCA** from GitHub and localise vars/database.yaml to required source and target databases.

### Usage

Use from ansible control machine or via RedHat Tower / AWX.

### Examples
`
$ ansible-playbook <playbook-name>.yaml
`

## Restrictions

- Source and Target database(s) reside on the same FlashArray

## Authors

Ron Ekins, EMEA Oracle Solutions Architect at Pure Storage

## License

This module is available to use under the Apache 2.0 license, stipulated as follows:

Copyright 2018 Pure Storage, Inc.
Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at http://www.apache.org/licenses/LICENSE-2.0 Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on  an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.

## Link(s)

[RedHat Ansible] (https://www.ansible.com)

[RedHat Ansible Tower] (https://www.ansible.com/products/tower)

[RedHat Ansible AWX] (https://www.ansible.com/products/awx-project)

 

