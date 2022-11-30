---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# Math.Mean

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` ||A sequence of floating point numbers. | | `[ Float ]` |
| `<output>` ||The calculated mean. | | `Float` |
| `Kind` |  | The kind of Pythagorean means. | `Enum: 0 vendor: 0x66726167 type: 0x6d65616e` | `Mean` |

</div>

Calculates the mean of a sequence of floating point numbers.

## Examples

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/Math/Mean/Mean.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/Math/Mean/Mean.edn.log"
    ```
&nbsp;

--8<-- "includes/license.md"
