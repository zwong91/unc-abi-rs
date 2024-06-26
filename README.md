<div align="center">

  <h1><code>unc-abi-rs</code></h1>

  <p>
    <strong>Rust library providing unc ABI models.</strong>
  </p>

  <p>
    <a href="https://github.com/unc/unc-abi-rs/actions/workflows/test.yml?query=branch%3Amain"><img src="https://github.com/unc/unc-abi-rs/actions/workflows/test.yml/badge.svg" alt="Github CI Build" /></a>
    <a href="https://crates.io/crates/unc-abi"><img src="https://img.shields.io/crates/v/unc-abi.svg?style=flat-square" alt="Crates.io version" /></a>
    <a href="https://crates.io/crates/unc-abi"><img src="https://img.shields.io/crates/d/unc-abi.svg?style=flat-square" alt="Download" /></a>
    <a href="https://docs.rs/unc-abi"><img src="https://docs.rs/unc-abi/badge.svg" alt="Reference Documentation" /></a>
  </p>

  <h3>
      <a href="https://github.com/unc/abi">unc ABI</a>
      <span> | </span>
      <a href="https://docs.rs/unc-abi">Reference Documentation</a>
      <span> | </span>
      <a href="#contributing">Contributing</a>
  </h3>
</div>

## Release notes

**Release notes and unreleased changes can be found in the [CHANGELOG](CHANGELOG.md)**

## Overview

❗ **Warning: ABI is still in early stages of development so expect breaking changes to this library until we reach 1.0**

This library is meant to serve as an unopinionated reference for Rust models of the [Utility ABI](https://github.com/unc/abi).

## ABI Metaschema

This repo also contains meta [JSON Schemas](https://json-schema.org/) of ABI. These schemas can be found in the [`metaschema`](/metaschema) folder: `unc-abi-${version}-schema.json` for a specific ABI schema version or `unc-abi-current-schema.json` for what is currently in the `main` branch of the repository.

Metaschemas describe the properties of ABI schema format and allow anyone to validate whether a JSON file is a valid unc ABI. For example, one could use an online validator like <https://www.jsonschemavalidator.net/> or a library such as [ajv](https://github.com/ajv-validator/ajv).

## Contributing

If you are interested in contributing, please look at the [contributing guidelines](CONTRIBUTING.md).

## License

Licensed under either of

* Apache License, Version 2.0
   ([LICENSE-APACHE](LICENSE-APACHE) or <http://www.apache.org/licenses/LICENSE-2.0>)
* MIT license
   ([LICENSE-MIT](LICENSE-MIT) or <http://opensource.org/licenses/MIT>)

at your option.
