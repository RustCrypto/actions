# RustCrypto: `intel-sde-install` action

Installs the Intel Software Development Emulator for AVX-512 CI.

## Example

```yaml
steps:
  - uses: actions/checkout@v6
  - uses: RustCrypto/actions/intel-sde-install@master
  - uses: dtolnay/rust-toolchain@master
  - run: cargo test --features avx512
```
