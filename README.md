# Freelancing Tools

Desktop app for freelance **proposals**, **English ↔ Spanish translation**, **resume builder & PDF export**, and **notes** with attachments.

## Index

- [Quick start](#quick-start)
  - [Installer](#installer)
  - [Portable (zip)](#portable-zip)
  - [API keys](#api-keys)
- [License & pricing](#license--pricing)
  - [Purchase a license](#purchase-a-license)
  - [How to activate](#how-to-activate)
- [How to use](#how-to-use)
  - [Proposal tab](#proposal-tab)
  - [Translator tab](#translator-tab)
  - [Note tab](#note-tab)
  - [Resume tab](#resume-tab)
  - [Backup](#backup)
- [Coming soon](#coming-soon)
- [Troubleshooting](#troubleshooting)
- [Support the project (donate)](#support-the-project-donate)

---

## Quick start

### Installer

1. Run `installer\FreelancingTools-Setup-*.exe`.
2. Launch **Freelancing Tools** from the Start menu (optional desktop shortcut).
3. On first run, **activate a license** or start the **3-day free trial**.

### Portable (zip)

1. Unzip `FreelancingTools-*-portable.zip` to a folder (e.g. `Desktop\FreelancingTools`).
2. Run **`Freelancing Tools.exe`** inside the `FreelancingTools` folder.
3. Keep all files in that folder together — do not move only the `.exe`.

### API keys

1. Open **Settings** (gear icon in the title bar).
2. Add your **Anthropic API key** (required for proposals, translation, and resume AI).
3. Click **Save**.

Your data (database, notes, resume profiles, attachments) is stored in:

`%LOCALAPPDATA%\FreelancingTools\`

---

## License & pricing

| Plan | Duration | Price | Notes |
|------|----------|-------|-------|
| **Free trial** | 3 days | **$0** | One trial per device. Start from the License screen. |
| **1 month** | 30 days | **$10** |  |
| **3 months** | 90 days | **$25** | Save $5 vs paying monthly ($30). |
| **6 months** | 180 days | **$45** | Save $15 vs paying monthly ($60). |
| **1 year** | 365 days | **$80** | Save $40 vs paying monthly ($120). |
| **Lifetime** | No expiry | **$149** | Best value — one-time license, all future updates. |

### Purchase a license

1. Pay for the plan you want using crypto on any **EVM network** (wallet address in [Support the project (donate)](#support-the-project-donate) below).
2. Send an email to **mern2025@outlook.com** with:
   - **Device ID** — from the License screen (`XXXX-XXXX-XXXX-XXXX`)
   - **Duration** — the plan you purchased (e.g. 1 month, 3 months, 1 year, lifetime)
   - **Transaction link** — URL from a blockchain explorer (Etherscan, Polygonscan, BscScan, etc.) showing your payment

You will receive your license key by email after the payment is confirmed.

### How to activate

1. Open the app and go to the **License** screen (shown on startup, or when trial ends).
2. Copy your **Device ID** and keep it for the purchase email above.
3. Paste the key you receive (`XXXX-XXXX-XXXX-YYYYMMDD` — last segment is the expiry date).
4. Click **Activate license**.

**Free trial:** click **Start 3-day trial** once per device — no payment required.

**Questions or license support:** mern2025@outlook.com

---

## How to use

### Proposal tab

1. Add a **proposal maker** (+) — your freelancer profile and platform (Upwork, Fiverr, etc.).
2. Select a maker, paste the **job description**, click **Generate** (play).
3. Copy or clear the proposal from the output panel.
4. History is saved locally per maker.

### Translator tab

1. Choose source and target language (English ↔ Spanish).
2. Paste text, click **Run** for that direction.
3. Copy the translation from the output panel.

### Note tab

1. Create **notes** (+) in the left column.
2. Add **keys** (+) in the middle column; drag to reorder.
3. Edit **values** on the right — text auto-saves; attach images or files from the toolbar.

### Resume tab

Build a modern two-column resume and export a PDF that matches the on-screen preview.

1. Open the **Resume** tab.
2. Under **Users**, click **+** to add a profile (list name, e.g. a client or your name).
3. Fill in **Profile details**: name, contact, links, location, and **Education**.
4. In **Generated content**, optionally click the **play** button to generate **headline**, **skills**, **summary**, and **experience** with AI from a job post or resume brief (uses your Anthropic key and the profile **Location** for realistic employers).
5. Edit any field manually — changes save automatically.
6. Click **Preview** to see the formatted resume in a dialog.
7. Click **Save as…** to export a PDF to your chosen folder.

Drag users in the left list to reorder profiles.

### Backup

In **Settings**, use **Export data** / **Import data** to back up or restore your database, resume profiles, and attachments as a ZIP file.

---

## Coming soon

Planned features:

- OpenAI integration (in addition to Anthropic) for proposals, translation, and resume AI
- More languages in the translator for developers and international clients
- Additional resume PDF templates and layout styles
- Multi-language caption detection from voice (live captions across languages)

---

## Troubleshooting

| Issue | What to try |
|-------|-------------|
| App won’t start | Run from the install or portable folder; allow through antivirus. |
| License / trial | Enter a valid key for this Device ID, or start the 3-day trial once. |
| API errors | Check Anthropic key in Settings, billing, and internet connection. |
| Resume AI | Ensure Anthropic key is set; paste a job description or brief when generating. |
| PDF export | Use **Save as…** after filling profile fields; try **Preview** first. |

---

## Support the project (donate)

If Freelancing Tools helps your work, you can send a tip to the same wallet on **any EVM-compatible network** (Ethereum, Polygon, Arbitrum, Base, BNB Chain, and others).

Use the **same address** on whichever chain you prefer. Send native coins (ETH, MATIC, BNB, etc.) or tokens (USDT, USDC, and other ERC-20-style assets on that chain).

**EVM address:**
```
0xc3E55e24e7F4d4539e87205F3b03791e0034fdcE
```

Always double-check the address and network in your wallet before sending.

![Donate — scan QR code (EVM address)](donate-qrcode.png)


---

Thank you for using **Freelancing Tools**.
