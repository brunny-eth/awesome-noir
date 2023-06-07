# Awesome Noir

A curated list of resources for learning and programming in Noir.

[![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)
[![Twitter](https://img.shields.io/twitter/url/https/twitter.com/Noir.svg?style=social&label=Follow%20%40Noir)](https://twitter.com/NoirLang)
[![Discord](https://img.shields.io/discord/563037431604183070?logo=discord)](https://discord.gg/aztec)

## Contents

- [Official Resources](#official-resources)
- [Talks & Workshops](#talks--workshops)
- [Get Coding](#get-coding)
  - [Dev Tools](#dev-tools)
  - [Boilerplates](#boilerplates)
  - [Libraries](#libraries)
- [Projects](#projects)
  - [Authentication](#authentication)
  - [Education](#education)
  - [Gaming](#gaming)
  - [Governance](#governance)
- [Contribute](#contribute)

---

## Official Resources

- [Docs](https://noir-lang.org/)
- [GitHub](https://github.com/noir-lang/noir)
- [Forum](https://discourse.aztec.network/c/noir/7)
- [noir-starter repo](https://github.com/noir-lang/noir-starter)

## Talks & Workshops

- [10 mins] [Writing Circuits with Noir](https://www.youtube.com/watch?v=I5M8LhOECpM&t=2879s) ([Source Code](https://github.com/vezenovm/basic_mul_noir_example))
  - Nargo setup
  - Basic Noir syntax
  - Noir interactions in TypeScript
- [20 mins] [Painless Zero-Knowledge Circuitry with Noir at ETHDam](https://www.youtube.com/watch?v=5KLTroMcldg&list=PLc5OGwyCUIhXny_mY4NPE5JfYNcTh8jUs&index=28)
  - Introduction to Noir
  - Simple demo and test
- [20 mins] [Private Value Transfer in 10 Lines](https://www.youtube.com/watch?v=wYqqXas8_O4) ([Source Code](https://github.com/vezenovm/simple_shield))
  - Tornado-like private asset transfer using Merkle proofs
- [25 mins] [Noir as a Smart Contract Language](https://www.youtube.com/watch?v=tYdUaCbACtk)
  - Noir as the smart contract language for the Aztec rollup 
  - Noir smart contracts
- [1 hr] [Circuit Safety and an Introduction to Noir](https://www.youtube.com/watch?v=rLvu61DA-hk)
  - Common circuit bugs
  - Proving system vulnerabilities
  - Unconstrained functions
- [2 hrs] [ZK HACK III - Introduction to Noir](https://www.youtube.com/watch?v=5CziMfChveY) ([Souce Code](https://github.com/joss-aztec/quadratic_voting_noir))
  - Code-together: Quadratic Voting
- [1.5 hrs] [Sudoku in Noir](https://drive.google.com/file/d/1D4XCdiIZVjUW1JHDoMW3pG-15mgjMm9E/) ([Source Code](https://github.com/guipublic/crypdoku))
- [Video Series] [BattleZips-Noir](https://www.youtube.com/playlist?list=PLWACGbvIsEgnR2aUCr9i-PpmTVhF5Zuik) ([Source Code](https://github.com/BattleZips/BattleZips-Noir))
  - Walkthrough of building an on-chain Battleships game in Noir

## Get Coding

### Dev Tools

- [Noir Editor](https://noir-lang.github.io/noir-cra/)   - Browser IDE ([Souce Code](https://github.com/noir-lang/noir-cra))
- [VSCode Extension](https://marketplace.visualstudio.com/items?itemName=noir-lang.noir-programming-language-syntax-highlighter) - Syntax highlight ([Source Code](https://github.com/noir-lang/vscode-noir))
- [Vim Plugin](https://github.com/Louis-Amas/noir-vim-support) - Syntax highlight
- [Emacs Plugin](https://github.com/hhamud/noir-mode) - Syntax highlight
- [hardhat-noir](https://www.npmjs.com/package/hardhat-noir) - Hardhat plugin ([Source Code](https://github.com/spalladino/hardhat-noir))

### Boilerplates

- [nplate](https://github.com/whitenois3/nplate) - Minimalist template
- [noir-hardhat-template](https://github.com/hooperben/noir-hardhat-template) - Hardhat template
- [noir-starter](https://github.com/noir-lang/noir-starter) - Template repository containing example projects using Noir (Next.js + Hardhat, Foundry, etc.)

### Libraries

- [Standard Library](https://github.com/noir-lang/noir/tree/master/noir_stdlib)
- [BigInt](https://github.com/okuyiga/noir-bigint/tree/master)
- [Ecrecover](https://github.com/colinnielsen/ecrecover-noir/tree/main) - a library to verify an ECDSA signature and return the source Ethereum address 
- [Sparse Merkle Tree Verifier](https://github.com/vocdoni/smtverifier-noir/tree/main)

## Projects

A curated list of projects powered by Noir.

### Authentication

- Anonymous proof of token ownership on Aztec (for token-gated access)
  - [Sequi](https://github.com/sequi-xyz)
  - [Cyclone](https://github.com/TalDerei/cyclone)

### Education

- [circuit-examples](https://github.com/thor314/circuit-examples) - Dot Product & Merkle Proof in Circom, Noir and RISC0
- [Mastermind](https://github.com/vezenovm/mastermind-noir) - Mastermind in Noir

### Gaming

- [BattleZips](https://battlezips.com/) ([Source Code](https://github.com/BattleZips/BattleZips-Noir)) - On-chain Battleship
- [Sudoku, Wordle, and Trivia](https://github.com/ruizehung/Zero-Knowledge-Sudoku-Wordle-Trivia) - Sudoku, Wordle, and Trivia games
- [ZCaptcha](https://github.com/signorecello/zcaptcha) - A ZK version of Captcha

### Governance

- [MeloCafe](https://github.com/MeloCafe) - Anonymous on-chain voting

## Contribute

Propose link additions by visiting [README.md](./README.md) and click the "pen" icon in the top right corner. Make changes to the file and follow the instructions to create a pull request.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)
