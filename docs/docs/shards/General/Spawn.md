---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# Spawn

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` || | | `Any` |
| `<output>` || | | `Wire` |
| `Wire` | :fontawesome-solid-circle-plus:{title="Optional"}  | The wire to spawn and try to run many times concurrently. | `None` | `Wire String &Wire` |

</div>



## Examples

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/General/Spawn/Spawn.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/General/Spawn/Spawn.edn.log"
    ```
&nbsp;

--8<-- "includes/license.md"
