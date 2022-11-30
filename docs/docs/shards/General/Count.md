---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# Count

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` ||Any input is ignored. | | `None` |
| `<output>` ||Count of characters, elements, or key-value pairs contained in the `:Name` parameter variable. | | `Int` |
| `Name` |  | The name of the variable. | `""` | `String &Any` |
| `Key` | :fontawesome-solid-circle-plus:{title="Optional"}  | The key of the value to read/write from/in the table (parameter applicable only if the target variable is or will become a table). | `None` | `String &String ` |
| `Global` |  | If the variable is or should be available to all of the wires in the same mesh. | `false` | `Bool` |

</div>

Parses the value in passed to in the `:Name` parameter and returns the count of characters (if string passed), elements (if sequence passed), or key-value pairs (if table passed).

## Details

--8<-- "details/shards/General/Count.md"


## Examples

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/General/Count/Count.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/General/Count/Count.edn.log"
    ```
&nbsp;

--8<-- "includes/license.md"
