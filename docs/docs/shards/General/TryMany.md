---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# TryMany

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` || | | `[ Any ]` |
| `<output>` || | | `[ Any ]` |
| `Wire` | :fontawesome-solid-circle-plus:{title="Optional"}  | The wire to spawn and try to run many times concurrently. | `None` | `Wire String &Wire` |
| `Policy` |  | The execution policy in terms of wires success. | `Enum: 1 vendor: 0x66726167 type: 0x7472794d` | `WaitUntil` |
| `Threads` |  | The number of cpu threads to use. | `1` | `Int` |
| `Coroutines` |  | The number of coroutines to run on each thread. | `1` | `Int` |

</div>



## Examples

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/General/TryMany/TryMany.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/General/TryMany/TryMany.edn.log"
    ```
&nbsp;

--8<-- "includes/license.md"
