# ZEOSIO

This is the header-only library for EOS(IO) smart contracts to integrate ZEOS protocol features like zk-SNARK verification or private deposits and withdrawals. Check out the [ZEOS whitepaper](https://github.com/mschoenebeck/zeos-docs/releases/download/v1.0.0/zeos_whitepaper_v1.0.0.pdf) for more Information.

See also:
- [Token Contract](https://github.com/mschoenebeck/thezeostoken/)
- [The ZEOS Book](https://mschoenebeck.github.io/zeos-orchard/) (including a full protocol specification)

## Description
This library includes all functions and action declarations of the ZEOS smart contracts that are necessary to get started with privacy on the EOS mainnet. It supports input packing for [Groth16](https://electriccoin.co/blog/bellman-zksnarks-in-rust/) and [Halo2](https://zcash.github.io/halo2/index.html) proofs.

## Getting Started

Clone this repository:

```
git clone https://github.com/mschoenebeck/zeosio.git
```

Include the header file into your smart contract and build as usual.

### Dependencies

- [EOSIO Contract Development Toolkit (CDT)](https://github.com/EOSIO/eosio.cdt/releases)

## Help
If you need help join us on [Telegram](https://t.me/ZeosOnEos)

## Authors

Matthias Schönebeck

## License

It's open source. Do with it whatever you want.

## Acknowledgments

Big thanks to the Electric Coin Company for developing, documenting and maintaining this awesome open source codebase for zk-SNARKs!

* [Zcash Protocol Specification](https://zips.z.cash/protocol/protocol.pdf)