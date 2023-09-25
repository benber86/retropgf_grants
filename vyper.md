## Basic info

#### Please provide an email address where we can contact you in connection with your grant and KYC process

`Fill`

#### Display name

Vyper

#### Website URL 

http://www.vyperlang.org

#### Short Bio

Vyper is a contract-oriented, pythonic programming language that targets the Ethereum Virtual Machine (EVM).

## Impact statement

#### Describe your contribution(s) to Optimism 
_Please share the contributions you wish to receive RetroPGF for._

Vyper is a pythonic programming language for smart contracts on the Ethereum Virtual Machine (EVM).
Vyper contracts account for over 7% ($50m) of the TVL on Optimism and secure more than $2 billion across multiple chains for major protocols such as Curve, Lido, Perpetual Protocol and Yearn.

Vyper is the second most-widely used smart contract programming language after Solidity and an essential resource to ensure language diversity on Optimism and Ethereum.

Vyper is also a long-time supporter of the Optimism ecosystem. 
The team added support for the first (non EVM-equivalent) version of the OVM back in 2020, and, more recently, worked on ways to mitigate issues faced by users unaware of the differences between EVM versions on Optimism and Mainnet (such as the PUSH0 opcode not being supported on Optimism, for instance).

Vyper's design principles have always prioritized security and audibility. Over the past couple of years, the team has greatly enhanced the review and audit process of the compiler to ensure the robustness and safety of the language.
The codebase is regularly reviewed by ChainSecurity, with additional input from StateMind and large protocols working with Vyper.
Following the discovery of a vulnerability in an older version of the compiler in the summer of 2023, the team responded by quickly coordinating with security professionals and affected protocols to prevent further exploits on other chains such as Optimism and rescue user funds. 
They later organized a $150k audit competition, coordinated bug bounty programs and allocated funding to bring Vyper support to essential smart contract security tools such as Trail of Bits' Slither (static analyzer) and Echidna (fuzzer). Certora also recently added support for Vyper to their prover, allowing for the formal verification of smart contracts written in Vyper.

The available tooling for Vyper has considerably improved thanks to the team's effort and collaboration to improve integrations. Frameworks such as ape, brownie and titanoboa offer an excellent integrated development experience for Vyper developers, making it possible to both quickly prototype or extensively tests contracts. Vyper is well integrated with popular editors such as Vim and VSCode and constant work is being done to improve integrations with major chain analysis tools (streamlining verification on Etherscan, improving debugging support on Tenderly) and popular development frameworks such as Foundry.

Since being praised by Vitalik Buterin in 2022 for "quietly continuing to progress and become a better and better Ethereum high-level language", Vyper has seen several upgrades and optimizations that have further solidified its reputation as a reliable, user-friendly and highly efficient choice for smart contract development.
Compiler optimizations allow the language to systematically offer lower gas costs and contract bytecode size compared to Solidity. 
The elaboration and implementation of the ERC-5202 factory pattern allows developers to deploy larger contracts for minimum deployment gas and to create complex factory contracts.
Finally, the development of a module system for the language will improve developer experience by limiting the need to reuse code across contracts.

As Optimism's second largest language, Vyper plays an instrumental role in the Collective's evolution, helping to provide onboard a larger amount of protocols and offer end-users more dapps while fostering language diversity. Vyper's unwavering commitment to security and continuous support for Optimism's growth testifies to its profound impact and make it a prime candidate for the retrofunding grant.

##### Contribution links

https://github.com/vyperlang/vyper
Official repository of the Vyper programming language

#### Impact

_Select the categories that best describe your impact_
- [x] OP Stack 
- [x] Developer Ecosystem

_Describe the impact your contribution(s) had on the Optimism Collective_

OP Stack:
- Vyper's commitment to security through its language design choices and stringent audit process increases the security of the OP Stack.
- Vyper contributes to language diversity on Optimism, thereby reducing the risk of a systemic failure arising from vulnerabilities in a single programming language.
- The Vyper team's continued efforts to bring optimizations to the compiler enhance the efficiency of the OP stack.

Developer Ecosystem:
- Major projects such as Curve, Lido, Perpetual Protocol, Velodrome Finance and Yearn all used Vyper contracts as part of their Optimism deployments.
- Vyper has been used by the Velodrome Finance team to develop contracts for chain data analytics (https://github.com/velodrome-finance/sugar). By offering a Python-like syntax and integrating with Python tooling such as Jupyter, Vyper significantly lowers the barrier of entry for the existing large community of Python developers.


#### Impact metrics
_Highlight metrics to help badgeholders understand your impact. You can link to data dashboards, onchain contracts, spreadsheets, or any resources._

Github stars - 4700<br>
https://github.com/vyperlang/vyper

TVL Secured - $2.3 billions<br>
https://defillama.com/languages

TVL Secured on Optimism - $50.2 millions<br>
https://defillama.com/protocol/curve-finance, https://optimistic.etherscan.io/address/0xd360b73b19fb20ac874633553fb1007e9fcb2b78, https://defillama.com/protocol/yearn-finance

Gas comparison metrics<br>
https://blog.chain.link/solidity-vs-vyper/

Gas comparison metrics 2<br>
https://github.com/z80dev/gascomps


## Grants and funding

- [x] RetroPGF2 <br>
135200 OP <br>
Vyper received 1.35% of the 10M OP allocated for RetroPGF2 for its contributions to the OP ecosystem

## Payout address

`Fill`
