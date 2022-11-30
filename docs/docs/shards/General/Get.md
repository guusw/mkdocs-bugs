---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# Get

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` ||Any input is ignored. | | `None` |
| `<output>` ||The output is the value read from the variable. | | `Any` |
| `Name` |  | The name of the variable. | `""` | `String &Any` |
| `Key` | :fontawesome-solid-circle-plus:{title="Optional"}  | The key of the value to read/write from/in the table (parameter applicable only if the target variable is or will become a table). | `None` | `String &String ` |
| `Global` |  | If the variable is or should be available to all of the wires in the same mesh. | `false` | `Bool` |
| `Default` |  | The default value to use to infer types and output if the variable is not set, key is not there and/or type mismatches. | `None` | `Any` |

</div>

Reads the value of the variable passed to it.

## Details

--8<-- "details/shards/General/Get.md"


## Examples

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/General/Get/Get.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/General/Get/Get.edn.log"
    ```
&nbsp;

--8<-- "includes/license.md"
