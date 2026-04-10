<div align="center">

<img src="https://raw.githubusercontent.com/00impera/wBASEwrapped/master/logo.png" width="140" height="140" style="border-radius:50%;" alt="wBASE Logo"/>

# 🟢 Wrapped Base — wBASE

### *The native wrapped token of Monad Mainnet*

[![Chain](https://img.shields.io/badge/Chain-Monad%20Mainnet-00FF88?style=for-the-badge&logoColor=white)](https://monad.xyz)
[![Chain ID](https://img.shields.io/badge/Chain%20ID-143-00EEFF?style=for-the-badge)](https://monad.xyz)
[![Token](https://img.shields.io/badge/Token-BASE-00FFD0?style=for-the-badge)](https://monadvision.com/token/0x571c49484966dE336C74AEc98A5FF18e701E58Fe)
[![Decimals](https://img.shields.io/badge/Decimals-18-0099FF?style=for-the-badge)](https://monadvision.com/token/0x571c49484966dE336C74AEc98A5FF18e701E58Fe)

</div>

---

## 📌 Contract Address

```
0x571c49484966dE336C74AEc98A5FF18e701E58Fe
```

> 🔗 [View on MonadVision](https://monadvision.com/token/0x571c49484966dE336C74AEc98A5FF18e701E58Fe?tab=Contract)

---

## ⚡ What is wBASE?

**Wrapped Base (wBASE)** is the ERC-20 wrapped version of the native **MON** token on **Monad Mainnet**.  
It follows the classic `WETH` pattern — deposit MON to receive BASE 1:1, and withdraw any time to get MON back.

wBASE enables MON to be used in DeFi protocols, DEXes, and smart contracts that require an ERC-20 interface.

---

## 🔧 Contract Functions

| Function | Type | Description |
|---|---|---|
| `deposit()` | 🟢 payable | Send MON → receive BASE 1:1 |
| `withdraw(wad)` | 🔵 write | Burn BASE → get MON back |
| `transfer(dst, wad)` | 🔵 write | Send BASE to any address |
| `approve(guy, wad)` | 🔵 write | Allow a spender to use your BASE |
| `transferFrom(src, dst, wad)` | 🔵 write | Transfer BASE on behalf of owner |
| `balanceOf(addr)` | 👁️ view | View BASE balance of a wallet |
| `totalSupply()` | 👁️ view | Total MON locked in the contract |
| `allowance(owner, spender)` | 👁️ view | Check approved spend amount |

---

## 🚀 How to Use

### Deposit MON → BASE
```solidity
// Send MON with the transaction, receive BASE 1:1
wBASE.deposit{ value: 1 ether }();
```

### Withdraw BASE → MON
```solidity
// Burn 1 BASE, receive 1 MON back
wBASE.withdraw(1 ether);
```

### Transfer BASE
```solidity
// Send BASE to another address
wBASE.transfer(recipientAddress, amount);
```

---

## 🌐 Network Details

| Parameter | Value |
|---|---|
| Network | Monad Mainnet |
| Chain ID | `143` |
| RPC URL | `https://rpc.monad.xyz` |
| Explorer | `https://monadscan.com` |
| Symbol | `BASE` |
| Decimals | `18` |

---

## 🖥️ dApp

A fully functional web dApp is available in [`index.html`](./index.html).

**Features:**
- 🦊 EVM wallet connect (MetaMask & compatible)
- 🟩 NEAR wallet connect (MyNearWallet, HERE, Meteor, WalletConnect)
- 💚 Deposit MON → BASE
- 💙 Withdraw BASE → MON
- 🔀 Transfer BASE to any address
- 📊 Live balance display
- 🔔 Auto network detection & switch prompt

---

## 📡 Links

| | |
|---|---|
| 🐦 Twitter / X | [@bnbgold277983](https://x.com/bnbgold277983) |
| 💬 Discord | [Join Server](https://discord.com/channels/1316093079090106472) |
| 🔍 Contract | [MonadVision](https://monadvision.com/token/0x571c49484966dE336C74AEc98A5FF18e701E58Fe?tab=Contract) |
| ⛓️ Explorer | [MonadScan](https://monadscan.com) |

---

## ⛽ Donate

If you find wBASE useful, consider donating to the contract address:

```
0x571c49484966dE336C74AEc98A5FF18e701E58Fe
```

---

<div align="center">

**WRAPPED BASE · wBASE · MONAD MAINNET · CHAIN ID 143**

*Made with 💚 on Monad*

</div>
