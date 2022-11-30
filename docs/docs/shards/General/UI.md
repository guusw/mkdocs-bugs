---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# UI

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` || | | `Any` |
| `<output>` || | | `Any` |
| `Queue` |  | The draw queue | `None` | `&GFX.DrawQueue` |
| `Contents` | :fontawesome-solid-circle-plus:{title="Optional"}  | The UI contents. | `None` | `Shard [ Shard ]` |

</div>

Initializes a UI context.

## Examples

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/General/UI/1.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/General/UI/1.edn.log"
    ```
&nbsp;

--8<-- "includes/license.md"
