<div align = "center">
<h1>Rust Calculator 🖩 in Solana 🦀<h1>
</div>

This Calculator written Rust using [Anchor ⚓](https://project-serum.github.io/anchor/getting-started/introduction.html) 

## Setting up the Environment:

* Rust Installation:

```bash
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
source $HOME/.cargo/env
rustup component add rustfmt
```

* Solana Installation:

```bash
sh -c "$(curl -sSfL https://release.solana.com/v1.8.0/install)"
```
**Please update your `PATH` environment variable to include the solana programs**

* [Anchor ⚓](https://project-serum.github.io/anchor/getting-started/introduction.html) Installation: 

```bash
npm i -g @project-serum/anchor-cli
```

* And we can use Cargo to install CLI:

```bash
cargo install --git https://github.com/project-serum/anchor --tag v0.17.0 anchor-cli --locked
```

---

## Configurations on Solana CLI

```bash
solana config get
```

Configure `RPC URL`

```bash
solana config set --url localhost
```

Wallet address and airdrop some **SOL**

```bash
solana address
```

* For more comprehensive details of your account

```
solana account <your address from the last command>
```
---

### Build project from scratch

* Setting up anchor project

```bash
anchor init <your project name>

cd <your project directory>
```

* Compile the project

```bash
anchor build
```

* To run tests 

```bash
anchor test
```
