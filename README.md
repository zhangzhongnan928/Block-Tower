# Block Tower: Dynamic Blockchain Tower Building

**Table of Contents**

1. [Introduction](#introduction)
2. [Game Overview](#game-overview)
3. [Game Mechanics](#game-mechanics)
   - [1. Tower Creation and Building](#1-tower-creation-and-building)
   - [2. Block Strength](#2-block-strength)
   - [3. Entering and Exiting](#3-entering-and-exiting)
   - [4. Tower Battles](#4-tower-battles)
   - [5. Battle Consequences](#5-battle-consequences)
   - [6. Strategic Elements](#6-strategic-elements)
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

**Block Tower: Dynamic Blockchain Tower Building** is an innovative blockchain-based game that combines strategic tower building with real-world cryptocurrency market dynamics. Players engage in constructing towers by purchasing blocks with various whitelisted ERC20 tokens, participate in battles against other towers, and strategize to maximize their rewards through market movements and game mechanics.

---

## Game Overview

- **Genre:** Strategy, Blockchain, Multiplayer
- **Platform:** **Base Blockchain** (utilizing ERC20 tokens and smart contracts)
- **Objective:** Build the tallest and strongest tower, engage in battles, and strategically manage your tower to maximize rewards.

---

## Game Mechanics

### 1. Tower Creation and Building

- **Open Participation:** Any player can start a new tower or contribute to existing towers by purchasing blocks.
- **Block Purchase:**
  - Blocks are purchased using ERC20 tokens from a **whitelisted list**.
  - Initially, the whitelist is managed by the developer; over time, governance will be passed to the players.
  - The price of blocks increases according to a bonding curve mechanism, making each subsequent block more expensive.
- **Token Selection:**
  - Players can choose different ERC20 tokens for each block from the whitelisted tokens, considering potential price movements and market trends.

### 2. Block Strength

- **Initial State:** All blocks start as **Neutral**.
- **Strength Categories:**
  - **Very Strong**
  - **Strong**
  - **Neutral**
  - **Weak**
  - **Very Weak**
- **Determining Strength:**
  - The strength of each block changes based on the price fluctuations of the ERC20 token used to create it.
  - Positive price movement increases block strength; negative movement decreases it.
  - Strength affects the tower's overall value and performance in battles.

### 3. Entering and Exiting

- **Entering the Game:**
  - Players enter by purchasing blocks in any tower.
  - Early entry is advantageous due to lower block prices.
- **Exiting the Game:**
  - Players can exit by removing their blocks.
  - Upon exiting, they claim the current value of their block.
- **Profit Mechanism:**
  - Profits for exiting players are funded by new players purchasing subsequent blocks.
  - The bonding curve ensures that early investors can profit as block prices increase.

### 4. Tower Battles

- **Eligibility:**
  - Towers reaching **level 20** (having 20 blocks) become eligible for battles.
- **Initiating Battles:**
  - Eligible towers can challenge other eligible towers.
  - Battles are mutual agreements or can be randomly matched.
- **Battle Duration:**
  - Each battle lasts for **10 minutes**.
- **Victory Conditions:**
  - The tower with the **highest total value** at the end of the battle wins.
  - Total value is calculated based on the current strength and market value of all blocks.

### 5. Battle Consequences

- **Token Swap Mechanism:**
  - Upon losing a battle, **20%** of the value from each block of the losing tower is automatically used to purchase the corresponding tokens of the winning tower's blocks via **Uniswap on Base** on a **1:1 basis**.
    - *Example:* If Block 1 of the losing tower contains $100 worth of Token A, then $20 is used to buy Token B (the token of Block 1 in the winning tower).
  - This process is repeated for each block in the losing tower.
- **Holding of Swapped Tokens:**
  - The acquired tokens are **held within the winning tower**.
  - These tokens are **not** allocated to block holders proportionally.
- **Claiming Winnings:**
  - The accumulated swapped tokens can only be claimed by the **last block holder** when they remove the final block of the tower.
  - This incentivizes players to acquire the last block and decide the optimal time to dismantle the tower.

### 6. Strategic Elements

- **Market Engagement:**
  - Players are encouraged to monitor and potentially influence the market prices of their chosen tokens.
- **Tower Ownership:**
  - Owning multiple blocks, especially the last block, offers strategic advantages.
- **Risk Management:**
  - Players must balance the risks of tower battles and market volatility with the potential rewards.
- **Governance Participation:**
  - Players can participate in the governance of the game by voting on the whitelist of allowed tokens using the **Block Tower Token**.
- **Timing and Exit Strategy:**
  - Deciding when to remove the last block is crucial, as it determines when accumulated winnings are claimed.

---

## Game Flow

### 1. Tower Building Phase

- **Block Purchase:**
  - Players buy blocks using whitelisted ERC20 tokens.
  - Early blocks are cheaper due to the bonding curve pricing.
- **Token Selection:**
  - Strategic selection of tokens from the whitelist based on market analysis.
- **Tower Growth:**
  - Towers grow as more blocks are added, increasing eligibility for battles.

### 2. Pre-Battle Phase

- **Preparation:**
  - As towers approach level 20, players prepare for potential battles.
- **Strategizing:**
  - Players may strengthen their tower by adding valuable blocks or enhancing existing ones.
  - Collaboration or competition among block holders to maximize tower strength.

### 3. Battle Phase

- **Initiation:**
  - Towers initiate battles with other eligible towers.
- **Duration:**
  - Battles last for 10 minutes, during which tower values can fluctuate.
- **Market Influence:**
  - Players might engage in market activities to boost their token prices, thereby increasing their tower's value.
- **Outcome:**
  - The tower with the highest total value at the end of the battle wins.

### 4. Post-Battle Phase

- **Token Swap Execution:**
  - 20% of the value from each block of the losing tower is swapped for the winning tower's tokens via Uniswap on Base.
- **Accumulation of Winnings:**
  - Swapped tokens are held within the winning tower, accumulating over time as the tower wins more battles.
- **No Immediate Claiming:**
  - Current block holders cannot claim these tokens; they remain locked within the tower.

### 5. Tower Death and Claiming Winnings

- **Tower Death:**
  - Occurs when the last block is removed from the tower.
- **Last Block Holder's Reward:**
  - The player who removes the final block receives **all** the accumulated swapped tokens held within the tower.
- **Strategic Decision:**
  - The last block holder must decide the optimal time to dismantle the tower to maximize rewards.

### 6. Continuous Gameplay

- **Entering and Exiting:**
  - Players can join or leave towers at any time by purchasing or removing blocks.
- **Dynamic Environment:**
  - Continuous market fluctuations and player actions create a dynamic and strategic gaming experience.
- **Ongoing Battles:**
  - Towers can engage in multiple battles, accumulating more winnings or risking losses.

---

## Strategic Implications

- **Tower Control:**
  - Players may attempt to acquire multiple blocks to gain greater control over the tower's fate.
- **Market Strategies:**
  - Monitoring and influencing token prices can significantly impact tower strength and battle outcomes.
- **Governance Participation:**
  - Holding **Block Tower Tokens** allows players to vote on the whitelist of allowed tokens, influencing game dynamics.
- **Risk vs. Reward:**
  - Holding the last block comes with risks, such as potential tower loss in battles, but offers substantial rewards.
- **Collaboration and Competition:**
  - Players might form alliances to strengthen their towers or compete to control the last block.
- **Exit Timing:**
  - Deciding when to remove the last block requires careful consideration of accumulated winnings and potential future gains.

---

## Additional Considerations

### 1. Whitelisted Tokens

- **Initial Whitelist:**
  - The initial list of allowed tokens comes from the top tokens on **Base Uniswap**.
- **Governance Transition:**
  - Initially managed by the developer, the whitelist management will be passed to the players over time.
- **User Voting:**
  - Players vote on adding or removing tokens from the whitelist using the **Block Tower Token**, an ERC20 token on Base distributed as reward points to all users.

### 2. Block Tower Token and Governance

- **Block Tower Token (BTT):**
  - An ERC20 token on the Base blockchain.
  - Distributed as reward points to players based on their participation and achievements in the game.
- **Governance Mechanism:**
  - BTT holders can vote on proposals, such as which tokens to include in the whitelist.
  - This democratic process empowers the community to shape the game's future.

### 3. Battle Cooldown

- **Purpose:**
  - Prevents towers from being constantly attacked.
- **Mechanism:**
  - After a battle, towers have a cooldown period during which they cannot engage in new battles.

### 4. Balanced Matchmaking

- **Fairness:**
  - Ensures towers are matched with opponents of similar strength and value.
- **Criteria:**
  - Matching based on tower level, total value, and block strengths.

### 5. Anti-Manipulation Measures

- **Market Integrity:**
  - Implements safeguards to detect and prevent artificial token price manipulation during battles.
- **Monitoring:**
  - Automated systems to flag suspicious activities.

### 6. Tower Alliances

- **Collaboration:**
  - Allows players to form alliances, pooling resources to build stronger towers.
- **Shared Goals:**
  - Alliance members work together to enhance tower strength and strategize for battles.

### 7. Leaderboards

- **Recognition:**
  - Showcases towers with the most victories, highest values, and tallest heights.
- **Competition:**
  - Encourages friendly competition among players.

### 8. Token Diversity Bonus

- **Incentive:**
  - Encourages use of a variety of ERC20 tokens from the whitelist.
- **Mechanism:**
  - Towers with diverse tokens may receive bonuses, such as increased block strength or reduced battle cooldowns.

### 9. Liquidity and Slippage

- **Market Considerations:**
  - Ensures sufficient liquidity on Uniswap on Base for token swaps to minimize slippage.
- **Limitations:**
  - Parameters set to handle low-liquidity situations, preventing excessive market impact.

### 10. Transparency and Fair Play

- **Smart Contracts:**
  - All game mechanics are encoded in transparent, open-source smart contracts.
- **Player Trust:**
  - Transparency ensures players understand the rules and that the game operates fairly.

### 11. Regulatory Compliance

- **Legal Considerations:**
  - Compliance with financial regulations related to token swaps and prize distributions.
- **Responsible Gaming:**
  - Measures in place to prevent illicit activities and protect players.

### 12. Player Education

- **Guidance:**
  - Provides clear instructions and information about game mechanics, risks, and rewards.
- **Support:**
  - Resources available to help players make informed decisions.

---

## Conclusion

**"Block Tower: Dynamic Blockchain Tower Building"** offers an engaging blend of strategic gameplay and real-world market dynamics. By incorporating ERC20 tokens and blockchain technology on the Base blockchain, players experience a unique gaming environment where their decisions have tangible financial implications. The game's mechanics encourage strategic thinking, collaboration, and active market participation, making it a compelling experience for both gamers and cryptocurrency enthusiasts.

---

## Disclaimer

*This game involves the use of real ERC20 tokens and engagement with cryptocurrency markets. Players should be aware of the inherent risks associated with token investments, including market volatility and potential financial loss. The game is designed for entertainment purposes and should not be considered as financial advice or a guaranteed investment opportunity. Players are encouraged to conduct their own research and exercise caution when participating. The developers are not responsible for any losses incurred during gameplay.*

---
