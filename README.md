# ChatOps Solution Pack

## Release Information

- Solution Pack Version: 1.0.0
- Minimum Compatible FortiSOAR™ Version: 7.2.0
- Authored By: Fortinet
- Certified: No

## Overview

### Introduction

*ChatOps Solution Pack* is designed to provide playbooks that facilitate users to perform a particular task using a set of commands. Please open any record like Alert or Incident, expand the **Workspace** panel and use ‘Comments’ to type your commands and observe the results.

### Usage

For more information, refer [here](https://github.com/fortinet-fortisoar/solution-pack-chatops/blob/develop/docs/solution-pack-guide.md).

## Prerequisites

|**Solution Pack**|**Purpose**|**Doc Link**|
| :- | :- | :- |
|SOAR Framework 1.0.0|Require for Incident Response modules|[Click here](https://github.com/fortinet-fortisoar/solution-pack-soar-framework/blob/develop/README.md)|

## Contents

1. Connector(s)

    |**Sr. No.**|**Connector**|
    | :- | :- |
    |1|IpStack|
    |2|VirusTotal|

     **Warning:** After deployment, this Solution Pack will install or upgrade the stated connectors list.

2. Global Variable(s)

    - `Server_fqhn`

3. Playbook Collection(s)

    - 09 - ChatOps(9):

    |**Playbook Name**|**Description**|
    | :- | :- |
    |Bot command - Display Options|Displays a list of all the Bot commands.|
    |Bot Command - Get Alerts|Retrieves details of a specific alert based on the provided alert ID.|
    |Bot Command - Get Incidents|Retrieves details of a specific incident based on the provided incident ID.|
    |Bot Command - Get Location|Retrieves the Geolocation details for the specified indicator.|
    |Bot Command - Get Reputation|Retrieves the reputation for the specified indicator.|
    |Bot - Execute commands|Executes the specified Bot Command.|
    |Bot Command - Get Similar Alerts|Retrieves the alert records that are similar to a specific alert based on the provided alert ID.|
    |Code Snippet|Executes the provided Python code.|
    |Get Similar Alerts - Fetch Similar Alerts|Retrieves a list of alerts related to the specified indicator.|

     **Warning:** It is recommended to clone these Playbooks before any customizations to avoid loss of information while upgrading the Solution Pack.
