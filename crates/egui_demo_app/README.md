# egui demo app

This app demonstrates [`egui`](https://github.com/emilk/egui/) and [`eframe`](https://github.com/emilk/egui/tree/master/crates/eframe).

The demo app is slightly modified to use `eframe_tao` instead.

View the demo app online at <https://egui.rs>.

Run it locally with `cargo run --release -p egui_demo_app`.

`egui_demo_app` can be compiled to WASM and viewed in a browser locally with:

```sh
./scripts/start_server.sh &
./scripts/build_demo_web.sh --open
```

`egui_demo_app` uses [`egui_demo_lib`](https://github.com/emilk/egui/tree/master/crates/egui_demo_lib).
