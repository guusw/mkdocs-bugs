---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# Branch

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` || | | `Any` |
| `<output>` || | | `Any` |
| `Wires` | :fontawesome-solid-circle-plus:{title="Optional"}  | The wires to schedule and run on this branch. | `None` | `Wire [ Wire ] ` |
| `FailureBehavior` |  | The behavior to take when some of the wires running on this branch mesh fail. | `Enum: 0 vendor: 0x66726167 type: 0x62726342` | `BranchFailure` |

</div>

A branch is a child mesh that runs and is ticked when this shard is activated, wires on this mesh will inherit all of the available exposed variables in the activator wire.

## Examples

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/General/Branch/Branch.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/General/Branch/Branch.edn.log"
    ```
&nbsp;

--8<-- "includes/license.md"
