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
  - This process is repeated for each block in the losing tower.
- **Holding of Swapped Tokens:**
  - The acquired tokens are **held within the winning tower**.
  - These tokens are **not** allocated to block holders proportionally.
- **Claiming Winnings:**
  - The accumulated swapped tokens can only be claimed by the **last block holder** when they remove the final block of the tower.
  - This incentivizes players to acquire the last block and decide the optimal time to dismantle the tower.

### 7. Strategic Elements

- **Market Engagement:**
  - Players are encouraged to monitor and potentially influence the market prices of their associated tokens.
- **Token Association Strategy:**
  - Choosing which token to associate with a block is a strategic decision based on expected token performance.
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
  - Players buy blocks using ETH on Base.
  - Early blocks are cheaper due to the bonding curve pricing.
- **Token Association:**
  - Players associate their blocks with ERC20 tokens from the whitelist.
  - The amount of tokens associated is calculated based on the ETH price at the time of block addition.
    - *Example:* If 1 ETH = 100 Token A at the time of purchase, and the player spends 0.5 ETH on the block, the block is associated with 50 Token A.
- **Tower Growth:**
  - Towers grow as more blocks are added, increasing eligibility for battles.

### 2. Pre-Battle Phase

- **Preparation:**
  - As towers approach level 20, players prepare for potential battles.
- **Strategizing:**
  - Players may strengthen their tower by associating blocks with tokens expected to appreciate.
  - Collaboration or competition among block holders to maximize tower strength.

### 3. Battle Phase

- **Initiation:**
  - Towers initiate battles with other eligible towers.
- **Duration:**
  - Battles last for **12 hours**, allowing ample time for strategic decisions.
- **Market Influence:**
  - Players might engage in market activities to boost their associated token prices, thereby increasing their tower's average value.
- **Player Actions:**
  - Players can enter or exit towers during battles, impacting the average value.
- **Outcome:**
  - The tower with the highest **average value per block** at the end of the battle wins.

### 4. Post-Battle Phase

- **Token Swap Execution:**
  - 20% of the **ETH value** from each block of the losing tower is swapped for the winning tower's associated tokens via Uniswap on Base.
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
  - Players can join or leave towers at any time by purchasing or removing blocks, even during battles.
- **Dynamic Environment:**
  - Continuous market fluctuations and player actions create a dynamic and strategic gaming experience.
- **Ongoing Battles:**
  - Towers can engage in multiple battles, accumulating more winnings or risking losses.

---

## Strategic Implications

- **Token Selection Strategy:**
  - Players must carefully choose which tokens to associate with their blocks based on market expectations.
- **Market Timing:**
  - Associating blocks with tokens expected to appreciate during battles can enhance block strength.
- **Tower Control:**
  - Acquiring multiple blocks increases influence over the tower's performance and decisions.
- **Risk vs. Reward:**
  - Balancing the potential gains from high-risk tokens against the stability of more predictable ones.
- **Collaboration and Competition:**
  - Forming alliances to strengthen towers or competing for control of the last block.
- **Exit Timing:**
  - Strategic removal of blocks can impact the tower's average value during battles.
- **Battle Strategies:**
  - Exiting low-value blocks during battles to increase the tower's average value.
  - Encouraging other players to associate their blocks with strong tokens.

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
  - Ensures towers are matched with opponents of similar average block values.
- **Criteria:**
  - Matching based on tower level, average value per block, and block strengths.

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
  - Showcases towers with the most victories, highest average values, and tallest heights.
- **Competition:**
  - Encourages friendly competition among players.

### 8. Token Diversity Bonus

- **Incentive:**
  - Encourages association with a variety of ERC20 tokens from the whitelist.
- **Mechanism:**
  - Towers with diverse token associations may receive bonuses, such as increased block strength or reduced battle cooldowns.

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

**"Block Tower: Simplified Blockchain Tower Building"** offers an engaging blend of strategic gameplay and real-world market dynamics, now streamlined for simplicity. By using ETH on Base for block transactions and allowing token associations that record the ERC20 token contract address and amount based on the price per ETH at the time of block addition, players experience a unique gaming environment where their decisions have tangible financial implications. The game's mechanics encourage strategic thinking, market analysis, and active participation, making it a compelling experience for both gamers and cryptocurrency enthusiasts.

---

## Disclaimer

*This game involves the use of real ETH and ERC20 tokens, engaging with cryptocurrency markets. Players should be aware of the inherent risks associated with token investments, including market volatility and potential financial loss. The game is designed for entertainment purposes and should not be considered as financial advice or a guaranteed investment opportunity. Players are encouraged to conduct their own research and exercise caution when participating. The developers are not responsible for any losses incurred during gameplay.*

---
