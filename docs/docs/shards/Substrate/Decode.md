---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# Substrate.Decode

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` ||The encoded SCALE bytes. | | `Bytes` |
| `<output>` ||The decoded values. | | `[ Any ]` |
| `Types` |  | The list of types expected to decode. | `None` | `[ Type ]` |
| `Hints` |  | The hints of the types to decode, either "i8"/"u8", "i16"/"u16" etc... for int types, "c" for Compact int, "a" for AccountId or nil for other types. | `None` | `[ String None ]` |
| `Version` |  | The substrate version prefix. | `42` | `Int` |

</div>

Decode SCALE encoded bytes into values

--8<-- "includes/license.md"
