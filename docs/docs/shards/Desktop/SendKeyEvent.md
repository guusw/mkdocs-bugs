---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# Desktop.SendKeyEvent

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` || | | `Int2` |
| `<output>` || | | `Int2` |
| `Window` | :fontawesome-solid-circle-plus:{title="Optional"}  | None or a window variable if we wish to send the event only to a specific target window. | `None` | `Object ` |

</div>

### Sends the input key event.
#### The input of this shard will be a Int2.
 * The first integer will be 0 for Key down/push events and 1 for Key up/release events.
 * The second integer will the scancode of the key.


--8<-- "includes/license.md"
