# Unit 2.5 - Closures and Dynamic dispatch

<a href="../slides/2_5-closures-and-dynamic-dispatch-export.pdf" target="_blank">Slides</a>


## Exercise 2.5.1: Config Reader

<!-- TODO this exercise imports dependencies, a concept which is introduced in B.
    We may want to put that a bit into the background by providing proxy functions in the scaffolding
    which can be called in the implementations of the `DeserializeConfig` trait
-->
In this exercise, you'll work with dynamic dispatch to deserialize with `serde_json` or `serde_yaml`, depending on the file extension. The starter code is in `exercises/2-foundations-of-rust/5-closures-and-dynamic-dispatch/1-config-reader`. Fix the todo's in there.

To run the program, you'll need to pass the file to deserialize to the binary, not to Cargo. To do this, run
```bash
cargo run -- <FILE_PATH>
```

Deserializing both `config.json` and `config.yml` should result in the `Config` being printed correctly.
