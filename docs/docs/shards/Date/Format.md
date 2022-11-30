---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# Date.Format

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` ||An epoch timestamp (seconds after epoch). | | `Int` |
| `<output>` ||A formatted readable string. | | `String` |
| `Format` |  | The actual formatting string, see full docs: https://docs.rs/chrono/0.4.19/chrono/format/strftime/index.html#specifiers | `"%a %b %e %T %Y"` | `String` |

</div>

Reads an epoch timestamps and formats it into a readable string.

--8<-- "includes/license.md"
