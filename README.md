# FabricOS CLI Support README

FabricOS CLI Support contains what I consider to be the most important CLI commands for dealing with SAN-Switches. 
I created the collection to make my life easier when creating scripts with [PowerShell][] for [Visual Studio Code][].
I currently use [PowerShell][] Version 7.4.x for this purpose.
The easiest and better way is to download the extensions directly in the VS code under Extensions, 
as this is the quickest way to get the latest version without having to do anything.

All commands you find here correspond to the commands you can find in the [Brocade FabricOS Command Reference Manual][]. 
Not all options for all commands are available here, but the most common ones should be available.
If you miss something please contact me.

## Categorization List
| Categorization            | Subcategory                          | Content                                                                    |
| ------------------------- | ------------------------------------ | -------------------------------------------------------------------------- |
|          --------         | trufos_setup                         | One way to configure TruFOS (Basic)                                        |
|          --------         | switch_setup                         | One way to configure a SAN switch (Basic) via CLI                          |
|          --------         | virtualfabric_setup                  | One way to implement a virtual fabric                                      |
| ---------------------     | ------------------------------------ | -------------------------------------------------------------------------- |
| fos_alias                 |                                      | Everything that has to do with aliases                                     |
| fos_zone                  |                                      | Everything that has to do with zones                                       |
| fos_peerzone              |                                      | Everything that has to do with Peer zones                                  |
| fos_zoneObject            |                                      | Everything that has to do with Zone Objects                                |
| fos_cfg                   |                                      | Everything that has to do with Zone Configs and similar                    |
| fos_setup                 |                                      | Everything that has to do with SAN Switch setup like DNS, switchname etc.  |
| fos_passwd                |                                      | Everything that has to do with Password config                             |
| fos_user                  |                                      | Everything that has to do with User Configs                                |
| fos_virtual               |                                      | Everything that has to do with virtual Fabric and a bit more               |
| fos_firmware              |                                      | Everything that has to do with Frimware, upload download, delete           |
| fos_support               |                                      | Everything that has to do with Support                                     |
| fos_port                  |                                      | Everything that has to do with Port Config                                 |
| fos_port_show             |                                      | Everything that has to do with Port Information, classic show commands     |
| fos_port_log              |                                      | Everything that has to do with Port log commands                           |
| fos_port_cfg              |                                      | Everything that has to do with Port Config                                 |
| fos_switch_cfg            |                                      | Everything that has to do with Switch Config                               |
| fos_switch                |                                      | Everything that has to do with fos software "in direkt line" with a Switch |
| fos_slot                  |                                      | Everything that has to do with Slot Config, Management, etc                |
| fos_sec_policy            |                                      | Everything that has to do with Security Police                             |
| fos_switch_info           |                                      | Everything that has to do with Switch Infos with some show commands        |
| fos_info                  |                                      | This section includes commands that have not found a proper place          |

...more are still in the pipeline

## Requirements

Use [Visual Studio Code][] with recommendation in connection with the current [PowerShell][] module.
It also works in combination with my [IBM Storage CLI Support][] Snippet

[PowerShell]: https://github.com/PowerShell/PowerShell
[Visual Studio Code]: https://github.com/Microsoft/vscode
[Brocade FabricOS Command Reference Manual]: https://techdocs.broadcom.com/us/en/fibre-channel-networking/fabric-os/fabric-os-commands/9-2-x.html
[IBM Storage CLI Support]: https://marketplace.visualstudio.com/items?itemName=ToolDoc.ibm-storage-cli-support

## Known Issues

* Some tab stops do not work as desired
* Some explanations are not clear enough

## Release Notes

See [changelog](CHANGELOG.md) for all changes and releases.

## Working with Markdown

Here are some useful editor keyboard shortcuts:

* Split the editor (`Cmd+\` on macOS or `Ctrl+\` on Windows and Linux).
* Toggle preview (`Shift+Cmd+V` on macOS or `Shift+Ctrl+V` on Windows and Linux).
* Press `Ctrl+Space` (Windows, Linux, macOS) to see a list of Markdown snippets.

## For more information

* [Visual Studio Code's Markdown Support](http://code.visualstudio.com/docs/languages/markdown)
* [Markdown Syntax Reference](https://help.github.com/articles/markdown-basics/)

**Enjoy!**
