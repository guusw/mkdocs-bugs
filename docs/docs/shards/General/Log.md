---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# Log

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` || | | `Any` |
| `<output>` || | | `Any` |
| `Prefix` |  | The message to prefix to the logged output. | `""` | `String` |
| `Level` |  | The level of logging. | `Enum: 2 vendor: 0x66726167 type: 0x6c6f674c` | `LogLevel` |

</div>

Logs the output of a shard or the value of a variable to the console (along with an optional prefix string).

## Details

--8<-- "details/shards/General/Log.md"


## Examples

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/General/Log/1.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/General/Log/1.edn.log"
    ```
&nbsp;

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/General/Log/2.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/General/Log/2.edn.log"
    ```
&nbsp;

--8<-- "includes/license.md"
