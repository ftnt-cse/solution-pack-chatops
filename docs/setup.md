| [Home](https://github.com/fortinet-fortisoar/solution-pack-chatops/blob/develop/README.md) |
|--------------------------------------------|

# Installation

1. To install a solution pack, click **Content Hub** > **Discover**.   
2. From the list of solution packs that appears, search for and select **ChatOps**.    
3. Click the **ChatOps** solution pack card.   
4. Click **Install** on the bottom to begin installation.

## Prerequisites
The **ChatOps** solution pack depends on the following solution packs. 

|Solution Pack|Purpose|
| :- | :- |
|SOAR Framework|Required for Incident Response modules|

# Configuration

For optimal performance of **ChatOps** solution pack, you can install and configure: 

* A connector that provides a geolocation service
    * To configure and use the IPStack as a geolocation service provider, refer to [Configuring IPStack](https://docs.fortinet.com/document/fortisoar/1.0.0/ipstack/1/ipstack-v1-0-0)
* Threat intelligence connectors to enrich context of a given indicator
    * To configure and use the VirusTotal connector as a source of threat intelligence, refer to [Configuring Virus Total](https://docs.fortinet.com/document/fortisoar/2.1.0/virustotal/166/virustotal-v2-1-0#Configuration_parameters)

