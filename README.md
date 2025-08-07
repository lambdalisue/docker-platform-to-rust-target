# docker-platform-to-rust-target

Static site to find a rust target for the docker platform

# Usage

Read `https://lambdalisue.github.io/docker-platform-to-rust-target/[{kind}/]{platform}` to find the target.

```sh
# Default (GNU on Linux, MSVC on Windows)
curl https://lambdalisue.github.io/docker-platform-to-rust-target/linux/amd64
curl https://lambdalisue.github.io/docker-platform-to-rust-target/linux/arm64
curl https://lambdalisue.github.io/docker-platform-to-rust-target/windows/amd64
curl https://lambdalisue.github.io/docker-platform-to-rust-target/windows/arm64
curl https://lambdalisue.github.io/docker-platform-to-rust-target/darwin/amd64
curl https://lambdalisue.github.io/docker-platform-to-rust-target/darwin/arm64

# GNU (GNU on Linux, GNU on Windows)
curl https://lambdalisue.github.io/docker-platform-to-rust-target/gnu/linux/amd64
curl https://lambdalisue.github.io/docker-platform-to-rust-target/gnu/linux/arm64
curl https://lambdalisue.github.io/docker-platform-to-rust-target/gnu/windows/amd64
curl https://lambdalisue.github.io/docker-platform-to-rust-target/gnu/windows/arm64
curl https://lambdalisue.github.io/docker-platform-to-rust-target/gnu/darwin/amd64
curl https://lambdalisue.github.io/docker-platform-to-rust-target/gnu/darwin/arm64

# musl (musl on Linux, MSVC on Windows)
curl https://lambdalisue.github.io/docker-platform-to-rust-target/musl/linux/amd64
curl https://lambdalisue.github.io/docker-platform-to-rust-target/musl/linux/arm64
curl https://lambdalisue.github.io/docker-platform-to-rust-target/musl/windows/amd64
curl https://lambdalisue.github.io/docker-platform-to-rust-target/musl/windows/arm64
curl https://lambdalisue.github.io/docker-platform-to-rust-target/musl/darwin/amd64
curl https://lambdalisue.github.io/docker-platform-to-rust-target/musl/darwin/arm64

# msvg (GNU on Linux, MSVC on Windows)
curl https://lambdalisue.github.io/docker-platform-to-rust-target/msvc/linux/amd64
curl https://lambdalisue.github.io/docker-platform-to-rust-target/msvc/linux/arm64
curl https://lambdalisue.github.io/docker-platform-to-rust-target/msvc/windows/amd64
curl https://lambdalisue.github.io/docker-platform-to-rust-target/msvc/windows/arm64
curl https://lambdalisue.github.io/docker-platform-to-rust-target/msvc/darwin/amd64
curl https://lambdalisue.github.io/docker-platform-to-rust-target/msvc/darwin/arm64
```

# LICENSE

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
