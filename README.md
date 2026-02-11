<h1 align="center">⚔️ Albion Faction Manager (AFM)</h1>
<p align="center"><i>The Ultimate Discord Bot for Albion Online Faction Management & Coordination.</i></p>

<p align="center">
  <img src="https://github.com/ibnuuiqbal/readme-assets/blob/main/foto-faction/bannerawal%20(1).png?raw=true" alt="Albion Faction Manager Banner" width="800">
</p>

<p align="center">
  <img src="https://github.com/ibnuuiqbal/readme-assets/blob/main/foto-faction/albion%20-%202025-11-03T120822.309.png?raw=true" alt="AFM Logo" width="120" height="120">
</p>

<p align="center">
  <a href="https://discord.js.org/"><img src="https://img.shields.io/badge/Discord.js-v14-blue?style=for-the-badge&logo=discord" alt="Discord.js"></a>
  <a href="https://nodejs.org/"><img src="https://img.shields.io/badge/Node.js-v18+-339933?style=for-the-badge&logo=node.js" alt="Node.js"></a>
  <a href="https://www.mongodb.com/"><img src="https://img.shields.io/badge/Database-MongoDB-47A248?style=for-the-badge&logo=mongodb" alt="MongoDB"></a>
  <img src="https://img.shields.io/badge/License-Proprietary-red?style=for-the-badge" alt="License">
</p>

**Albion Faction Manager (AFM)** is an advanced, fully-automated Discord Bot designed specifically to handle the massive scale of Faction Warfare communities in Albion Online. From a luxurious, multi-layered verification system to real-time ZvZ tracking and micro-economy, AFM brings order to the chaos of faction coordination.

---

## 🏜️ Live Deployment & Community
Want to see AFM in action or join our massive community? AFM is currently serving as the core operational backbone for the **EAST Bridgewatch Faction**. 

Join our forces, participate in Faction CTAs, and experience the premium bot features firsthand:

<p align="center">
  <a href="https://discord.gg/buuP3NEWZ2">
    <img src="https://img.shields.io/badge/Join_Bridgewatch_Discord-FFA500?style=for-the-badge&logo=discord&logoColor=white" alt="Join Bridgewatch Discord">
  </a>
</p>

---

## 🌟 Highlight Feature: Premium Faction Verification
Managing thousands of faction members requires strict security and profiling. AFM introduces a **Luxurious Verification UI** for Faction Officers.

* **`/verify` Command:** Users submit their In-Game Name (IGN), Previous Faction history, an in-game screenshot, and an optional Voucher (a veteran who guarantees them).
* **Officer Dashboard UI:** The bot generates a clean, interactive Embed sent directly to verify channel with quick-action buttons:
  * `✅ Approve (Veteran/Core)` - Grants high-tier faction roles.
  * `🔰 Approve (Rookie)` - Grants entry-level roles for new players.
  * `🤝 Request Vouch` - Pings the mentioned veteran to confirm the user's identity.
  * `📊 Check Stats` - Instantly pulls the user's Albion API stats (PvE/PvP Fame).
  * `❌ Decline` - Rejects the application with a logged reason.

---

## 🚀 Core Systems & Automations
Powered by a robust `agenda.js` background scheduler, AFM works 24/7 without manual input:
* **⚔️ Parallel Killboard Listener:** Fetches Albion events every 15 seconds, tracking faction kills, displaying juicy loot, and celebrating Faction MVPs.
* **🧠 Faction Intel Broadcaster:** Randomly drops Albion lore, tactical advice, and hidden mechanics into the chat every 6-12 hours to educate the faction.

---

## 📜 Complete Command Module List

### 🛂 Identity & Security
* `/verify` - Core faction verification workflow.

### ⚔️ Warfare & Scouting (ZvZ)
* `/cta` - Call To Arms deployment and attendance tracking.
* `/scout` & `/scanner` - Report enemy movements and scan zone activity.
* `/bandit` - Track the Faction Warfare Bandit Assault status.
* `/rankbw` - Faction-specific leaderboard and participation content.
* `/route` - Quickly pull up safe travel transport.

### 💰 Faction Economy & Logistics
* `/factionbalance`, `/balance` - Check personal and faction treasury funds.
* `/donate`, `/subsidy` - Contribute to or request funds from the faction bank.
* `/invest`, `/splitloot` - Financial tools for party members.
* `/regear` - Request gear replacements after official CTA deaths.

### 📊 Intelligence & Analytics
* `/albionprofile`, `/stats` - View detailed player fame and kill/death ratios.
* `/price`, `/gold`, `/premium` - Real-time market prices across royal cities.
* `/resource`, `/combatfame` - Track spec and crafting cities.

### 🎯 Minigames & Social Engagement
* `/Bounty`, `/rob`, `/guard` - Bounty System & Economy minigame within Discord.
* `/adventure`, `/fishing`, `/work`, `/daily` - Idle RPG mechanics to earn bot currency.
* `/trivia`, `/gamble`, `/roll` - Albion Trivia and minigames.
* `/albionmeme`, `/randomfact` - Pulls the latest memes from Reddit and game lore.

### ⚙️ Administration & Utilities
* `/admin`, `/setup-admin` - Configure bot behavior and channel routing.
* `/chat`, `/serverinfo`, `/userinfo` - Community management tools.
* `/timezone` - UTC to local time conversion for global factions.
* `/suggest` - Submit feedback to the server manager.

---

## ⚙️ Interface Preview

| **Market System** | **Verify Button** | **Verification System** |
| :---: | :---: | :---: |
| ![Faction Market](https://github.com/ibnuuiqbal/readme-assets/blob/main/foto-faction/Screenshot_1.png?raw=true) | ![Party](https://github.com/ibnuuiqbal/readme-assets/blob/main/foto-faction/Screenshot_2.png?raw=true) | ![Economy](https://github.com/ibnuuiqbal/readme-assets/blob/main/foto-faction/Screenshot_5.png?raw=true) |
| *Marketplace Blackmarket.* | *Sistem Verify Button by API.* | *Verification with Rank 1-5.* |

---
## 🛠️ Architecture
AFM uses a dynamic modular architecture. By simply changing the `FACTION_NAME` and `FACTION_COLOR` in the `.env` file, the bot completely rebrands itself to serve Bridgewatch, Martlock, Lymhurst, Fort Sterling, Thetford, or Caerleon.

<p align="center">
  <i>Developed with ❤️ for the Albion Online Faction Community by <strong>Ibnuuiqbal (JokoSmilch)</strong>.</i>
</p>
