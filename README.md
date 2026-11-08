# mruby-gpu-examples

> **Proofs of concept written in mruby with the mruby GPU gems, and how they run on each device.**

🚧 **Planned** as part of the Ruby Association Grant 2026 project "Expanding GPU computing libraries for mruby" ([selection result](https://www.ruby.or.jp/en/news/20261102)). Nothing is usable here yet.

## Examples

1. A low-pass filter on camera frames with a 2-D FFT (`ifft2(fft2(img) * mask).real` in NumPy)
2. Aligning two images with phase-only correlation
3. Measuring a desk fan's rotation with both a camera and a single-point LiDAR (PONO TSD20)

Each example is meant to run unchanged on Raspberry Pi, an AMD mini PC, and NVIDIA Jetson AGX Orin. The results for each device will be published here.

Progress is tracked in the [GitHub Project](https://github.com/users/yujiteshima/projects/3).

## License

MIT
