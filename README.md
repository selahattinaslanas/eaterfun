


<img width="1025" height="949" alt="image" src="https://github.com/user-attachments/assets/25f1c32b-a8d3-4e17-83c1-305b1e117b8b" />


<img width="1858" height="942" alt="image" src="https://github.com/user-attachments/assets/b3336c0c-0365-4902-8759-34b36dd5344c" />




# Eater.fun - Multiplayer P2E Game on Solana
First of all i have eater.fun domain but backend-frontend buying server is cost me hundreds of $ and i dont have that much money to spend on it so I created cloud flare to players test server on my computer thanks all

https://jean-dark-fit-wendy.trycloudflare.com


A multiplayer browser game where players compete in real-time and earn SOL by eating other players.

## 🎮 What It Is

Eater.fun is Agar.io meets blockchain. Players control cells, eat smaller players to steal their SOL balance, and compete for prize pools distributed every 30 minutes.

## 🚀 Live Demo

**Play now:** https://jean-dark-fit-wendy.trycloudflare.com

(Currently on Solana devnet - free to play with testnet SOL)

## ✨ Features

- **Real-time Multiplayer** - Smooth gameplay with Socket.io
- **Blockchain Integration** - Every transaction on Solana
- **Prize Pools** - Every player share rewards every 30 minutes according to their score (mass x playing time)
- **Skill-Based** - Win by strategy, not pay-to-win
- **Crypto Skins** - Bitcoin, Ethereum, Solana, Pepe, Doge, BNB
- **Early Exit Penalty** - 80% penalty keeps games competitive
- **Phantom Wallet** - Seamless Web3 integration

## 🛠️ Tech Stack

**Frontend:**
- JavaScript/HTML/CSS
- Socket.io-client for real-time communication
- Solana Web3.js for blockchain interactions
- Webpack for bundling

**Backend:**
- Node.js + Express
- Socket.io for WebSocket connections
- Solana Web3.js for transaction handling
- Custom Rust smart contract (Anchor framework)

**Blockchain:**
- Solana (Devnet)
- Custom on-chain program for game logic
- PDAs (Program Derived Addresses) for player accounts
- SPL Token standard

## 🎯 How It Works

1. **Entry** - Players pay 0.01-0.1 SOL to join a round
2. **Gameplay** - Eat food pellets and smaller players to grow
3. **Stealing** - When you eat a player, you steal their SOL balance
4. **Prize Pool** - 0.5% of each entry  and % 0.5 of each eating goes to prize pool
5. **Distribution** - Every 30 minutes, prize pool splits based on scores
6. **Withdrawal** - Players can exit anytime (with penalty if early)

## 💰 Tokenomics

**Entry Fees:**
- 98% goes to player's game balance
- 1.5% house fee
- 0.5% prize pool

**Early Exit:**
- 20% returned to player
- 64% to prize pool
- 16% house fee

**Eating Players:**
- 99.5% goes to eating player
- 0.5% to prize pool

## 🏗️ Architecture
```
Frontend (Client)
    ↓
Socket.io (Game Server) ← → Backend API ← → Solana Blockchain
    ↓                              ↓
Real-time Game State        Transaction Handling
```

## 📊 Current Status

- ✅ Live on Solana Devnet
- ✅ Fully functional multiplayer
- ✅ Real blockchain transactions
- ✅ Prize pool distribution working
- ✅ Phantom wallet integration
- 🔄 Testing phase - gathering player feedback
- 📅 Planning mainnet launch

## 🚧 Roadmap

**Phase 1 (Current):**
- [x] Core gameplay
- [x] Blockchain integration
- [x] Prize pool system
- [ ] 100+ active players

**Phase 2 (Next):**
- [ ] Move to mainnet
- [ ] Mobile optimization
- [ ] More skins and customization
- [ ] Tournament mode
- [ ] Referral system

**Phase 3 (Future):**
- [ ] NFT skins
- [ ] Governance token
- [ ] DAO for game decisions
- [ ] Cross-chain support

## 🎓 What I Learned

Building this taught me:
- Real-time multiplayer architecture
- Blockchain transaction handling at scale
- Race condition management
- Prize pool distribution algorithms
- WebSocket + blockchain synchronization

You can find gameplay video on my x account also.

## 📞 Contact

- **Twitter:** @eaterfungame
- **Demo:** https://jean-dark-fit-wendy.trycloudflare.com
- **Email:** selahattin.aslanas@gmail.com

all rights reserverd

Full code available for review to serious partners/investors
---# eaterfun
eaterfunporject
