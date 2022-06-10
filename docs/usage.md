| [Home](https://github.com/fortinet-fortisoar/solution-pack-chatops/blob/develop/README.md) |
|--------------------------------------------|

# Usage

The syntax of the command is: `$<command>` and followed by arguments. You need to type the command in the **Comments** tab under **Workspace** as shown in the following figure:

For Example. `$Get Alert 1` (Here 1 is Alert ID)

- Click on the **Workspace** icon in the detailed view of the record

    ![Open Workspace](https://github.com/fortinet-fortisoar/solution-pack-chatops/blob/develop/docs/res/open-workspace.png)

- Type the command in the **Comment** field

    ![Workspace Command](https://github.com/fortinet-fortisoar/solution-pack-chatops/blob/develop/docs/res/workspace-command.png)

- The playbooks associated with command execute in the background and provide the respective command output

    ![Command Output](https://github.com/fortinet-fortisoar/solution-pack-chatops/blob/develop/docs/res/command-output.png)

ChatOps Solution Pack supports following commands:

|Command|Description|
| :- | :- |
| `$Bot --help` | Displays a list of all the Bot commands. |
| `$Get Alert <Alert ID>` | Retrieves details of a specific alert based on the provided alert ID.|
| `$Get GeoLocation <IP Address or Domain>` | Retrieves the Geolocation details for the specified IP Address. |
| `$Get Incident <Incident ID>` | Retrieves details of a specific incident based on the provided incident ID. |
| `$Get Reputation <Indicator Value>` | Retrieves the reputation for the specified indicator. |
