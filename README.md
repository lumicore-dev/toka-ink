# tokalibs

A monorepo of Toka libraries.

## toka-colors

```toka
import lib/toka_colors::{red, green, blue, bold, dim, reset}
println("{}Success!{}", green, reset)
```

## toka-box

```toka
import lib/toka_box/main::{info_box, success_box, warn_box, error_box}
import std/string::String

print_line(cede info_box(String::from("Server started")))
```

## Run

```bash
toka run
```

## License
Apache-2.0
