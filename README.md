# minigrep

A simple grep-like program written in Rust.

## Usage

```shell
minigrep <pattern> <file>
```

if you want to ignore case:

```shell
IGNORE_CASE=1 minigrep <pattern> <file>
```

## Example

```shell
➜ cargo run -- to ./poem.txt
    Finished dev [unoptimized + debuginfo] target(s) in 0.00s
     Running `target/debug/minigrep to ./poem.txt`
Are you nobody, too?
How dreary to be somebody!

➜ IGNORE_CASE=1 cargo run -- to ./poem.txt
    Finished dev [unoptimized + debuginfo] target(s) in 0.00s
     Running `target/debug/minigrep to ./poem.txt`
Are you nobody, too?
How dreary to be somebody!
To tell your name the livelong day
To an admiring bog!
```
