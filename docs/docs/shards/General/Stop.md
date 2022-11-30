---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# Stop

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` || | | `Any` |
| `<output>` || | | `Any` |
| `Wire` | :fontawesome-solid-circle-plus:{title="Optional"}  | The wire to stop. | `None` | `Wire String &Wire` |
| `Passthrough` |  | The output of this shard will be its input. | `false` | `Bool` |

</div>

Stops another wire. If no wire is given, stops the current wire.

## Examples

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/General/Stop/Stop.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/General/Stop/Stop.edn.log"
    ```
&nbsp;

--8<-- "includes/license.md"
