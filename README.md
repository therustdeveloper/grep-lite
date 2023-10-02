# Grep Lite

From Rust in Action.

## Add regex

```commandline
cargo add regex@1
```

## Generate Local Documentation

```commandline
cargo doc
```

### Open the doc

```commandline
cd target/doc/grep_lite/
open index.html

or just run:

cargo doc --open
```

## Add Clap

```commandline
cargo add clap@2
```

### Run program with arguments

```commandline
cargo run -- picture
```