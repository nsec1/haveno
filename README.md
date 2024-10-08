<div align="center">
  <img src="https://raw.githubusercontent.com/haveno-dex/haveno-meta/721e52919b28b44d12b6e1e5dac57265f1c05cda/logo/haveno_logo_landscape.svg" alt="Haveno logo">

  [![Codacy Badge](https://app.codacy.com/project/badge/Grade/505405b43cb74d5a996f106a3371588e)](https://app.codacy.com/gh/haveno-dex/haveno/dashboard)
  ![GitHub Workflow Status](https://img.shields.io/github/actions/workflow/status/haveno-dex/haveno/build.yml?branch=master)
  [![GitHub issues with bounty](https://img.shields.io/github/issues-search/haveno-dex/haveno?color=%23fef2c0&label=Issues%20with%20bounties&query=project%3Ahaveno-dex%2F2)](https://github.com/orgs/haveno-dex/projects/2) |
  [![Twitter Follow](https://img.shields.io/twitter/follow/HavenoDEX?style=social)](https://twitter.com/havenodex)
  [![Matrix rooms](https://img.shields.io/badge/Matrix%20room-%23haveno-blue)](https://matrix.to/#/#haveno:monero.social) [![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-2.1-4baaaa.svg)](https://github.com/haveno-dex/.github/blob/master/CODE_OF_CONDUCT.md)
</div>

## What is Haveno?

Haveno (pronounced ha‧ve‧no) is an open source platform to exchange [Monero](https://getmonero.org) for fiat currencies like USD, EUR, and GBP or other cryptocurrencies like BTC, ETH, and BCH.

Main features:

- All communications are routed through **Tor**, to preserve your privacy

- Trades are **peer-to-peer**: trades on Haveno happen between people only, there is no central authority.

- Trades are **non-custodial**: Haveno supports arbitration in case something goes wrong during the trade, but arbitrators never have access to your funds.

- There is **No token**, because it's not needed. Transactions between traders are secured by non-custodial multisignature transactions on the Monero network.

See the [FAQ on our website](https://haveno.exchange/faq/) for more information.

## Status of the project

Haveno can be used on Monero's main network by using a third party Haveno network. We do not officially endorse any networks at this time.

A test network is also available for users to make test trades using Monero's stagenet. See the [instructions](https://github.com/haveno-dex/haveno/blob/master/docs/installing.md) to build Haveno and connect to the network.

Note that Haveno is being actively developed. If you find issues or bugs, please let us know.

Main repositories:

- **[haveno](https://github.com/haveno-dex/haveno)** - This repository. The core of Haveno.
- **[haveno-ui](https://github.com/haveno-dex/haveno-ui)** - The user interface.
- **[haveno-ts](https://github.com/haveno-dex/haveno-ts)** - TypeScript library for using Haveno.
- **[haveno-meta](https://github.com/haveno-dex/haveno-meta)** - For project-wide discussions and proposals.

If you wish to help, take a look at the repositories above and look for open issues. We run a bounty program to incentivize development. See [Bounties](#bounties)

The PGP keys of the core team members are in `gpg_keys/`.

## Keep in touch and help out!

Haveno is a community-driven project. For it to be successful it's fundamental to have the support and help of the community. Join the community rooms on our Matrix server:

- General discussions: **Haveno** ([#haveno:monero.social](https://matrix.to/#/#haveno:monero.social)) relayed on IRC/Libera (`#haveno`)
- Development discussions: **Haveno Development** ([#haveno-dev:monero.social](https://matrix.to/#/#haveno-dev:monero.social)) relayed on IRC/Libera (`#haveno-dev`)

Email: contact@haveno.exchange
Website: [haveno.exchange](https://haveno.exchange)

## Contributing to Haveno

See the [developer guide](docs/developer-guide.md) to get started developing for Haveno.

See [docs/CONTRIBUTING.md](docs/CONTRIBUTING.md) for our styling guides.

If you are not able to contribute code and want to contribute development resources, [donations](#support) fund development bounties.

## Bounties

To incentivize development and reward contributors we adopt a simple bounty system. Contributors may be awarded bounties after completing a task (resolving an issue). Take a look at the issues eligible for a bounty on the [dedicated Kanban board](https://github.com/orgs/haveno-dex/projects/2) or look for [issues labelled '💰bounty'](https://github.com/haveno-dex/haveno/issues?q=is%3Aissue+is%3Aopen+label%3A%F0%9F%92%B0bounty) in the main `haveno` repository. [Details and conditions for receiving a bounty](docs/bounties.md).

## Support and sponsorships

To bring Haveno to life, we need resources. If you have the possibility, please consider [becoming a sponsor](https://haveno.exchange/sponsors/) or donating to the project:

### Monero

<p>
  <img src="https://raw.githubusercontent.com/haveno-dex/haveno/master/media/donate_monero.png" alt="Donate Monero" width="150" height="150"><br>
  <code>42sjokkT9FmiWPqVzrWPFE5NCJXwt96bkBozHf4vgLR9hXyJDqKHEHKVscAARuD7in5wV1meEcSTJTanCTDzidTe2cFXS1F</code>
</p>

If you are using a wallet that supports OpenAlias (like the 'official' CLI and GUI wallets), you can simply put `fund@haveno.exchange` as the "receiver" address.

### Bitcoin

<p>
  <img src="https://raw.githubusercontent.com/haveno-dex/haveno/master/media/donate_bitcoin.png" alt="Donate Bitcoin" width="150" height="150"><br>
  <code>1AKq3CE1yBAnxGmHXbNFfNYStcByNDc5gQ</code>
</p>
