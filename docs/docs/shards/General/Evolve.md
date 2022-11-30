---
authors: Fragcolor & contributors
license: CC-BY-SA-4.0
---


# Evolve

<div class="sh-parameters" markdown="1">
| Name | - {: #sh-flags-row} | Description | Default | Type |
|------|---------------------|-------------|---------|------|
| `<input>` || | | `Any` |
| `<output>` || | | `[ Float Wire ]` |
| `Wire` |  | The wire to optimize and evolve. | `None` | `Wire` |
| `Fitness` |  | The fitness wire to run at the end of the main wire evaluation and using its last output; should output a Float fitness value. | `None` | `Wire` |
| `Population` |  | The population size. | `64` | `Int` |
| `Mutation` |  | The rate of mutation, 0.1 = 10%. | `0.2` | `Float` |
| `Crossover` |  | The rate of crossover, 0.1 = 10%. | `0.2` | `Float` |
| `Extinction` |  | The rate of extinction, 0.1 = 10%. | `0.1` | `Float` |
| `Elitism` |  | The rate of elitism, 0.1 = 10%. | `0.1` | `Float` |
| `Threads` |  | The number of cpu threads to use. | `2` | `Int` |
| `Coroutines` |  | The number of coroutines to run on each thread. | `8` | `Int` |

</div>



--8<-- "includes/license.md"
