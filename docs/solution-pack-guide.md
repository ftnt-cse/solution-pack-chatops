# Usage of ChatOps Solution Pack

## ChatOps Commands

### Syntax

The syntax of this command is: `$` `<command>` and followed by arguments. You need to type the command in the **Comments** tab under **Workspace** as shown in the following figure:

For Example. `$Get Alert 1` (Here 1 is Alert ID)

- Click on the **Workspace** icon in the detailed view of the record

    ![Open Workspace](media/openWorkspace.png)

- Type the command in the comment field

    ![Workspace Command](media/workspaceCommand.png)

- The playbooks associated with command execute in the background and provide the respective command output

    ![Command Output](media/commandOutput.png)

ChatOps Solution Pack supports following commands:

|**Command**|**Description**|
| :- | :- |
| `$Bot --help` | Displays a list of all the Bot commands. |
| `$Get Alert <Alert ID>` | Retrieves details of a specific alert based on the provided alert ID.|
| `$Get GeoLocation <IP Address or Domain>` | Retrieves the Geolocation details for the specified IP Address. |
| `$Get Incident <Incident ID>` | Retrieves details of a specific incident based on the provided incident ID. |
| `$Get Reputation <Indicator Value>` | Retrieves the reputation for the specified indicator. |
