---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# Network.Server

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` || | | `Any` |
| `<output>` || | | `Any` |
| `Address` |  | The local bind address or the remote address. | `"localhost"` | `String &String` |
| `Port` |  | The port to bind if server or to connect to if client. | `9191` | `Int &Int` |
| `Receive` | :fontawesome-solid-circle-plus:{title="Optional"}  | The flow to execute when a packet is received. | `None` | `Shard [ Shard ] ` |

</div>



--8<-- "includes/license.md"
