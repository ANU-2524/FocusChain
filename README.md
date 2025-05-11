# 🚀 FocusChain

**FocusChain** is a real-time, blockchain-based attendance and focus tracking system designed to promote transparency, productivity, and accountability. It combines smart contract technology with real-time focus tracking (inspired by Yeolpumta) to deliver a modern attendance system.

---

## 🧭 Development Roadmap

### ✅ Phase 1: Project Setup & Planning (1–2 days)
- [x] Initialize Git repo (`focuschain`)
- [x] Plan app structure (`client`, `server`, `contracts`)
- [x] Create high-level architecture diagram
- [x] Choose Tech Stack:
  - Frontend: React Native (Expo) or React (Web)
  - Backend: Node.js + Express
  - Blockchain: Solidity + Hardhat + Polygon or Ethereum testnet
  - Database: MongoDB or Firebase (for off-chain data)

---

### 🧠 Phase 2: Learn & Prepare (up to 1 week)

#### Required Skills:

| Area       | Skills to Learn                                |
|------------|------------------------------------------------|
| Frontend   | React / React Native, state management, UI     |
| Backend    | Express, REST APIs, WebSockets                 |
| Blockchain | Solidity, Smart Contracts, Hardhat, Ethers.js |
| Realtime   | Socket.io / Firebase                           |
| Extras     | Git, .env config, MongoDB basics               |

---

### 🚀 Phase 3: Frontend – Focus App UI (1–2 weeks)

- [ ] Login/Register screen
- [ ] Focus Timer screen
  - Timer start/stop
  - Phone lock or background detection
- [ ] Attendance button (Check-in / Check-out)
- [ ] Real-time focus session updates
- [ ] Wallet connect (Metamask / WalletConnect)

---

### ⚙️ Phase 4: Backend Server + API (1–2 weeks)

- [ ] User authentication (JWT or sessions)
- [ ] `POST /check-in` → triggers smart contract
- [ ] WebSocket connection → real-time focus data
- [ ] MongoDB Schema:
  - Users
  - Focus sessions
  - Attendance logs
- [ ] Admin routes for dashboard analytics

---

### 🔗 Phase 5: Blockchain Smart Contracts (1–2 weeks)

- [ ] `AttendanceTracker.sol` contract
  - `markAttendance(address user, uint timestamp)`
  - `getAttendance(address user)`
- [ ] Optional: ERC20 token contract for rewards
- [ ] Deploy to local Hardhat → Polygon Mumbai testnet
- [ ] Integrate with frontend using Ethers.js

---

### 📡 Phase 6: Real-Time Functionality (5–7 days)

- [ ] Implement WebSocket server
- [ ] Track active users & focus duration in real-time
- [ ] Push updates to frontend dashboard

---

### 📊 Phase 7: Admin Dashboard (Optional)

- [ ] View online / checked-in / inactive users
- [ ] Total focus time per user
- [ ] Export logs (CSV/Excel)
- [ ] Analytics: streaks, session lengths, etc.

---

### 💰 Phase 8: Gamification (Optional)

- [ ] Reward system with ERC20 tokens
- [ ] Daily check-in streak rewards
- [ ] NFT badges (ERC721) for milestones

---

### 🚢 Phase 9: Testing & Deployment (1 week)

- [ ] Unit tests (contracts + backend)
- [ ] Host frontend (Vercel / Netlify / Expo Go)
- [ ] Host backend (Railway / Render)
- [ ] Deploy smart contracts to testnet/mainnet
- [ ] Security reviews (envs, contract audits)

---

### 🎉 Final Phase: Launch & Improve

- [ ] Collect user feedback
- [ ] Fix bugs
- [ ] Add advanced features:
  - Geo-location attendance
  - IP restriction
  - Phone lock/device usage detection

---


| Phase                 | Time Estimate   |
|----------------------|-----------------|
| Setup & Learning     | 1–2 weeks       |
| Frontend             | 1–2 weeks       |
| Backend              | 1–2 weeks       |
| Smart Contracts      | 1–2 weeks       |
| Real-time + Admin    | 1 week          |
| Testing & Launch     | 1 week          |

---

> Built with ❤️ and Web3 for focused minds.
