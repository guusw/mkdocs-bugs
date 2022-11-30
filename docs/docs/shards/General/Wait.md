---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# Wait

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` || | | `Any` |
| `<output>` || | | `Any` |
| `Wire` | :fontawesome-solid-circle-plus:{title="Optional"}  | The wire to wait. | `None` | `Wire String &Wire` |
| `Passthrough` |  | The output of this shard will be its input. | `false` | `Bool` |
| `Timeout` | :fontawesome-solid-circle-plus:{title="Optional"}  | The optional amount of time in seconds to wait for the wire to complete, if the time elapses the wire will be stopped and the flow will fail with a timeout error. | `None` | `Float &Float ` |

</div>

Waits for another wire to complete before resuming execution of the current wire.

## Examples

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/General/Wait/Wait.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/General/Wait/Wait.edn.log"
    ```
&nbsp;

--8<-- "includes/license.md"
