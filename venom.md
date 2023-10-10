## Basic info

#### Please provide an email address where we can contact you in connection with your grant and KYC process

`cooper.charles.m@gmail.com`

#### Display name

Venom & Fang

#### Website URL 

https://github.com/charles-cooper/venom-design

#### Short Bio

Venom is an intermediate representation (IR) for Vyper while Fang handles the compilation of Venom IR to assembly and bytecode.

## Impact statement

#### Describe your contribution(s) to Optimism 
_Please share the contributions you wish to receive RetroPGF for._

As the intermediate language for Vyper, Venom greatly facilitates optimizations resulting in drastically reduced bytecode size and gas usage. Fang can be used to compile Venom IR directly to assembly or EVM bytecode.

Venom offers a reduction in 20 to 30% of the size of the bytecode produced and in equivalent gas savings (up to 3 gas per byte saved, depending on usage patterns). 

Venom gives lower-level access to developers and auditors, facilitating the analysis and security auditing of smart contracts.

While implemented for Vyper, Venom is language agnostic and can work as an IR for other high level smart contract programming languages.

##### Contribution links

https://github.com/harkal/vyper/pull/1
Current work on new IR for Vyper

#### Impact

_Select the categories that best describe your impact_
- [x] OP Stack 

_Describe the impact your contribution(s) had on the Optimism Collective_

OP Stack:
- By making it easier to map IR to source code and bytecode, Venom increases the auditability and security of the OP Stack.
- The optimization allowed by Venom and the Fang compiler improve the efficiency of the OP stack. 


#### Impact metrics
_Highlight metrics to help badgeholders understand your impact. You can link to data dashboards, onchain contracts, spreadsheets, or any resources._

Bytecode size reduction - 20 to 30% <br>
https://github.com/harkal/vyper/pull/1



## Grants and funding

None

## Payout address

`0xAbfA48BCc0F96Fc70be7a4156b0a74Ea350167fD`
