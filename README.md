# Docker RUST nightly
[![Build Status](https://travis-ci.org/giansalex/docker-rust-nightly.svg?branch=master)](https://travis-ci.org/giansalex/docker-rust-nightly)    
This image has a single tag, `nightly`, which is updated every week to match the
current Rust nightly. It is configured identically to that of the `latest` tag
of the official image, except that the nightly toolchain is selected via rustup.

### Install
```bash
docker pull giansalex/rust:nightly
```

> For typical use cases, see the [official image](https://hub.docker.com/_/rust/).


