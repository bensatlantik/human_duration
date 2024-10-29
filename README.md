## Installation
Add human_duration to your Cargo.toml dependencies:

[dependencies]
human_duration = "0.1.0"

## Usage
The following example demonstrates how to use the format_duration function with the Duration type:

use human_duration::format_duration;
use std::time::Duration;

fn main() {
    let duration = Duration::new(93784, 0); // 1 day, 2 hours, 3 minutes, 4 seconds
    println!("{}", format_duration(duration)); 
    // Outputs: "1 day, 2 hours, 3 minutes, 4 seconds"
}

## License
This project is licensed under the MIT License. See the LICENSE file for details.

