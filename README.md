# Block Tower: Simplified Blockchain Tower Building

**Table of Contents**

1. [Introduction](#introduction)
2. [Game Overview](#game-overview)
3. [Game Mechanics](#game-mechanics)
   - [1. Tower Creation and Building](#1-tower-creation-and-building)
   - [2. Block Association with Tokens](#2-block-association-with-tokens)
   - [3. Block Strength](#3-block-strength)
   - [4. Entering and Exiting](#4-entering-and-exiting)
   - [5. Tower Battles](#5-tower-battles)
   - [6. Battle Consequences](#6-battle-consequences)
   - [7. Strategic Elements](#7-strategic-elements)
4. [Game Flow](#game-flow)
   - [1. Tower Building Phase](#1-tower-building-phase)
   - [2. Pre-Battle Phase](#2-pre-battle-phase)
   - [3. Battle Phase](#3-battle-phase)
   - [4. Post-Battle Phase](#4-post-battle-phase)
   - [5. Tower Death and Claiming Winnings](#5-tower-death-and-claiming-winnings)
   - [6. Continuous Gameplay](#6-continuous-gameplay)
5. [Strategic Implications](#strategic-implications)
6. [Additional Considerations](#additional-considerations)
   - [1. Whitelisted Tokens](#1-whitelisted-tokens)
   - [2. Block Tower Token and Governance](#2-block-tower-token-and-governance)
   - [3. Battle Cooldown](#3-battle-cooldown)
   - [4. Balanced Matchmaking](#4-balanced-matchmaking)
   - [5. Anti-Manipulation Measures](#5-anti-manipulation-measures)
   - [6. Tower Alliances](#6-tower-alliances)
   - [7. Leaderboards](#7-leaderboards)
   - [8. Token Diversity Bonus](#8-token-diversity-bonus)
   - [9. Liquidity and Slippage](#9-liquidity-and-slippage)
   - [10. Transparency and Fair Play](#10-transparency-and-fair-play)
   - [11. Regulatory Compliance](#11-regulatory-compliance)
   - [12. Player Education](#12-player-education)
7. [Conclusion](#conclusion)
8. [Disclaimer](#disclaimer)

---

## Introduction

**Block Tower: Simplified Blockchain Tower Building** is an innovative blockchain-based game that combines strategic tower building with real-world cryptocurrency market dynamics. Players engage in constructing towers by purchasing blocks using **ETH on Base**, associate their blocks with various whitelisted ERC20 tokens, and participate in battles against other towers. They strategize to maximize their rewards through market movements and game mechanics.

---

## Game Overview

- **Genre:** Strategy, Blockchain, Multiplayer
- **Platform:** **Base Blockchain** (utilizing ETH and ERC20 tokens)
- **Objective:** Build the tallest and strongest tower, engage in battles, and strategically manage your tower to maximize rewards.

---

## Game Mechanics

### 1. Tower Creation and Building

- **Open Participation:** Any player can start a new tower or contribute to existing towers by purchasing blocks.
- **Block Purchase:**
  - Blocks are purchased using **ETH on Base**.
  - The price of blocks increases according to a **bonding curve** mechanism, making each subsequent block more expensive.
- **Block Removal:**
  - Players can remove their blocks at any time, receiving ETH based on the bonding curve.

### 2. Block Association with Tokens

- **Token Association:**
  - After purchasing a block with ETH, players can **associate** their block with an ERC20 token from a **whitelisted list**.
- **Association Details:**
  - **Recorded Information:**
    - **ERC20 Token Contract Address**
    - **Amount of Tokens:** Calculated based on the price per ETH at the time the block is added.
  - This means that the ETH used to purchase the block is notionally converted into the associated ERC20 token amount, based on the current exchange rate at the time of purchase.
- **Purpose of Association:**
  - The associated token's performance influences the block's strength over time.
- **Flexibility:**
  - Players can choose different tokens for each block or associate multiple blocks with the same token.

### 3. Block Strength

- **Initial State:** All blocks start with a strength level based on the initial token amount.
- **Strength Categories:**
  - **Very Strong**
  - **Strong**
  - **Neutral**
  - **Weak**
  - **Very Weak**
- **Determining Strength:**
  - The strength of each block changes based on the **price fluctuations** of its associated ERC20 token since the block was added.
  - **Calculation:**
    - **Block Strength Value** = Current Value of Associated Tokens (Amount × Current Token Price)
    - The initial amount and token price are recorded at the time of block addition.
    - As the token price changes, the block's strength adjusts accordingly.
- **Impact on Gameplay:**
  - Strength affects the tower's overall value and performance in battles.

### 4. Entering and Exiting

- **Entering the Game:**
  - Players enter by purchasing blocks using ETH and associating them with tokens.
  - Early entry is advantageous due to lower block prices on the bonding curve.
- **Exiting the Game:**
  - Players can exit by removing their blocks.
  - Upon exiting, they receive ETH based on the current bonding curve price.
- **Profit Mechanism:**
  - Profits for exiting players are funded by new players purchasing subsequent blocks.
  - The bonding curve ensures that early investors can profit as block prices increase.

### 5. Tower Battles

- **Eligibility:**
  - Towers reaching **level 20** (having 20 blocks) become eligible for battles.
- **Initiating Battles:**
  - Eligible towers can challenge other eligible towers.
  - Battles are mutual agreements or can be randomly matched.
- **Battle Duration:**
  - Each battle lasts for **12 hours**.
- **Victory Conditions:**
  - The tower with the **highest average value per block** at the end of the battle wins.
    - **Average Value Calculation:** Total tower value divided by the number of blocks.
    - **Block Value:** Determined by the current value of the associated tokens.
- **Player Activity During Battle:**
  - Players can still enter or exit the tower during battles.
  - Exiting players' blocks are removed from the tower, affecting the average value.

### 6. Battle Consequences

- **Token Swap Mechanism:**
  - Upon losing a battle, **20%** of the **ETH value** from each block of the losing tower is automatically used to purchase the corresponding **associated tokens** of the winning tower's blocks via **Uniswap on Base** on a **1:1 basis**.
    - *Example:* If Block 1 of the losing tower has $100 worth of ETH, then $20 is used to buy Token B (the associated token of Block 1 in the winning tower).
  - This​⬤
