---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# Msg

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` || | | `Any` |
| `<output>` || | | `Any` |
| `Message` |  | The message to display on the user's screen or console. | `""` | `String` |
| `Level` |  | The level of logging. | `Enum: 2 vendor: 0x66726167 type: 0x6c6f674c` | `LogLevel` |

</div>

Displays the passed message string or the passed variable's value to the user via standard output.

## Details

--8<-- "details/shards/General/Msg.md"


## Examples

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/General/Msg/1.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/General/Msg/1.edn.log"
    ```
&nbsp;

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/General/Msg/2.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/General/Msg/2.edn.log"
    ```
&nbsp;

--8<-- "includes/license.md"
