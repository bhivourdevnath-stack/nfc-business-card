#  NFC Business Card

A smart business card with an embedded NFC chip that shares your contact info, social links, or portfolio with a single tap. No app required—just tap and connect.

---

#  Features

- **One-Tap Sharing** — Hold near any NFC-enabled phone to instantly open your digital profile
- **No App Needed** — Works natively on iOS and Android
- **Fully Customizable** — Update your info anytime by editing a linked webpage
- **Reusable** — One card, endless updates. No reprinting, no waste
- **Sleek & Durable** — Available in PVC or metal finishes

---

#  How It Works

1. An NFC tag (NTAG213/215) is embedded in the card
2. The tag is programmed with a URL or vCard data
3. When tapped, the phone reads the tag and opens your profile
4. Update your details online—the card stays the same

---

#  Getting Started

### What You'll Need

| Item | Details |
|------|---------|
| NFC Tag/Card | NTAG213 or NTAG215 (use on-metal tags for metal cards) |
| Writer Device | Any NFC-enabled smartphone |
| Writing App | [NFC Tools](https://www.wakdev.com/en/apps/nfc-tools.html) (iOS/Android) |

### Programming Your Card

**Option 1: URL Method (Recommended)**
1. Create a webpage with your contact info (e.g., Carrd, Linktree, or custom)
2. Open your NFC writing app
3. Write the URL to the tag
4. Done—update the page anytime without reprogramming

**Option 2: vCard Method**
1. Prepare your contact details (name, phone, email, company)
2. Use the app to write a vCard to the tag
3. Tapping prompts the phone to save your contact directly

---

#   Compatibility

- **iOS** — iPhone 7 and newer
- **Android** — Most devices with NFC hardware

---

#  Tips

- Use **on-metal NFC tags** if your card is metal, or the signal will be blocked
- Keep URLs short for faster reads
- Test on both iOS and Android before distributing

---

#  Project Structure
<p>
nfc-business-card/<br>
├── README.md<br>
├── card-design/ # Print files and layouts<br>
├── firmware/ # custom PCB code<br>
└── docs/ # Guides and references
</p>

---

# 🤝 Contributing

Contributions, ideas, and improvements are welcome! Feel free to open an issue or submit a pull request.

---

#  License

This project is licensed under the MIT License.

---

## 🔗 Resources

- [NFC Tools App](https://www.wakdev.com/en/apps/nfc-tools.html)
- [NTAG213 Datasheet](https://www.nxp.com/docs/en/data-sheet/NTAG213_215_216.pdf)
- [NFC Forum Specifications](https://nfc-forum.org/)

---
