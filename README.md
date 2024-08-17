# EpicChain-CPP-Engine

## Overview

**EpicChain-CPP-Engine** is the C++ core engine for the EpicChain blockchain platform. It provides a foundational implementation of the blockchain's core functionalities and is designed to work seamlessly with the EpicChain ecosystem, including integrations with JavaScript-based tools and libraries.

## Getting Started

### Cloning the Repository

To get started, clone the repository and initialize submodules:

```bash
git clone https://github.com/epicchain/EpicChain-CPP-Engine.git
cd EpicChain-CPP-Engine
git submodule update --init --recursive
git submodule update --recursive
```

### Building and Testing

**EpicChain-CPP-Engine** is in the prototype stage but is already quite advanced. To build and test the C++ and JavaScript implementations:

- **For C++ Implementation**:
  - Build the project by running:
    ```bash
    make
    ```
  - Run the built application:
    ```bash
    ./build/app_main
    ```

- **For JavaScript Implementation**:
  - Build and run the tests by executing:
    ```bash
    make jstest
    ```
  - This command will build everything and run `node_test.js`.

## Dependencies

**EpicChain-CPP-Engine** relies on several key external libraries:

- **BigInteger Library**:
  - **C++**: Uses [csBigInteger-cpp](https://github.com/neoresearch/csBigInteger-cpp), which depends on GNU MP (GMP) or optionally Mono BigInteger.
  - **JavaScript**: Utilizes [csBigInteger.js](https://github.com/neoresearch/csBigInteger.js), which uses [bn.js](https://github.com/indutny/bn.js).

- **Cryptography Library**:
  - **C++**: Incorporates [libcrypton](https://github.com/neoresearch/libcrypton), which uses OpenSSL or optionally Crypto++ from Wei Dai.
  - **JavaScript**: Employs [crypto-js](https://github.com/brix/crypto-js) for SHA256 and may use [elliptic](https://github.com/indutny/elliptic) for elliptic curve operations.

## Contributing

Contributions are welcome! Please refer to the [Contribution Guidelines](CONTRIBUTING.md) for details on how to contribute to the project.

## License

This project is licensed under the [MIT License](LICENSE).

## Contact

For questions or further information, please reach out to us at [support@epic-chain.org](mailto:support@epic-chain.org).

