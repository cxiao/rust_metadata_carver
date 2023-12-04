# Rust Metadata Carver
Find metadata in Rust binaries

![A screenshot of the Tags interface in Binary Ninja, showing a large number of tags labelled with the source file path, source file line, and source file column of panic location metadata embedded inside a Rust binary. For example, one tag has the label "library\std\src\sys\windows\c.rs: line 1362, col 9". All tags are using the 😱 emoji as an icon.](images/panic-path-tags-screenshot-border.png)

![A screenshot of several Rust "core::panic::Location" structs, all with the source file path "library\std\src\sys\windows\stdio.rs" and each with a line number and column number.](images/panic-location-structs-screenshot-border.png)

## Description

WIP plugin to find metadata from Rust binaries, including:

- Source file locations from panic unwind metadata (i.e. `core::panic::Location` structs embedded in the binary) 

## Minimum Version

4689

## License

This plugin is released under an [MIT license](./LICENSE).

## Metadata Version

2