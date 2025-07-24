# yolo-rs

Run example from <https://github.com/pykeio/ort/tree/main/examples/yolov8> as a single project.

## Setup

- Copy image from <https://github.com/pykeio/ort/tree/main/examples/yolov8/data> into `data/` directory.

- Download model checkpoint from <https://cdn.pyke.io/0/pyke:ort-rs/example-models@0.0.0/yolov8m.onnx> into `checkpoints/` directory.

## Execute

With a working [Rust](https://www.rust-lang.org/) installation, you can simply execute

```bash
cargo run
```

## Todos

- [x] Try out execution provider for Apple Neural Engine
- [ ] Try out execution provider for Nvidia Cuda
