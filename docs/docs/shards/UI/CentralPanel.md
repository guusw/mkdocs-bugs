---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# UI.CentralPanel

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` ||The value that will be passed to the Contents shards of the panel. | | `Any` |
| `<output>` ||The output of this shard will be its input. | | `Any` |
| `Contents` | :fontawesome-solid-circle-plus:{title="Optional"}  | The UI contents. | `None` | `Shard [ Shard ]` |

</div>

Layout UI elements into the central panel.

## Examples

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/UI/CentralPanel/1.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/UI/CentralPanel/1.edn.log"
    ```
&nbsp;

--8<-- "includes/license.md"
