Decentralized Notes App on Solana

A fully decentralized Notes Application built on the Solana blockchain using Rust, Anchor Framework, Next.js, and Tailwind CSS.
Store, manage, and access your notes in a trustless, user-owned, and fully on-chain environment.

🔗 Live Demo: https://notes-dapp-solana.vercel.app

📸 Preview

<img width="639" height="262" alt="image" src="https://github.com/user-attachments/assets/a23764f3-7e22-4b22-9917-d6be1de87d23" />


🚀 Features
🧱 On-Chain Architecture

Decentralized Storage: Notes are saved directly on the Solana blockchain

Anchor Framework: Manages accounts, instructions, constraints, and PDA derivations

User-Owned Accounts: Only the wallet owner can update/delete their notes

💼 Wallet Integration

Supports Phantom Wallet

Connect / disconnect seamlessly

All actions require on-chain signatures

📝 Full CRUD Functionality

Create a new on-chain note

Read all notes associated with your wallet

Update existing notes

Delete notes permanently

All operations stored immutably on chain

🎨 Modern UI

Built with Next.js (App Router)

Styled using Tailwind CSS

Fully responsive, clean UI

📦 Packages Required

Install all required Solana + Anchor client packages:

npm install \
  @project-serum/anchor \
  @solana/web3.js \
  @solana/wallet-adapter-base \
  @solana/wallet-adapter-react \
  @solana/wallet-adapter-react-ui \
  @solana/wallet-adapter-wallets

  ⚙️ Development Setup
1. Clone the Repository
git clone https://github.com/developernarendra/notes-dapp-solana-program.git
cd notes-dapp-solana-program

2. Install Dependencies
npm install

