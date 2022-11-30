---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# Substrate.StorageMap

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` ||A sequence of three strings representing the map we want to encode, the last one being SCALE encoded data of the key. | | `[ String ]` |
| `<output>` ||The encoded storage map. | | `Bytes` |
| `PreHashed` |  | If the keys are already hashed. | `false` | `Bool` |

</div>

Returns the encoded storage map corresponding to the input strings.

--8<-- "includes/license.md"
