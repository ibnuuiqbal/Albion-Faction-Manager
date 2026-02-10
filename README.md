# ⚔️ Albion Faction Manager (AFM)
> **The Ultimate Discord Bot for Albion Online Faction Management & Coordination.**
<p align="center">
  <img src="https://github.com/ibnuuiqbal/readme-assets/blob/main/foto-faction/bannerawal%20(1).png?raw=true" alt="Albion Faction Manager Banner" width="800">
</p>

<p align="center">
  <img src="https://github.com/ibnuuiqbal/readme-assets/blob/main/foto-faction/albion%20-%202025-11-03T120822.309.png?raw=true" alt="AFM Logo" width="120" height="120">
</p>
[![Discord.js](https://img.shields.io/badge/Discord.js-v14-blue?style=for-the-badge&logo=discord)](https://discord.js.org/)
[![Node.js](https://img.shields.io/badge/Node.js-v18+-339933?style=for-the-badge&logo=node.js)](https://nodejs.org/)
[![MongoDB](https://img.shields.io/badge/Database-MongoDB-47A248?style=for-the-badge&logo=mongodb)](https://www.mongodb.com/)
[![License](https://img.shields.io/badge/License-Proprietary-red?style=for-the-badge)]()

**Albion Faction Manager (AFM)** is an advanced, fully-automated Discord Bot designed specifically to handle the massive scale of Faction Warfare communities in Albion Online. From a luxurious, multi-layered verification system to real-time ZvZ tracking and micro-economy, AFM brings order to the chaos of faction coordination.

---

## 🌟 Highlight Feature: Premium Faction Verification
Managing thousands of faction members requires strict security and profiling. AFM introduces a **Luxurious Verification UI** for Faction Officers.

* **`/verify` Command:** Users submit their In-Game Name (IGN), Previous Faction history, an in-game screenshot, and an optional Voucher (a veteran who guarantees them).
* **Officer Dashboard UI:** The bot generates a clean, interactive Embed sent directly to the Officer channel with quick-action buttons:
  * `✅ Approve (Veteran/Core)` - Grants high-tier faction roles.
  * `🔰 Approve (Rookie)` - Grants entry-level roles for new players.
  * `🤝 Request Vouch` - Pings the mentioned veteran to confirm the user's identity.
  * `📊 Check Stats` - Instantly pulls the user's Albion API stats (PvE/PvP Fame).
  * `❌ Decline` - Rejects the application with a logged reason.

---

## 🚀 Core Systems & Automations
Powered by a robust `agenda.js` background scheduler, AFM works 24/7 without manual input:
* **🛡️ Smart Role Sync:** Periodically scans the Albion API. If a verified user leaves the faction or guild in-game, their Discord roles are automatically revoked after a 5-strike safety tolerance.
* **⚔️ Parallel Killboard Listener:** Fetches Albion events every 15 seconds, tracking faction kills, displaying juicy loot, and celebrating Faction MVPs.
* **⏱️ Tactical Smart Alarms:** A built-in timer system (`/timer`) that pings users/roles with a high-visibility Embed when crucial ZvZ objectives or outpost captures are due.
* **🧠 Faction Intel Broadcaster:** Randomly drops Albion lore, tactical advice, and hidden mechanics into the chat every 6-12 hours to educate the faction.

---

## 📜 Complete Command Module List

### 🛂 Identity & Security
* `/verify`, `/unverify`, `/sendverify` - Core faction verification workflow.
* `/admin-verify` - Manual override for administrators.
* `/register` - Links Discord account to Albion IGN.

### ⚔️ Warfare & Scouting (ZvZ)
* `/cta` - Call To Arms deployment and attendance tracking.
* `/scout` & `/scanner` - Report enemy movements and scan zone activity.
* `/bandit` - Track the Faction Warfare Bandit Assault status.
* `/rankbw` - Faction-specific leaderboard and participation tracking.
* `/route` - Quickly pull up safe travel routes.

### 💰 Faction Economy & Logistics
* `/factionbalance`, `/balance` - Check personal and faction treasury funds.
* `/donate`, `/subsidy` - Contribute to or request funds from the faction bank.
* `/invest`, `/splitloot` - Financial tools for party members.
* `/regear` - Request gear replacements after official CTA deaths.

### 📊 Intelligence & Analytics
* `/albionprofile`, `/stats` - View detailed player fame and kill/death ratios.
* `/price`, `/gold`, `/premium` - Real-time market prices across royal cities.
* `/resource`, `/combatfame` - Optimization tools for gathering and fame farming.

### 🎯 Minigames & Social Engagement
* `/bounty`, `/rob`, `/guard` - Social PvP economy minigames within Discord.
* `/adventure`, `/fishing`, `/work`, `/daily` - Idle RPG mechanics to earn bot currency.
* `/trivia`, `/gamble`, `/roll` - Server entertainment.
* `/albionmeme`, `/randomfact` - Pulls the latest memes from Reddit and game lore.

### ⚙️ Administration & Utilities
* `/admin`, `/setup-admin` - Configure bot behavior and channel routing.
* `/chat`, `/serverinfo`, `/userinfo` - Community management tools.
* `/timezone` - UTC to local time conversion for global factions.
* `/suggest` - Submit feedback to the Faction Leadership.

---

## 🛠️ Architecture
AFM uses a dynamic modular architecture. By simply changing the `FACTION_NAME` and `FACTION_COLOR` in the `.env` file, the bot completely rebrands itself to serve Bridgewatch, Martlock, Lymhurst, Fort Sterling, Thetford, or Caerleon.

<p align="center">
  <i>Developed with ❤️ for the Albion Online Faction Community.</i>
</p>
