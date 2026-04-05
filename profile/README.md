# Protocol 01

**Privacy infrastructure for Solana.**

One SDK. Ten lines of code. Private transactions.

```bash
npm install @protocol-01/zk-sdk
```

## What we build

| Package | Description | npm |
|---------|-------------|-----|
| **[@protocol-01/zk-sdk](https://github.com/P-01SDK/zk-sdk)** | ZK privacy SDK — shield, transfer, unshield | [![npm](https://img.shields.io/npm/v/@protocol-01/zk-sdk?color=CB3837)](https://www.npmjs.com/package/@protocol-01/zk-sdk) |
| **[@protocol-01/privacy-sdk](https://github.com/P-01SDK/privacy-sdk)** | Unified privacy — stealth, streams, MPC, compliance | [![npm](https://img.shields.io/npm/v/@protocol-01/privacy-sdk?color=CB3837)](https://www.npmjs.com/package/@protocol-01/privacy-sdk) |
| **[@protocol-01/privacy-toolkit](https://github.com/P-01SDK/privacy-toolkit)** | Crypto primitives — Poseidon, Merkle, proof conversion | [![npm](https://img.shields.io/npm/v/@protocol-01/privacy-toolkit?color=CB3837)](https://www.npmjs.com/package/@protocol-01/privacy-toolkit) |
| **[@protocol-01/auth-sdk](https://github.com/P-01SDK/auth-sdk)** | Login with Protocol 01 — QR + biometrics + ZK proofs | [![npm](https://img.shields.io/npm/v/@protocol-01/auth-sdk?color=CB3837)](https://www.npmjs.com/package/@protocol-01/auth-sdk) |
| **[@protocol-01/streams](https://github.com/P-01SDK/streams)** | Payment streams — continuous, cancellable, private | — |

## Tech stack

16 Solana programs · 12 ZK circuits (SNARKs + STARKs) · Quantum-resistant · 8 SDKs

## Try it

```bash
npm init -y && npm install @protocol-01/zk-sdk
node -e "const {poseidonHash}=require('@protocol-01/zk-sdk');poseidonHash([1n,2n]).then(h=>console.log('Poseidon hash:',h.toString(16).slice(0,20)+'...'))"
```

Check out our **[demos](https://github.com/P-01SDK/demos)** for full examples: private payments, subscriptions, payroll, airdrops, OTC.

## Links

[![Website](https://img.shields.io/badge/Website-protocol--01.vercel.app-00D4AA?style=flat)](https://protocol-01.dev)
[![Twitter](https://img.shields.io/badge/Twitter-@Protocol01__-000000?style=flat&logo=x)](https://x.com/Protocol01_)
[![npm](https://img.shields.io/badge/npm-@protocol--01-CB3837?style=flat&logo=npm)](https://www.npmjs.com/org/protocol-01)
