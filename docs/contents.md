| [Home](https://github.com/fortinet-fortisoar/solution-pack-chatops/blob/develop/README.md) |
|--------------------------------------------|

# Contents

## Connector(s)

|Connector|Description|
| :- | :- |
|IpStack| IPStack provides geolocation facility for IP Address or Domain. |
|VirusTotal| This connector facilitates automated operations such as scanning and analyzing suspicious files and URLs and retrieving reports from VirusTotal for files, IP addresses, and domains. |

> **Warning:** After deployment, this Solution Pack will install or upgrade the stated connectors list.

## Global Variable(s)

|Global Variable|Description|
| :- | :- |
|`Server_fqhn`| Stores the fully qualified host name of the server |


## Playbook Collection(s)

|09 - ChatOps|
| :- |

Playbook Name|Description|
 :- | :- |
|Bot command - Display Options|Displays a list of all the Bot commands.|
|Bot Command - Get Alerts|Retrieves details of a specific alert based on the provided alert ID.|
|Bot Command - Get Incidents|Retrieves details of a specific incident based on the provided incident ID.|
|Bot Command - Get Location|Retrieves the Geolocation details for the specified indicator.|
|Bot Command - Get Reputation|Retrieves the reputation for the specified indicator.|
|Bot - Execute commands|Executes the specified Bot Command.|
|Bot Command - Get Similar Alerts|Retrieves the alert records that are similar to a specific alert based on the provided alert ID.|
|Code Snippet|Executes the provided Python code.|
|Get Similar Alerts - Fetch Similar Alerts|Retrieves a list of alerts related to the specified indicator.|

> **Warning:** It is recommended to clone these Playbooks before any customizations to avoid loss of information while upgrading the Solution Pack.
