# Brav-ton
Brav is an innovation on TON, crafted to dissolve the barriers of complexity in digital payments by embedding effortless transfers directly into conversations.


🚀 Vision

To make crypto transactions as simple and natural as chatting with a friend — no addresses, no complex UIs, just human language and blockchain precision.


✨ Key Features (MVP)

* Seamless Payments: Send TON using plain text commands (e.g., `@brav send @adam 50$`).
* Dollar-to-TON Conversion: Automatically converts fiat value to TON using the STONfi SDK.
* PIN Protection: Secure confirmations before sending.
* Inline Bot Experience: Works natively within Telegram chats.

---

🛠️ Future Features

* **Group Splits**: Divide bills and expenses among friends.
* **Nicknames & Tags**: Send to “Mama” or “Bro” instead of raw wallet addresses.
* **Liquidity & Swaps**: Integrate deeper STONfi SDK features for in-chat token swaps.
* **NLP Support**: Natural language commands like “Pay John back \$20.”

---

## 📐 Architecture

```text
[ User ] 
   │
   ▼
[ Brav Bot (Telegram Inline) ]
   │
   ▼
[ Backend Server: Python/Node.js + STONfi SDK ]
   │
   ▼
[ TON Blockchain ]
   │
   ▼
[ Recipient Wallet ]
```

---

## 🔒 Security Considerations

* All sensitive data (PINs, wallet keys) encrypted and stored securely.
* Optional 2FA for large transactions.
* Clear error handling and cancellation options.

---

## 📍 Roadmap

**Phase 1:** Basic transfers + fiat conversion (MVP).
**Phase 2:** Group payments, nicknames, and referral rewards.
**Phase 3:** NLP integration + advanced DeFi functions (swaps, LP).

Just a short one, an extensive roadmap is being built on the brav website at the moment, including every important steps possible.

---

## 💬 Example Usage (Mock Chat Demo)

**Scenario 1: Basic Payment**

**User in Telegram chat:**

```
@brav send @adam 50$
```

**Brav Bot Reply (private to sender):**

```
You are about to send $50 (≈ 12.34 TON) to @adam.  
Please confirm with your PIN:  
```

**User enters PIN:**

```
••••  
```

**Brav Bot Confirmation:**

```
✅ Success! 12.34 TON has been sent to @adam.  
Transaction ID: abc123...xyz  
```

**Recipient (@adam) sees:**

```
💰 You’ve received 12.34 TON from @zaprince via Brav.  
```

---

**Scenario 2: Combined Payment + Balance Check**

**User in Telegram chat:**

```
@brav send $50 in TON to Madison and let me know what my balance is afterwards
```

**Brav Bot Reply (private to sender):**

```
You are about to send $50 (≈ 12.34 TON) to Madison.  
Please confirm with your PIN:  
```

**User enters PIN:**

```
••••  
```

**Brav Bot Confirmation:**

```
✅ Success! 12.34 TON has been sent to Madison.  
Transaction ID: def456...uvw  

Your remaining balance: 243.87 TON  
```

---

## 🤝 Contribution

Brav is in its early stages. Contributions, feedback, and collaboration are welcome. The goal is to grow this into a community-driven payments layer for TON.

---

## 📜 License

MIT License — open for collaboration and innovation.


⚡ Brav makes sending money as easy as sending a message.
