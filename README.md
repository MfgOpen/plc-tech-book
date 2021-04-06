# Programmable Logic Controller (PLC) Technology Book

This repository contains the source materials for the "Programmable Logic
Controller (PLC) Technology Book".

## Requirements

In order to build this book locally, the
[mdBook](https://github.com/rust-lang/mdBook) utility must be used.

After installing [Rust](https://www.rust-lang.org/tools/install), the mdBook
package can be installed by the following command:

```sh
cargo install mdbook
```

## Building

The book can be build with the following command:

```sh
mdbook build
```

The output of this command can be found in the `book` directory.

To build the book and view it locally in a web browser, the following command
can be used:

```sh
mdbook serve
```

This will launch a local web server and the book can be viewed by visiting
[http://localhost:3000/](http://localhost:3000/). Any changes to the book
source materials will automatically be built and refreshed in the web browser.

## Licenses

The source code contained within this repository is licensed under the
[MIT License](./LICENSE).

The actual written content is licensed under the [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).
