Tipcaster is a Farcaster-native social tipping app that lets users send tips in MON (the Monad native token) directly through Frames — no wallet connection required.

This project enables seamless, gasless, one-click tipping to support creators and celebrate great casts in a decentralized, user-friendly way.

---

✨ Features

⚡ Gasless tipping — users can send MON without signing or connecting wallets

🧵 Farcaster Frames integration — tipping happens right in the feed

💰 Monad-native tokens — tips are powered by Monad, optimized for low-cost and high-speed txs

🎨 Modern UI — styled with Tailwind CSS and shadcn/ui, designed to match the Farcaster aesthetic

🔒 No user setup required — frictionless UX for first-time users

📈 Potential integrations — leaderboard, tip history, and on-chain proof

---

🛠 Tech Stack

Frontend: Next.js 14, React, Tailwind CSS, shadcn/ui

Farcaster Integration: Frames via Neynar or custom serverless endpoint

Blockchain: Monad (testnet or mainnet)

Optional Backend: Relayer / tipping orchestrator (Node.js or serverless functions)

---

🚀 Getting Started

git clone https://github.com/your-username/tipcaster.git
cd tipcaster
npm install
npm run dev

Update your .env file with any necessary keys (e.g., for relayers, Neynar, RPC endpoints).

---

📁 Project Structure

/components        → UI elements (button, card, frame)
/pages             → App routes (tip frame, success)
/lib or /utils     → Utility functions
/public            → Static assets
/styles            → Tailwind base config

---

🧪 Example Use Case

> A user sees a great cast. A “Tip” button appears via a Frame. They click, and MON is sent instantly — no wallet needed. The cast gets rewarded, the user feels good, and everyone wins.

---

📜 License

MIT


---

🤝 Contributing

Pull requests, suggestions, and feature ideas are welcome! Let’s build a better way to reward value onchain — one tip at a time.
