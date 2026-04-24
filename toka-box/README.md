# toka-box

Colorful information boxes for Toka.

## Usage

```toka
import std/io::{print_line}
import lib/toka_box/main::{info_box, success_box, warn_box, error_box}
import std/string::{String}

pub fn main() -> i32 {
    print_line(cede info_box(String::from("Server started")))
    print_line(cede success_box(String::from("All tests passed")))
    print_line(cede warn_box(String::from("Disk nearly full")))
    print_line(cede error_box(String::from("Connection lost")))
    return 0
}
```

## API

- `info_box(text)` — Blue box
- `success_box(text)` — Green box
- `warn_box(text)` — Yellow box
- `error_box(text)` — Red box

## License

Apache-2.0
