---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# Http.Patch

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` || | | `None { String } Bytes String` |
| `<output>` || | | `String` |
| `URL` |  | The url to request to. | `""` | `String &String` |
| `Headers` | :fontawesome-solid-circle-plus:{title="Optional"}  | The headers to use for the request. | `None` | `{ String } &{ String }` |
| `Timeout` |  | How many seconds to wait for the request to complete. | `10` | `Int` |
| `Bytes` |  | If instead of a string the shard should output bytes. | `false` | `Bool` |
| `FullResponse` |  | If the output should be a table with the full response, including headers and status. | `false` | `Bool` |

</div>



--8<-- "includes/license.md"
