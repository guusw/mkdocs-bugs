---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# ParseFloat

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` ||A string representing a number. | | `String` |
| `<output>` ||A floating-point number equivalent to the number contained in the string input. | | `Float` |

</div>

Converts the string representation of a number to a floating-point number equivalent.

## Examples

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/General/ParseFloat/1.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/General/ParseFloat/1.edn.log"
    ```
&nbsp;

--8<-- "includes/license.md"
