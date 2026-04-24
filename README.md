# tokalibs

A monorepo of Toka libraries.

## Libraries

| Library | File | Description |
|---------|------|-------------|
| toka-colors | `lib/toka_colors.tk` | Colorize text with ANSI codes |
| toka-box | `lib/toka_box/main.tk` | Colored info boxes |
| toka-progress | `lib/toka_progress/main.tk` | Progress bars |

### toka-colors
```toka
import lib/toka_colors::{red, green, yellow, blue, bold}
print_line(cede green(String::from("Success!")))
```

### toka-box
```toka
import lib/toka_box/main::{info_box, success_box, warn_box, error_box}
print_line(cede info_box(String::from("Server started")))
```

### toka-progress
```toka
import lib/toka_progress/main::{render}
print(cede render(50))
```

## Run demo
```bash
toka run
```

## License
Apache-2.0
