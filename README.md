# ZeroVault

A privacy-centric multi-signature wallet, leveraging the robust [Risc0](https://www.risczero.com/) stack.  

## Overview

**ZeroVault** signers remain undisclosed, and the multisig process is validated off-chain, then translated into proofs for later verification. This approach could yield a more cost-effective smart contract wallet, in contrast to current solutions managing similar functions on-chain where gas cost increase linearly with the number of signers. The wallet offers an off-chain guest code that computes the current state of the wallet, including signers and threshold, and verifies intended calls via the ZeroVault by validating signatures until the threshold is reached. Upon successful validation, a proof with a journal is generated and validated on the on-chain wallet, ensuring secure and efficient transaction processing.

**⚠️ WIP**

## References
- [risc0 Blog](https://www.risczero.com/blog/scalingeth-virtual-hackathon-winners)

