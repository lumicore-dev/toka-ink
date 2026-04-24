# tokalibs

A monorepo of Toka libraries.

## Libraries

| Library | Description |
|---------|-------------|
| toka-colors | Colorize text with ANSI codes |
| toka-box | Colored info boxes with Unicode borders |
| toka-progress | Progress bars with percentage |
| toka-spinner | Animated spinner (frames: `- \ | /`) |

## Usage

```
import lib/toka_colors::{red, green, yellow, blue, bold}
import lib/toka_box/main::{info_box, success_box, warn_box, error_box}
import lib/toka_progress/main::{render}
import lib/toka_spinner/main::{spin}
```

See `src/main.tk` for a full demo.

## Run

```bash
toka run
```

## License
Apache-2.0
