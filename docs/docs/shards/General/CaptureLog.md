---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# CaptureLog

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` || | | `None` |
| `<output>` || | | `[ String ]` |
| `Size` |  | The maximum number of logs to retain. | `8` | `Int` |
| `MinLevel` |  | The minimum level of logs to capture. | `"debug"` | `String` |
| `Pattern` |  | The pattern used to format the logs. | `"%^[%l]%$ [%Y-%m-%d %T.%e] [T-%t] [%s::%#] %v"` | `String` |
| `Suspend` |  | TODO. | `false` | `Bool` |

</div>



## Examples

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/General/CaptureLog/1.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/General/CaptureLog/1.edn.log"
    ```
&nbsp;

--8<-- "includes/license.md"
