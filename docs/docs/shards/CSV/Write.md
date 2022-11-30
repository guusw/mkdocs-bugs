---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# CSV.Write

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` ||A sequence of rows, with each row being a sequence of strings. | | `[ [ String ] ]` |
| `<output>` ||A multiline string in CSV format. | | `String` |
| `NoHeader` |  | Whether the shard should parse the first row as data, instead of header. | `false` | `Bool` |
| `Separator` |  | The character to use as fields separator. | `","` | `String` |

</div>

Reads a sequence of strings in a sequence of rows and outputs the data as a CSV string.

--8<-- "includes/license.md"
