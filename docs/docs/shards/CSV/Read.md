---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# CSV.Read

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` ||A multiline string in CSV format. | | `String` |
| `<output>` ||A sequence of rows, with each row being a sequence of strings. | | `[ [ String ] ]` |
| `NoHeader` |  | Whether the shard should parse the first row as data, instead of header. | `false` | `Bool` |
| `Separator` |  | The character to use as fields separator. | `","` | `String` |

</div>

Reads a CSV string and outputs the data as a sequence of strings in a sequence of rows.

--8<-- "includes/license.md"
