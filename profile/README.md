# BlockDAG Phoenix

**The Open-Source BlockDAG That Actually Ships**

[![Status](https://img.shields.io/badge/status-testnet%20live-brightgreen)](http://testnet.bdpscan.com:6663)
[![License](https://img.shields.io/badge/license-MIT-blue)](LICENSE)
[![Testnet](https://img.shields.io/badge/testnet-live-success)](http://testnet-rpc.bdp.network:16210)

---

## 🎯 **What We're Building**

BlockDAG Phoenix is a transparent, open-source blockchain project building a working DAG-based blockchain with smart contract capabilities.

### **Core Components**

- 🏗️ **[Phoenix Node](https://github.com/BlockDAGPhoenix/phoenix-node)** - Core blockchain node (Kaspa fork + EVM)
- 🔍 **[Phoenix Explorer](https://github.com/BlockDAGPhoenix/phoenix-explorer)** - Block explorer with DAG visualization
- 📦 **[SDKs](https://github.com/BlockDAGPhoenix/phoenix-sdk-js)** - JavaScript, Python, Go SDKs
- 🛠️ **[Dev Tools](https://github.com/BlockDAGPhoenix/phoenix-devtools)** - Hardhat plugin, Foundry config
- 📚 **[Documentation](https://github.com/BlockDAGPhoenix/phoenix-docs)** - Complete technical docs

---

## 🚀 **Quick Start**

### **Connect to Testnet**

```javascript
// Hardhat config
networks: {
  phoenixTestnet: {
    url: "http://testnet-rpc.bdp.network:16210",
    chainId: 11112,
  }
}
```

### **Deploy a Contract**

```bash
npx hardhat run scripts/deploy.js --network phoenixTestnet
```

### **View on Explorer**

🌐 **Explorer**: http://testnet.bdpscan.com:6663  
🔗 **RPC**: http://testnet-rpc.bdp.network:16210

---

## 📊 **Project Status**

| Component | Status | Testnet |
|-----------|--------|---------|
| **Phoenix Node** | ✅ Complete | ✅ Live |
| **Block Explorer** | ✅ Complete | ✅ Live |
| **EVM Integration** | ✅ Complete | ✅ Live |
| **RPC Server** | ✅ Complete | ✅ Live |
| **SDKs** | 🟡 In Progress | - |
| **Dev Tools** | 🟡 In Progress | - |

---

## 🔗 **Links**

- **🌐 Testnet Explorer**: http://testnet.bdpscan.com:6663
- **🔗 Testnet RPC**: http://testnet-rpc.bdp.network:16210
- **📚 Documentation**: [phoenix-docs](https://github.com/BlockDAGPhoenix/phoenix-docs)
- **💬 Community**: [Coming Soon]

---

## 🛠️ **Development**

### **Repositories**

- **[phoenix-node](https://github.com/BlockDAGPhoenix/phoenix-node)** - Core blockchain node
- **[phoenix-explorer](https://github.com/BlockDAGPhoenix/phoenix-explorer)** - Block explorer
- **[phoenix-sdk-js](https://github.com/BlockDAGPhoenix/phoenix-sdk-js)** - JavaScript SDK
- **[phoenix-sdk-python](https://github.com/BlockDAGPhoenix/phoenix-sdk-python)** - Python SDK
- **[phoenix-sdk-go](https://github.com/BlockDAGPhoenix/phoenix-sdk-go)** - Go SDK
- **[phoenix-devtools](https://github.com/BlockDAGPhoenix/phoenix-devtools)** - Developer tools
- **[phoenix-docs](https://github.com/BlockDAGPhoenix/phoenix-docs)** - Documentation

### **Contributing**

We welcome contributions! See individual repository READMEs for contribution guidelines.

---

## 📝 **License**

MIT License - See individual repositories for license details.

---

## 🎯 **Mission**

Build a transparent, open-source BlockDAG blockchain that delivers what others promised but failed to ship: a working DAG network with smart contract capabilities.

**100% EVM Compatible** - Deploy any Ethereum contract without modification.

---

**Status**: 🟢 **Testnet Live** | **Mainnet**: Q3 2025

