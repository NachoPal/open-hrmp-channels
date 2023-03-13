# HRMP open channels
Files to be run with https://github.com/paritytech/parachains-integration-tests

For this tests `v0.9.38` was used for both Polkadot an Cumulus to generate `polkadot` and `polkadot-parachain` binaries respectively.

Polakdot has to be build with `sudo` and `fast-runtime` flag. The branch with sudo is [this one](https://github.com/paritytech/polkadot/tree/it/release-v0.9.38-fast-sudo)
```
cargo build --release --features fast-runtime
```

Add under `./bin` the `polkadot` and `polkadot-parachain` generated binaries.
