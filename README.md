# 🕵️ Dark Web Simulation — Educational Cybersecurity Project

> **⚠ DISCLAIMER: This project is 100% fictional and created solely for educational and cybersecurity awareness purposes. No illegal content is included or promoted. All .onion addresses, products, crypto addresses, usernames, and data are completely fabricated.**

---

## 📖 Overview

**Dark Web Simulation** is an 8-page static HTML educational project that recreates the look, feel, and conceptual mechanics of real darknet services. It is designed for:

- Cybersecurity students and enthusiasts learning how the dark web works
- Educators demonstrating digital privacy, anonymity, and encryption concepts
- Writers and journalists who need an accurate reference for darknet architecture
- OSINT researchers studying digital threat surfaces

Every page includes a mandatory educational disclaimer popup and a creator attribution guard — removing or altering `Harshit Kashyap`'s name from any page will disable that page's functionality.

---

## 👤 Author

**Harshit Kashyap**

> Unauthorised removal or alteration of the creator's attribution in any file will render that page non-functional. The attribution guard is enforced via JavaScript DOM mutation observers.

---

## 🗂️ Project Structure

```
Local_Darknet/
├── index.html          ← Page 1: Gateway Directory (Hidden Wiki)
├── market.html         ← Page 2: Underground Marketplace
├── pgp_encrypt.html    ← Page 2a: PGP Escrow Checkout (linked from Market)
├── forum.html          ← Page 3: Paranoia Forum
├── paste.html          ← Page 4: Secure Pastebin / Dead Drop
├── mixer.html          ← Page 5: Cryptocurrency Tumbler
├── securedrop.html     ← Page 6: Whistleblower Secure Drop
├── search.html         ← Page 7: Darknet Search Engine
└── blog.html           ← Page 8: Cypherpunk Manifesto Blog
```

---

## 📄 Page Descriptions

### Page 1 — `index.html` · The Gateway Directory (Hidden Wiki)
The central hub that connects all local pages.

- **Design**: Pure black (`#000000`) background, terminal green (`#4AF626`) text, `Courier New` font
- **Animation**: CSS-only blinking cursor via `@keyframes` opacity toggle
- **Content**: ASCII "THE INDEX" logo, intro text about .onion URLs, categorised links table with fake 56-character .onion addresses, fake PGP public key block

**Concept taught**: How Hidden Wiki-style directories work as onion-site navigators, and why PGP keys are posted for site verification.

---

### Page 2 — `market.html` · Underground Marketplace
A stripped-down, utilitarian darknet market mimicking early eBay / AlphaBay.

- **Design**: 3-column CSS Grid, thin gray borders (`#333333`), small 150×150 product images with CSS dither/pixelation overlay
- **Animation**: On hover — border turns red, cursor changes to `crosshair`
- **Products** (all fictional):
  - *Encrypted Burner OS (Bootable USB)* — 0.04 XMR
  - *Leaked Area 51 Sub-level Blueprints (PDF)* — 0.01 BTC
  - *EMP Generator Schematics* — 0.15 XMR

**Concept taught**: How darknet markets are structured, crypto pricing, vendor ratings, and escrow systems.

#### Page 2a — `pgp_encrypt.html` · PGP Escrow Checkout
"Buy" buttons on the market link here instead of a cart.

**Concept taught**: Why buyers must encrypt their shipping address with the vendor's PGP key — the cornerstone of darknet escrow/opsec.

---

### Page 3 — `forum.html` · The Paranoia Forum
Anonymous text board (Reddit / 4chan aesthetic).

- **Design**: Alternating dark gray/black rows, text-heavy, no profile pictures, anonymous usernames only (e.g., `User_9942`, `CipherGhost`)
- **Threads**:
  - 📌 *OpSec Rules: How to not get caught* (pinned)
  - *Is anyone else's node routing through hostile servers today?*
  - *TUTORIAL: Setting up a dead-drop server on a Raspberry Pi*

**Concept taught**: Why UTC-only timestamps are mandatory — local time zones leak real-world location.

---

### Page 4 — `paste.html` · Secure Pastebin / Dead Drop
Anonymous encrypted text dump service.

- **Design**: Full-screen `<textarea>` occupying ~80vh, functional radio buttons for syntax type, expiry selector, no decorative animations (intentionally utilitarian)
- **Pre-filled content**: A fictional classified corporate memo about an AI that began rewriting its own code (complete with hex dumps and `[REDACTED BY SYSADMIN]` markers)
- **Burn After Reading**: Checkbox that simulates the "server deletes on first read" mechanism

**Concept taught**: How dead-drop pastebin services work, what "Burn After Reading" means in the context of one-time secure data sharing.

---

### Page 5 — `mixer.html` · Cryptocurrency Tumbler (CoinShuffle)
A professional-looking crypto mixing / laundering simulation.

- **Design**: Sleek dark blue (`#0A1128`) and white, clean sans-serif (Arial/Helvetica) — intentionally trust-building aesthetic
- **Animation**: CSS `@keyframes` rotating spinner + progress bar that simulates the "mixing" process
- **Steps**:
  1. Destination address input
  2. Delay time dropdown (2h – 72h)
  3. Randomised one-time deposit address generator
