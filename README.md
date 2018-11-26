# `stm32f30x`

> Peripheral access API for STM32F30X microcontrollers

# [Documentation](https://docs.rs/stm32f30x)

# Building

See also the ./ci/script.sh script
```
curl -LO https://github.com/posborne/cmsis-svd/raw/python-0.4/data/STMicro/STM32F30x.svd
dos2unix STM32F30x.svd
patch -p1 STM32F30x.svd < "${svd%.*}.patch"
```

# License

Licensed under either of

- Apache License, Version 2.0 ([LICENSE-APACHE](LICENSE-APACHE) or
  http://www.apache.org/licenses/LICENSE-2.0)

- MIT license ([LICENSE-MIT](LICENSE-MIT) or http://opensource.org/licenses/MIT)

at your option.

## Contribution

Unless you explicitly state otherwise, any contribution intentionally submitted
for inclusion in the work by you, as defined in the Apache-2.0 license, shall be
dual licensed as above, without any additional terms or conditions.
