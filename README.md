# tokalibs

A monorepo of Toka libraries.

## Libraries

### toka-colors — Colorize text
```toka
import lib/toka_colors::{red, green, yellow, blue, bold}
print_line(cede green(String::from("Success!")))
```

### toka-box — Info boxes
```toka
import lib/toka_box/main::{info_box, success_box, warn_box, error_box}
print_line(cede info_box(String::from("Server started")))
```

## Run demo
```bash
toka run
```

## License
Apache-2.0
