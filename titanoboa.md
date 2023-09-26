## Basic info

#### Please provide an email address where we can contact you in connection with your grant and KYC process

`Fill`

#### Display name

Titanoboa

#### Website URL 

https://github.com/vyperlang/titanoboa

#### Short Bio

Titanoboa is a Vyper interpreter offering features such as step-by-step debugging, gas profiling, pretty tracebacks, Jupyter notebook integration and blazingly fast speeds thanks to its highly optimized backend. Titanoboa allows Vyper developers to quickly prototype as well as thoroughly test their smart contracts.

## Impact statement

#### Describe your contribution(s) to Optimism 
_Please share the contributions you wish to receive RetroPGF for._

Since its launch last year, Titanoboa (boa for short) has quickly evolved to become one of the most advanced smart contract development toolkits offering Vyper developers unrivaled speed in testing and prototyping, as well as a number of features unavailable with Solidity frameworks. 

Titanoboa's advanced and fast testing capabilities make it possible to run extremely comprehensive and fine grained tests on a smart contract suite. In addition to test coverage reports, print statements, a fork mode, time travel, EVM state patching, pattern matching for revert checking and integration with pytest, Titanoboa offers a number of more advanced testing features. Custom precompiles, for instance, make it easy to debug and test intermediate contract states while the fuzz decorator will automatically generate fuzzing strategies for a function. Opcode patching makes it possible to test advanced edge cases or soon-to-be-implemented EVM opcodes. This is particularly useful to developers who want to test their contracts across different versions of the EVM, such as those developing on Mainnet and Optimism. The fork mode is also set to see improvements to better handle differing EVM versions and rules based on the network provided.

The advantages of these testing features are compounded by the speed at which Titanoboa's highly optimized backend can run them. The Curve Finance protocol, for instance, drastically reduced the time it took to run the test suite for its new product from several hours to under a minute. Boa does so by cutting the need for slow external RPC calls, relying instead on a embedded EVM which allows it to run contracts directly as Python code.

Titanoboa also shines as a prototyping tool. The integration with Jupyter notebooks means that developers can easily spin up a notebook on Google Collab and start working together on prototyping and iterating their smart contract idea. It also makes it easy to share and run code to to craft and submit complex custom transactions such as DAO proposals with non-developers. Other features include a breakpoint() instruction which allows for step-by-step debugging and a line-by-line gas profiling tool for targeted optimizations.

Titanoboa's advanced features and easy-to-use interface have streamlined the smart-contract writing and testing process for Vyper developers on Optimism and Mainnet, thus making significant contributions to the growth and security of the network.


##### Contribution links

https://github.com/vyperlang/titanoboa Official repository for Titanoboa

https://github.com/curvefi/curve-stablecoin/tree/master/tests Tests for Curve's new stablecoin/lending product, written with titanoboa

#### Impact

_Select the categories that best describe your impact_
- [x] OP Stack
- [x] Developer Ecosystem

_Describe the impact your contribution(s) had on the Optimism Collective_

OP Stack:
- Titanoboa's embedded EVM, granular gas profiler and advanced testing features enhance contract security and efficiency within the OP Stack.

Developer Ecosystem:
- Features such as integration with Jupyter notebooks, live blockchain interactions, and pure Python execution are pivotal for swift and efficient contract deployments.
- Titanoboa's testing features are essential for smart-contract developers working on multiple networks such as Optimism and Mainnet.

#### Impact metrics
_Highlight metrics to help badgeholders understand your impact. You can link to data dashboards, onchain contracts, spreadsheets, or any resources._

Backend optimization metrics <br>
https://twitter.com/big_tech_sux/status/1671051375361560576

Jupyter notebook showcase <br>
https://twitter.com/big_tech_sux/status/1668305117605662720

## Grants and funding

None

## Payout address

`Fill`
