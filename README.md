<h1 align="center">Hi 👋, I'm Kay</h1>
<h3 align="center">I'm a Blockchain Developer. Every day is a learning day for me.</h3>

-   🔭 I’m currently working as a freelance **blockchain developer.**

-   🌱 I’m currently learning **Smart Contracts development.**

-   👀 Fun fact **If i don't know about something, I don't know it today. But i'll learn it and implement in my code.**

### Socials

<p align="center">
  <a href="https://monkeytype.com/profile/Kay-79"><img src="https://img.shields.io/badge/Monkeytype-gray?style=for-the-badge&logo=monkeytype&logoColor=white"></a>
  <a href="https://leetcode.com/u/Kay-79/"><img src="https://img.shields.io/badge/Leetcode-gray?style=for-the-badge&logo=leetcode&logoColor=white"></a>
  <a href="https://duolingo.com/profile/Kay-79"><img src="https://img.shields.io/badge/Duolingo-gray?style=for-the-badge&logo=duolingo&logoColor=white"></a>
</p>

### About me

```solidity
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.30;

contract Profile {
    string public name = "Kay";
    string public pronouns = "He | Him";
    string public currentFocus = "Web3 / Smart Contract / Dapp / EVM";

    string[] internal skills;
    string[] internal langs;
    string[] internal frameworks;

    function getSkills() public returns (string[] memory) {
        skills = ["git", "Agile/Scrum", "CI/CD"];
        return skills;
    }

    function getFrameworks() public returns (string[] memory) {
        frameworks = ["Next.js", "Redis", "PostgreSQL", "Tailwind CSS", "Hardhat", "Ethers.js", "Foundry"];
        return frameworks;
    }

    function getLangs() public returns (string[] memory) {
        langs = ["TypeScript", "Solidity", "JavaScript", "Rust", "Move", "Python", "AutoIt"];
        return langs;
    }

    function fun() public pure returns (string memory) {
        return
            "If i don't know about something, I don't know it today. But i'll learn it and implement in my code.";
    }
}
```
