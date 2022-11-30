---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# Start

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` || | | `Any` |
| `<output>` || | | `Any` |
| `Wire` | :fontawesome-solid-circle-plus:{title="Optional"}  | The name of the wire to switch to. | `None` | `Wire String ` |

</div>

Starts a given wire and suspends the current one. In other words, switches flow execution to another wire.

## Examples

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/General/Start/Start.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/General/Start/Start.edn.log"
    ```
&nbsp;

--8<-- "includes/license.md"
