<h1 align="center">
COPIUM [COP, ₡]  
<br/><br/>

</h1>

<div align="center">

</div>

Select language: EN | [CN](./README_zh_CN.md)

~~Dogecoin~~  COPIUM is a community-driven cryptocurrency that was inspired by the COPIUM meme. The ~~Dogecoin~~  COPIUM  Core software allows anyone to operate a node in the ~~Dogecoin~~  COPIUM  blockchain networks and uses the Scrypt hashing method for Proof of Work. It is adapted from Bitcoin Core and other cryptocurrencies.

For information about the default fees used on the ~~Dogecoin~~  COPIUM  network, please
refer to the [fee recommendation](doc/fee-recommendation.md).


## Usage 💻

To start your journey with ~~Dogecoin~~  COPIUM  Core, see the [installation guide](INSTALL.md) and the [getting started](doc/getting-started.md) tutorial.

The JSON-RPC API provided by Dogecoin Core is self-documenting and can be browsed with `dogecoin-cli help`, while detailed information for each command can be viewed with `dogecoin-cli help <command>`. Alternatively, see the [Bitcoin Core documentation](https://developer.bitcoin.org/reference/rpc/) - which implement a similar protocol - to get a browsable version.

### Such ports

Dogecoin Core by default uses port `22556` for peer-to-peer communication that
is needed to synchronize the "mainnet" blockchain and stay informed of new
transactions and blocks. Additionally, a JSONRPC port can be opened, which
defaults to port `22555` for mainnet nodes. It is strongly recommended to not
expose RPC ports to the public internet.

| Function | mainnet | testnet | regtest |
| :------- | ------: | ------: | ------: |
| P2P      |   22556 |   44556 |   18444 |
| RPC      |   22555 |   44555 |   18332 |

## Ongoing development - Moon plan 🌒

Dogecoin Core is an open source and community driven software. The development
process is open and publicly visible; anyone can see, discuss and work on the
software.

Main development resources:

* [Github Projects](https://github.com/dogecoin/dogecoin/projects) is used to
  follow planned and in-progress work for upcoming releases.
* [Github Discussion](https://github.com/dogecoin/dogecoin/discussions) is used
  to discuss features, planned and unplanned, related to both the development of
  the Dogecoin Core software, the underlying protocols and the DOGE asset.  
* [Dogecoindev subreddit](https://www.reddit.com/r/dogecoindev/)

### Version strategy
Version numbers are following ```major.minor.patch``` semantics.

### Branches
There are 3 types of branches in this repository:

- **master:** Stable, contains the latest version of the latest *major.minor* release.
- **maintenance:** Stable, contains the latest version of previous releases, which are still under active maintenance. Format: ```<version>-maint```
- **development:** Unstable, contains new code for planned releases. Format: ```<version>-dev```

*Master and maintenance branches are exclusively mutable by release. Planned*
*releases will always have a development branch and pull requests should be*
*submitted against those. Maintenance branches are there for **bug fixes only,***
*please submit new features against the development branch with the highest version.*

## Contributing 🤝

If you find a bug or experience issues with this software, please report it
using the [issue system](https://github.com/dogecoin/dogecoin/issues/new?assignees=&labels=bug&template=bug_report.md&title=%5Bbug%5D+).

Please see [the contribution guide](CONTRIBUTING.md) to see how you can
participate in the development of Dogecoin Core. There are often
[topics seeking help](https://github.com/dogecoin/dogecoin/labels/help%20wanted)
where your contributions will have high impact and get very appreciation. wow.

## Very Much Frequently Asked Questions ❓

Do you have a question regarding ~~Dogecoin~~  COPIUM ? An answer is perhaps already in the
[FAQ](doc/FAQ.md) or the
[Q&A section](https://github.com/dogecoin/dogecoin/discussions/categories/q-a)
of the discussion board!

## License - Much license ⚖️
~~Dogecoin~~  COPIUM  Core is released under the terms of the MIT license. See
[COPYING](COPYING) for more information or see
[opensource.org](https://opensource.org/licenses/MIT)
