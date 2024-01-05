# cargo-outdated with Bevy

An example Cargo project in which `cargo-outdated` takes a very long time
to complete. Tested with Rust 1.75.0 and nightly.

```shell
cargo install cargo-outdated
time cargo-outdated
```

```
Name                                         Project  Compat  Latest  Kind    Platform
----                                         -------  ------  ------  ----    --------
bevy_asset_loader                            0.18.0   ---     0.19.1  Normal  ---
bevy_asset_loader->bevy_asset_loader_derive  0.18.0   ---     0.19.0  Normal  ---
cargo outdated  119.29s user 3.08s system 97% cpu 2:05.21 total
```
