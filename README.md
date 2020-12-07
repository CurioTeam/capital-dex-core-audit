# capital-dex-core-audit

Security audit repo for Capital Dex smart contracts

## Features overview

- Liquidity pools and AMM mechanism, the ability to set the withdrawal of a part of the exchange fee to the team's wallet
- Liquidity mining mechanism: ERC-20 CGT (Curio Governance Token) tokens will be distributed, which will be issued separately and put on a special reserve contract, part of the tokens allocated for liquidity mining is reserved for further use as the team decides (lock-up parts of users rewards, use in Curio Aragon DAO rewards distributions)
- Whitelist of DEX users (to ensure that users pass the KYC / AML procedure): check for swap, adding / removing liquidity, liquidity mining
- Whitelist for tokens with which you can create trading pairs 
- Ability to disable user verification by whitelist (in case of legal changes regarding the KYC procedure of users)
- The admin and manager roles to manage the whitelist of users
- Upgradable functionality for whitelist of users
