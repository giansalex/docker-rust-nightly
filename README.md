# Docker RUST nightly
[![Travis-CI](https://img.shields.io/travis/giansalex/docker-rust-nightly.svg?label=build&branch=master&style=flat-square)](https://travis-ci.org/giansalex/docker-rust-nightly)
[![Docker Build Status](https://img.shields.io/docker/build/giansalex/rust.svg?style=flat-square)](https://hub.docker.com/r/giansalex/rust/builds/)    
This image has a single tag, `nightly`, which is updated every week to match the
current Rust nightly. It is configured identically to that of the `latest` tag
of the official image, except that the nightly toolchain is selected via rustup.

### Install
```bash
docker pull giansalex/rust:nightly
```

> For typical use cases, see the [official image](https://hub.docker.com/_/rust/).


