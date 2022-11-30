---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# Audio.ReadFile

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` || | | `None` |
| `<output>` || | | `Audio` |
| `File` |  | The audio file to read from (wav,ogg,mp3,flac). | `None` | `String &String` |
| `Channels` |  | The number of desired output audio channels. | `2` | `Int` |
| `SampleRate` |  | The desired output sampling rate. Ignored if inside an Audio.Channel. | `44100` | `Int` |
| `Samples` |  | The desired number of samples in the output. Ignored if inside an Audio.Channel. | `1024` | `Int` |
| `Looped` |  | If the file should be played in loop or should stop the wire when it ends. | `false` | `Bool` |
| `From` | :fontawesome-solid-circle-plus:{title="Optional"}  | The starting time in seconds. | `None` | `Float &Float ` |
| `To` | :fontawesome-solid-circle-plus:{title="Optional"}  | The end time in seconds. | `None` | `Float &Float ` |

</div>

--8<-- "includes/experimental.md"



--8<-- "includes/license.md"
