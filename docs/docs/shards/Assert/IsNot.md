---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# Assert.IsNot

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` ||The input can be of any type. | | `Any` |
| `<output>` ||The output will be the input (passthrough). | | `Any` |
| `Value` |  | The value to test against for equality. | `None` | `Any` |
| `Abort` |  | If we should abort the process on failure. | `false` | `Bool` |

</div>

This assertion is used to check whether the input is different from a given value.

## Details

--8<-- "details/shards/Assert/IsNot.md"


## Examples

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/Assert/IsNot/1.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/Assert/IsNot/1.edn.log"
    ```
&nbsp;

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/Assert/IsNot/2.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/Assert/IsNot/2.edn.log"
    ```
&nbsp;

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/Assert/IsNot/3.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/Assert/IsNot/3.edn.log"
    ```
&nbsp;

=== "Code"

    ```clojure linenums="1"
    --8<-- "samples/shards/Assert/IsNot/4.edn"
    ```

=== "Output"

    ```
    --8<-- "samples/shards/Assert/IsNot/4.edn.log"
    ```
&nbsp;

--8<-- "includes/license.md"
