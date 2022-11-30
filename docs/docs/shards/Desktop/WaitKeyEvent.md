---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# Desktop.WaitKeyEvent

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` || | | `None` |
| `<output>` || | | `Int2` |

</div>

### Pauses the wire and waits for keyboard events.
#### The output of this shard will be a Int2.
 * The first integer will be 0 for Key down/push events and 1 for Key up/release events.
 * The second integer will the scancode of the key.


--8<-- "includes/license.md"
