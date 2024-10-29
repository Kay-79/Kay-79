<h1 align="center">Hi 👋, I'm Kay</h1>
<h3 align="center">I'm a Blockchain Developer. Every day is a learning day for me.</h3>

-   🔭 I’m currently working as a freelance **blockchain developer.**

-   🌱 I’m currently learning **Smart Contracts development.**

-   👀 Fun fact **If i don't know about something, I don't know it today. But i'll learn it and implement in my code.**

### Socials

<p align="center">
  <a href="https://monkeytype.com/profile/Kay-79"><img src="https://img.shields.io/badge/Monkeytype-gray?style=for-the-badge&logo=monkeytype&logoColor=white"></a>
  <a href="https://duolingo.com/profile/Kay-79"><img src="https://img.shields.io/badge/Duolingo-gray?style=for-the-badge&logo=duolingo&logoColor=white"></a>
</p>

### About me

```solidity
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.28;

contract Profile {
    string public name = "Kay";
    string public pronouns = "He | Him";
    string public currentFocus = "Web3 / Smart Contract / Dapp / EVM";

    string[] internal skills;
    string[] internal langs;

    function getSkills() public returns (string[] memory) {
        skills = ["git", "Web3", "Smart contract", "Hardhat", "Front Running"];
        return skills;
    }

    function getLangs() public returns (string[] memory) {
        langs = ["JavaScript", "TypeScript", "Solidity", "Rust", "Python", "AutoIt"];
        return langs;
    }

    function fun() public pure returns (string memory) {
        return
            "If i don't know about something, I don't know it today. But i'll learn it and implement in my code.";
    }
}
```
