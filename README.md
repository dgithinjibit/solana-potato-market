# Solana Potato Market

A decentralized application (DApp) built on Solana to connect potato farmers directly with buyers, eliminating the need for middlemen.
For teh data, I used ML algs to use synthesis daa for teting and it works better for data security and hope you do the same

## Features

- Farmer and buyer registration
- Potato listing and browsing
- Direct order placement and payment
- Transparent transaction history

## Project Structure

- `programs/` - Solana smart contracts (Rust, Anchor)
- `app/` - Frontend application (e.g., React)
- `tests/` - Integration and unit tests

## Getting Started

1. **Clone the repository:**
   ```sh
   git clone https://github.com/dgithinjibit/solana-potato-market.git
   cd solana-potato-market
   ```

2. **Install dependencies:**
   - [Solana CLI](https://docs.solana.com/cli/install-solana-cli)
   - [Rust](https://www.rust-lang.org/tools/install)
   - [Anchor](https://book.anchor-lang.com/chapter_1/installation.html)
   - [Node.js](https://nodejs.org/) (for frontend)

3. **Build and deploy the smart contract:**
   ```sh
   anchor build
   anchor deploy
   ```

4. **Run the frontend app:**
   ```sh
   cd app
   npm install
   npm start
   ```

## License

MIT
