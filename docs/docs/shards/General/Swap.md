---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# Swap

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` ||Any input is ignored. | | `Any` |
| `<output>` ||The input to this shard is passed through as its output. | | `Any` |
| `NameA` |  | The name of first variable. | `""` | `String &Any` |
| `NameB` |  | The name of second variable. | `""` | `String &Any` |

</div>

Swaps the values of the two variables passed to it via `:NameA` and `:NameB` parameters.

## Details

--8<-- "details/shards/General/Swap.md"


## Examples

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/General/Swap/Swap.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/General/Swap/Swap.edn.log"
    ```
&nbsp;

--8<-- "includes/license.md"
