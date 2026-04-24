# tokalibs

A monorepo of Toka libraries.

## Libraries

### toka-colors
```toka
import lib/toka_colors::{red, green, blue, bold, reset}
println("{}{}Hello{}", bold, green, reset)
```

### toka-box
```toka
import lib/toka_box/main::{info_box, success_box}
print_line(cede info_box(String::from("Server started")))
```

## Run

```bash
toka run
```

## License
Apache-2.0
