# MemoryMesh AI — Vercel Deployment

## 🚀 Deploy to Vercel (3 Steps)

### Option A — Vercel Dashboard (Easiest)
1. Go to **vercel.com** → New Project
2. Upload this folder OR connect GitHub repo
3. Click **Deploy** — done!

### Option B — Vercel CLI
```bash
npm install -g vercel
cd memorymesh-vercel
vercel --prod
```

### Option C — GitHub + Vercel Auto-Deploy
1. Push this folder to `github.com/Kashif130/memorymesh-subnet`
2. Go to vercel.com → Import Git Repository
3. Select the repo → Deploy

---

## 📁 Files
```
memorymesh-vercel/
├── index.html      ← Complete app (single file, 105KB)
├── vercel.json     ← Vercel routing config
└── README.md       ← This file
```

---

## ✅ Features Included

| Feature | Status |
|---------|--------|
| Wallet Connect (SubWallet, Talisman, Polkadot.js, Fearless) | ✅ |
| Manual address entry (SS58) | ✅ |
| Home / Landing page | ✅ |
| Dashboard with live stats | ✅ |
| Robot registration | ✅ |
| Task posting & management | ✅ |
| Memory Store query | ✅ |
| Reputation Leaderboard | ✅ |
| Simulator (full PoPW flow) | ✅ |
| testKNX Faucet | ✅ |
| Subnet Info page | ✅ |
| Live subnet log | ✅ |
| PoPW artifact viewer | ✅ |
| Score trend chart | ✅ |
| Toast notifications | ✅ |
| Responsive mobile layout | ✅ |
| Zero external dependencies | ✅ |
| Vercel-ready (vercel.json) | ✅ |

---

## 🔗 Wallet Setup for Konnex Testnet

**SubWallet (Recommended)**
1. Install from subwallet.app
2. Manage Networks → Add Network
3. RPC: `wss://testnet-rpc1.konnex.world:39944`
4. Connect in the dashboard

**Talisman**
1. Install from talisman.xyz
2. Settings → Networks → Add custom network
3. Same RPC endpoint above

---

**Muhammad Kashif Ali** | mkashifali.kcp@gmail.com | @mkashifalikcp
github.com/Kashif130/memorymesh-subnet
