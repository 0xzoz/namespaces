---
namespace-identifier: fil-caip2
title: Blockchain Reference for Filecoin Namespace - Chains
author: Sergey Ukustov (@ukstv)
discussions-to: https://github.com/ChainAgnostic/CAIPs/pull/23
status: Draft
type: Standard
created: 2020-08-26
requires: CAIP-2
supersedes: CAIP-23
---

# CAIP-2

This document is about the details of the Filecoin network namespace and reference for CAIP-2.

## Abstract
In CAIP-2 a general blockchain identification scheme is defined. This is the
implementation of CAIP-2 for Filecoin network.

## Motivation
See CAIP-2.

## Specification

### Filecoin Namespace

The namespace "fil" refers to the wider Filecoin ecosystem.

#### Reference Definition

The reference relies on Filecoin's current designation of addresses belonging to
test or main networks by prefixing them with `t` or `f` correspondingly.

Reference could only be populated with `f` or `t` symbols.

## Rationale

Blockchains in the "filecoin" namespace are [Filecoin](https://filecoin.io)
blockchains, i.e. Filecoin mainnet, Filecoin testnet, and few devnets.

## Backwards Compatibility

Not applicable

## Test Cases

This is a list of manually composed examples

```
# Testnet and Devnets
fil:t

# Mainnet
fil:f
```

## References

- [Filecoin Specification](https://beta.spec.filecoin.io/appendix/address/)

## Rights

Copyright and related rights waived via [CC0](https://creativecommons.org/publicdomain/zero/1.0/).