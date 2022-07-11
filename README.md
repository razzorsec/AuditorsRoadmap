# AuditorsRoadmap

![Smart_Contract_Auditor_RoadMap](https://user-images.githubusercontent.com/54918791/174233728-015bd233-1df9-49fb-a6a3-2af970d90b60.png)  


Available at: https://coggle.it/diagram/YqLzaiSABzXD4UnZ/t/smart-contract-auditor  
PDF: [Smart Contract Auditor.pdf](https://github.com/razzorsec/AuditorsRoadmap/files/8934042/Smart.Contract.Auditor.pdf)

### Step by Step Approach  

* [Mastering Ethereum](https://github.com/ethereumbook/ethereumbook)  
* Proof of Work vs Proof of Stake
* Solidity Fundamentals
  * [Solidity Documentation](https://docs.soliditylang.org/en/latest/)
  * [Solidity Docs](https://docs.soliditylang.org/en/v0.8.13/index.html)
  * [Smart Contract Programmer - Solidity 0.8](https://www.youtube.com/playlist?list=PLO5VPQH6OWdVQwpQfw9rZ67O6Pjfo6q-p)
  * Connect Missing Dots with Secureum
    * [Secureum Solidity 101](https://secureum.substack.com/p/solidity-101?s=r)
    * [Secureum Solidity 201](https://secureum.substack.com/p/solidity-201?s=r)

* Gas Optimizations
  * [Aggregated Tricks by pcaversaccio and Harikrishnan Mulackal](https://forum.openzeppelin.com/t/a-collection-of-gas-optimisation-tricks/19966/6)
  * [Kaden: Gas Optimization Tips](https://betterprogramming.pub/how-to-write-smart-contracts-that-optimize-gas-spent-on-ethereum-30b5e9c5db85)
  * [Juan: Advanced Gas Optimizations](https://dev.to/juanxavier/advanced-gas-optimizations-tips-for-solidity-1j2f)

* Smart Contract Testing
  * [Hardhat](https://hardhat.org/guides/waffle-testing.html)
  * [Better Programming Hub](https://betterprogramming.pub/the-complete-hands-on-hardhat-tutorial-9e23728fc8a4)
  * [Code Eater (Hindi)](https://www.youtube.com/watch?v=vuqhHOx6188&list=PLgPmWS2dQHW9mucRpDVe16j9Qn74ZXqcD&index=5)
  * [Foundry](https://github.com/foundry-rs/foundry)
  * [Tenderly](https://tenderly.co/)

* [ERC Standards]()
  * [Token Standards](https://ethereum.org/en/developers/docs/standards/tokens/)ERC20, ERC721, ERC777, ERC1155, ERC4626, BEP20
  * Other Standards: [ERC2981](https://eips.ethereum.org/EIPS/eip-2981)

* [Openzeppelin Helper Libraries/Contracts](https://github.com/OpenZeppelin/openzeppelin-contracts)

* Upgradeable Contracts
  * [Smart Contract Programmer - Upgradeable Contracts](https://www.youtube.com/watch?v=JgSj7IiE4jA&t=157s)
  * [Smart Contract Programmer - Risks of Upgradeable Contracts](https://www.youtube.com/watch?v=XmxfB5JOt1Q&t=3s)
  * [Different Proxy Patterns - EIPs 897, 1822, 1967, 1538, 2535](https://ethereum-blockchain-developer.com/110-upgrade-smart-contracts/00-project/)

* Attack Vectors
  * [Secureum Security Pitfalls 101](https://secureum.substack.com/p/security-pitfalls-and-best-practices-101?s=r)
  * [Secureum Security Pitfalls 201](https://secureum.substack.com/p/security-pitfalls-and-best-practices-201?s=r)
  * [SWC Registry](https://swcregistry.io/)
  * [Smart Contract Programmer - Hack Solidity](https://www.youtube.com/watch?v=4Mm3BCyHtDY&list=PLO5VPQH6OWdWsCgXJT9UuzgbC8SPvTRi5)
  * [Kaden: Smart Contract Attack Vectors](https://github.com/KadenZipfel/smart-contract-attack-vectors)

* [CTFs](https://github.com/blockthreat/blocksec-ctfs)
  * [Ethernaut](https://ethernaut.openzeppelin.com/)
  * [Capture The Ether](https://capturetheether.com/)
  * Read Walkthroughs

* DeFi
  * [Finematics - DeFi](https://www.youtube.com/watch?v=pWGLtjG-F5c&list=PLjrTIwaNiTwn39tg3sR_bPBWGHoznv47D)
  * [Smart Contract Programmer - DeFi](https://www.youtube.com/watch?v=qB2Ulx201wY&list=PLO5VPQH6OWdX-Rh7RonjZhOd9pb9zOnHW)
  * Well known protocols: Uniswap v2/v3, Compound, Curve, Aave, Balancer.
  * [Stablecoins](https://blog.chain.link/what-are-stablecoins/) => [Algorithmic Stablecoins](https://cointelegraph.com/altcoins-for-beginners/a-beginner-s-guide-on-algorithmic-stablecoins)
  * Staking Rewards, Vaults

* DeFi Attack Vectors
  * Flash Loan => Price Oracle Manipulation
  * Front-Running => Sandwich attacks
  * Rug Pulls => Unlimited Token Allowance

* [CTFs](https://github.com/blockthreat/blocksec-ctfs)  
  * [Damn Vulnerable DeFi](https://www.damnvulnerabledefi.xyz/)
  * Read Walkthroughs

* Postmortems
  * [Immunefi](https://medium.com/@immunefi)
  * [BlockSec](https://blocksecteam.medium.com/)
  * [SlowMist](https://slowmist.medium.com/)
  * [Rekt News](https://rekt.news/)
  * [PeckShield](https://twitter.com/peckshield)
  * [Mudit Gupta](https://twitter.com/mudit__gupta)
  * [Samczun](https://twitter.com/samczsun)

* Report Reading
  * [Secureum Audit Findings 101](https://secureum.substack.com/p/audit-findings-101?s=r)
  * [Secureum Audit Findings 201](https://secureum.substack.com/p/audit-findings-201?s=r)
  * Trail of Bits, Consensys, Openzeppelin, QuillAudits

* Security Standards & Checklists
  * [Rari-Capital Solcurity](https://github.com/Rari-Capital/solcurity)
  * [SCSVS](https://github.com/securing/SCSVS)

* Tools
  * [VS Code IDE](https://code.visualstudio.com/)
  * [Slither](https://github.com/crytic/slither)
  * [Mythril](https://github.com/ConsenSys/mythril)
  * [Mythx](https://mythx.io/)
  * [Echidna](https://github.com/crytic/echidna)
  * [Manticore](https://github.com/trailofbits/manticore)
  * [Surya](https://github.com/ConsenSys/surya)
  * [Scribble](https://github.com/ConsenSys/scribble)
  * [BlockSec ETH/BSC Tx Analysis](https://versatile.blocksecteam.com/tx) 
  * [ethtx ETH Tx Analysis](https://ethtx.info/)
  
* Continue Learning
  * [Ethereum Yellow Paper](https://github.com/ethereum/yellowpaper)
  * [Ethereum Improvement Proposals (EIPs)](https://eips.ethereum.org/)
  * [Eth Research](https://ethresear.ch/)
  * NewsLetters - Blockthreat, HashingBits
  * Communities
    * Immunefi, Secureum, Blockchain Pentesting( discord )  
    * Eth Security Community (Telegram)
  * Be Active on Twitter


* Knowledge Base
  * [Inline Assembly](https://docs.soliditylang.org/en/v0.8.13/assembly.html)
  * [Opcodes](https://www.ethervm.io/)
