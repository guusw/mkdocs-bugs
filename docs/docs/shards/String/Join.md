---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# String.Join

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` ||A sequence of string values that will be joined together. | | `[ String ]` |
| `<output>` ||A string consisting of all the elements of the sequence delimited by the separator. | | `String` |
| `Separator` |  | The string to use as a separator. | `""` | `String` |

</div>

Concatenates all the elements of a string sequence, using the specified separator between each element.

## Examples

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/String/Join/1.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/String/Join/1.edn.log"
    ```
&nbsp;

--8<-- "includes/license.md"