- **Warning**: Prominent banner — *"Do not send funds directly from a KYC exchange!"*

**Concept taught**: How crypto mixing/tumbling works, what blockchain analysis is, why timing delays break correlation attacks, and why KYC exchange funds are dangerous.

---

### Page 6 — `securedrop.html` · Whistleblower Drop (SecureDrop Clone)
A sterile, high-stakes document submission portal.

- **Design**: White (`#FFFFFF`) background, black text, stark red warning banner (`#D32F2F`), accessibility-focused
- **Animation**: Pulsing red dot next to "SECURE CONNECTION ESTABLISHED" using CSS `transform: scale()`
- **Content**:
  - Step-by-step OpSec instructions (Tails OS, public Wi-Fi)
  - EXIF/metadata scrubbing guide
  - `<input type="file">` upload portal
  - JavaScript codename generator (e.g., *Blue-Falcon-Nine*)

**Concept taught**: How SecureDrop works, what EXIF metadata is and why it must be scrubbed, how journalists protect source anonymity via codename-based reply systems.

---

### Page 7 — `search.html` · Darknet Search Engine (TorchX)
A Google-1998-style onion search engine.

- **Design**: Retro search engine layout — massive centred logo, simple text input, two buttons. Results on a separate view
- **Animation**: On hover over a result, `margin-left: 1px` applied — subtle jitter/instability effect
- **Ad banner**: Fake text-based ad (*"Need a new identity? Click here for offshore passports."*)
- **Results**: 6 fake links with vague titles, long .onion strings, and **Uptime %** badges

**Concept taught**: Why uptime % matters on the dark web (sites go offline constantly), how .onion DNS works (or doesn't), and why darknet search engines are inherently unreliable.

---

### Page 8 — `blog.html` · Cypherpunk Manifesto Blog
A hacker's personal technical blog.

- **Design**: Pure black background, amber (`#FFBF00`) text, no margins or padding — text stretches full width, multi-column layout with blogroll sidebar
- **Animation**: CSS typewriter effect on the `<h1>` header using `@keyframes` width animation + blinking caret
- **Article**: *"How to Build a Faraday Cage for Your Mobile Devices Using Household Items to Block IMSI-Catchers"* — a detailed, technical (fictional) tutorial
- **Blogroll**: Left sidebar with links to "allied" hacker blogs
- **PGP Signatures**: Every post ends with a realistic fake PGP signature block

**Concept taught**: What PGP post signatures are and why they're used, what IMSI-catchers/Stingrays are, and what Faraday cages accomplish.

---

## 🔐 Security & Attribution Guard

Every page implements the following protection mechanism:

1. **Educational Popup**: Shown immediately on page load. The user must acknowledge the educational purpose before any content is shown.

2. **Creator Attribution**: The name `Harshit Kashyap` is embedded in the DOM of every page as `<span id="creator-name">Harshit Kashyap</span>`.

3. **DOM Mutation Observer**: A JavaScript `MutationObserver` monitors the entire document body for changes. If the creator's name is removed or altered:
   - The main content is immediately hidden
   - The popup overlay re-appears with an `ERROR 403` message
   - The page becomes non-functional

This ensures the project cannot be repurposed without proper attribution.

---

## 🧠 Concepts Covered

| Concept | Covered In |
|---------|-----------|
| .onion URL structure | All pages |
| PGP public keys & signatures | index.html, blog.html |
| Escrow & PGP-encrypted shipping | market.html, pgp_encrypt.html |
| UTC-only timestamps | forum.html |
| Burn After Reading (one-time pastes) | paste.html |
| Blockchain analysis & mixing | mixer.html |
| KYC vs non-KYC wallets | mixer.html |
| EXIF metadata scrubbing | securedrop.html |
| Tails OS & operational security | securedrop.html |
| Darknet search uptime % | search.html |
| IMSI catchers (Stingrays) | blog.html |
| Faraday cages for RF shielding | blog.html |
| CSS-only animations | All pages |

---

## 🚀 Usage

This is a fully static HTML project — no server, no build step, no dependencies.

```bash
# Clone the repository
git clone https://github.com/Harshitkashyap2027/darkweb.git
cd darkweb

# Open in a browser
open index.html
# or
start index.html   # Windows
```

Navigate between pages using the in-page links. All pages are self-contained HTML files.

---

## ⚖️ Legal & Ethical Notice

- This project does **not** facilitate, promote, or enable any illegal activity.
- All .onion addresses, crypto wallet addresses, product listings, usernames, and documents are **completely fabricated**.
- The project is intended as an educational tool to understand the technical architecture of darknet services.
- Use of this project to engage in actual illegal activities is strictly prohibited and is the sole responsibility of the user.
- This project is inspired by publicly available cybersecurity research, journalism (ProPublica SecureDrop, Tor Project documentation), and academic literature.

---

## 📜 License

This project is released for educational use. Attribution to **Harshit Kashyap** is mandatory in any derivative work. Removal of attribution will disable the relevant pages by design.
