---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# Substrate.Encode

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` ||A sequence of values to SCALE encode. | | `[ Any ]` |
| `<output>` ||The encoded SCALE bytes. | | `Bytes` |
| `Hints` |  | The hints of types to encode, either "i8"/"u8", "i16"/"u16" etc... for int types, "c" for Compact int, "a" for AccountId or nil for other types. | `None` | `[ String None ]` |

</div>

Encode values into a byte array in SCALE format

--8<-- "includes/license.md"
