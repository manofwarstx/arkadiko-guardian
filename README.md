# 🛡️ Arkadiko Vault Guardian

> **Vibecode Submission:** A lightweight, visual health monitor for Arkadiko Finance Vaults on the Stacks blockchain.

![License](https://img.shields.io/badge/license-MIT-blue.svg) ![Platform](https://img.shields.io/badge/platform-Stacks-purple)

## 🔗 Live Demo
**[👉 Click here to view the Dashboard](https://manofwarstx.github.io/arkadiko-guardian/)**

---

## 📖 About
DeFi users often suffer from "Liquidation Anxiety"—the fear that market volatility will liquidate their assets while they sleep. 

**Arkadiko Vault Guardian** is a concept dashboard designed to solve this. It provides a simple, visual interface to check the health of a vault (Collateralization Ratio) at a glance. Instead of complex tables, it uses a **dynamic health bar** and color-coded alerts to indicate risk levels instantly.

## ✨ Features
* **Visual Risk Meter:** A dynamic bar that changes from Green (Safe) to Red (Danger) as the vault approaches the liquidation threshold (130%).
* **Instant Feedback:** No complex wallet connection required to simply *read* data.
* **Client-Side Privacy:** Runs entirely in the browser.

## 🛠️ How It Works (Architecture)
This demo simulates the following flow:
1.  **Input:** User provides a Stacks Wallet Address.
2.  **Query:** The app queries the Stacks Blockchain API (simulated in demo) for the specific Arkadiko Vault Contract ID.
3.  **Process:** It retrieves `collateral-amount` and `debt-amount`.
4.  **Compute:** Calculates the Collateralization Ratio using the current Oracle price of STX.
5.  **Render:** Updates the DOM to visualize the health status.

## 🚀 Quick Start
To run this locally on your machine:

1.  Clone this repository:
    ```bash
    git clone [https://github.com/yourusername/arkadiko-guardian.git](https://github.com/yourusername/arkadiko-guardian.git)
    ```
2.  Navigate to the folder:
    ```bash
    cd arkadiko-guardian
    ```
3.  Open `index.html` in your browser.

## 🔮 Future Roadmap
* [ ] **Live API Integration:** Connect to real-time Stacks Node API.
* [ ] **Push Notifications:** Integrate Discord Webhooks for mobile alerts.
* [ ] **Auto-Repay:** "One-click" debt repayment if health drops below 140%.

## 🤝 Community
Built for the **Arkadiko** and **Stacks** ecosystem.
Tags: `@ArkadikoFinance` `@Stacks` `@zeroauthdao`
