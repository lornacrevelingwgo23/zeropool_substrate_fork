This is a fork of [zeropool](https://github.com/zeropoolnetwork/zeropool-substrate) library, which will serve as an important module in the ruby protocol. 

## Install Substrate/Zeropool Node

### Requirements

1. [Install Rust](https://www.rust-lang.org/tools/install)

   `curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh`
   
2. Install `make`

   * Ubuntu: `sudo apt-get install build-essential`
   * Mac OS: `xcode-select --install`

### Build and Run

To build and run the dev node, execute:

```bash
cd zk-substrate-devnet
make init
make run
```

