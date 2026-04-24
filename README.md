# tokalibs

A monorepo of Toka third-party libraries.

## Libraries

| Library | Description |
|---------|-------------|
| toka-colors | ANSI color constants - `println("{}{}text{}", red, green, reset)` |
| toka-box | Info boxes with Unicode borders |
| toka-progress | Progress bars with percentage |
| toka-spinner | Animated spinner |
| toka-banner | Section headers and dividers |
| toka-prompt | Interactive prompts |

## Key feature

Since Toka v0.9.0, `v"..."` string literals support `\x` escape sequences,
enabling clean `const str` color constants:

```toka
import lib/toka_colors::{red, green, bold, reset}
println("{}{}Hello{}", bold, green, reset)
```

## Run

```bash
toka run
```

## License
Apache-2.0
