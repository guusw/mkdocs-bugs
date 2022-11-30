---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# Const

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` ||Any input is ignored. | | `None` |
| `<output>` ||The declared constant value. | | `Any` |
| `Value` |  | The constant value to insert in the wire. | `None` | `Any` |

</div>

Declares an un-named constant value (of any data type).

## Details

--8<-- "details/shards/General/Const.md"


## Examples

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/General/Const/Const.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/General/Const/Const.edn.log"
    ```
&nbsp;

--8<-- "includes/license.md"
