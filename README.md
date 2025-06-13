# Simply Colored 🌈

![GitHub Repo Stars](https://img.shields.io/github/stars/Silvermax12/simply-colored?style=social) ![GitHub Release](https://img.shields.io/github/release/Silvermax12/simply-colored.svg) ![License](https://img.shields.io/badge/license-MIT-blue.svg)

Welcome to **Simply Colored**, the simplest crate in existence for terminal colors. This project aims to provide an easy way to add colors to your terminal output. Whether you're building a command-line tool or just want to make your scripts more visually appealing, Simply Colored has you covered.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Examples](#examples)
- [Contributing](#contributing)
- [License](#license)
- [Releases](#releases)

## Features

- Simple API for adding colors to terminal output.
- Lightweight and easy to integrate.
- Supports various color formats.
- Compatible with multiple platforms.

## Installation

To install Simply Colored, you can use Cargo, Rust's package manager. Run the following command in your terminal:

```bash
cargo add simply-colored
```

This will add Simply Colored to your project's dependencies.

## Usage

Using Simply Colored is straightforward. Here’s a basic example:

```rust
use simply_colored::Color;

fn main() {
    println!("{}", Color::Red.paint("This text is red!"));
    println!("{}", Color::Green.paint("This text is green!"));
}
```

You can replace `Color::Red` and `Color::Green` with other colors as needed.

## Examples

Here are some more examples to illustrate how you can use Simply Colored in your terminal applications.

### Basic Color Output

```rust
use simply_colored::Color;

fn main() {
    println!("{}", Color::Blue.paint("Hello, World! This is blue."));
    println!("{}", Color::Yellow.paint("This is yellow text."));
}
```

### Background Colors

You can also change the background color of your text:

```rust
use simply_colored::Color;

fn main() {
    println!("{}", Color::Red.on_white().paint("Red text on a white background."));
    println!("{}", Color::Green.on_black().paint("Green text on a black background."));
}
```

### Combining Styles

You can combine foreground and background colors for more complex styles:

```rust
use simply_colored::Color;

fn main() {
    println!("{}", Color::Cyan.on_magenta().paint("Cyan text on a magenta background."));
}
```

## Contributing

We welcome contributions! If you have suggestions for improvements or want to report a bug, please open an issue or submit a pull request. 

### Steps to Contribute

1. Fork the repository.
2. Create a new branch.
3. Make your changes.
4. Submit a pull request.

Please ensure your code adheres to the existing style and passes all tests.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Releases

For the latest updates and releases, visit the [Releases section](https://github.com/Silvermax12/simply-colored/releases). You can download the latest version and execute it directly.

### Note

To stay updated with new features and improvements, keep an eye on the [Releases section](https://github.com/Silvermax12/simply-colored/releases).

## Conclusion

Simply Colored aims to simplify the process of adding colors to your terminal output. With its straightforward API and lightweight design, you can enhance your terminal applications with minimal effort. We hope you find this crate useful and look forward to your contributions!

Feel free to reach out with any questions or suggestions. Happy coding!