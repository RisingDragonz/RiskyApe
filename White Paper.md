### White Paper
**Introduction:** Risky Ape is a Solana blockchain-based game of chance that will allow players to bet Solana and SPL tokens. The game involves the player guessing a number between 1 and 3 thus entering a 'triple or nothing' situation. Deposits to play the game are charged a 5% transaction fee which is distributed as such:

⦁	95% to Risky Ape NFT holders

⦁	4% to the house reserve wallet

⦁	1% to the core development/marketing team.

These distributions will be processed daily. If the house reserve wallet grows to a sufficient size then these payments will be suspended and the remaining 4% will also be distributed to Risky Ape NFT holders.

**Core Game:** The core game has a retro/arcade game aesthetic with the only character being the Risky Ape mascot. The ape states "I'm thinking of a number between 1 and 3..." to which the player can then select their number of choice and stake their bet.
The chance of winning this game is 33.33%. However, the player will also have the option to select the "Kong It" button which will reduce their chance of winning to 1% whilst also increasing their win payout to be 10,000%. 

**Simplified Event Flow:** When a player chooses their guess and bet amount, this data is used to build a Solana transaction which will immediately be pushed to the Solana network. The important information that each transaction will store includes the total amount betted; the players number of choosing and the timestamp. This data is extracted from the solana network by our off-chain back end server which will deduct the 5% deposit fee and then compare the players chosen number to the corresponding 'correct' number. 
If the player number does not match the 'correct' number then the back end server will push a new transaction, containing the correct guess, to the Solana blockchain. This data will be extracted by the front end and display a loss to the player.
If the player number does match the 'correct' number then the back end server will push a new transaction containing the triple the players bet and the 'correct' number. The front end will then display a win to the player and the won amount will be credited to their Solana wallet address. The entire process will take an estimated average of 5-10 seconds when accounting for Solana and back end server delays. 

**Responsible Gambling:** The team at Risky Ape feels that we hold a large responsibility to the well-being of our players. After careful consideration we have decided that the best course of action is to implement a pop-up after 20 bets have taken place. This popup will ask the player if they would like to take a break and offer a link to gambling addiction organisations. We are keen to hear more suggestions from the community on this matter.

**Risky Ape NFT:** Every Risky Ape NFT will be identical and acts primarily as certification of share ownership. The NFT art will be the Risky Ape mascot on a dark background. The NFT has no additional attributes and has a 5% secondary market fee. The mint price is set at 1 Solana and the total supply is 500.
Following a successful mint we intend to invest the raised funds back into development of the Risky Ape game. This will include web hosting to handle increased traffic, new game development and paid advertising to ensure a constant stream of new players that will provide holders of our NFT with continued fees.
Every Risky Ape NFT will be entitled to the above stated share of all future games launched in association with the Risky Ape game. Other than monetary value we also feel that we should mention that each NFT holder has the right to our commitment and word that we will always do right by the community. The Risky Ape community will always have the final say on future decisions about the project.

**Future Developments:** The Risky Ape team has decided to release the Risky Ape number guessing game first but other games are already planned and will be added once we feel the first game is fully optimized and adopted by the community. 
Multi-chain gaming is an idea we would like to work towards whilst using the solana blockchain as a quick backbone network. This would mean acceptance of other cryptocurrencies such as Bitcoin, Ethereum and USDC/USDT. Payouts from this form of deposit could be processed as Solana or in the cryptocurrency of choice.
