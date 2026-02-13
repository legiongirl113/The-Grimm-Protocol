# 👁️ The Grimm Protocol

> *The Court is watching. Do you have what it takes to Ascend?*

**The Grimm Protocol** is a browser-based, local multiplayer "social stealth" game designed for mobile. It turns real life into a game board where players must secretly complete social tasks ("Fates") without getting caught by their friends or authority figures.

**[🔴 PLAY THE LIVE DEMO HERE](https://your-vercel-link-here.vercel.app)**
*(Replace the link above once you deploy!)*

---

## 💀 How It Works

This is not a game you play *on* your phone—it is a game you play *with* your phone. 

1. **The Ritual:** You open the app and draw a **Fate**.
   * *Example:* "Steal a pen from a teacher while holding your breath."
2. **The Action:** You must perform this action in real life, right now, without anyone noticing you are doing it for a game.
3. **The Ascension:** * **Success:** Tap "Task Complete" to fill your Ritual Bar and rank up (Initiate → Trickster → Monarch).
   * **Failure:** If someone catches you, you gain a **Strike** and must accept a public **Curse**.
4. **The End:** 3 Strikes and you are **BANISHED**.

## 🕸️ Features

* **⚡ Procedural Fate Engine:** Generates thousands of unique task combinations by mixing Verbs, Targets, and Constraints (e.g., *[Steal Item] + [From Best Friend] + [In Slow Motion]*).
* **🏆 Ascension System:** Visual progress bar and dynamic rank titles that change the game's color theme as you level up.
* **📱 Zero-Install:** Runs entirely in the browser (HTML/CSS/JS). No app store downloads needed.
* **🚫 Anti-Boredom:** Optimized for fast-paced play in social settings (school, parties, malls).

## 🛠️ Installation & Deployment

This game is built as a **Single File Application**. You do not need a backend server.

### Option 1: The Easy Way (Vercel/Netlify)
1.  Fork this repository.
2.  Log in to [Vercel](https://vercel.com) or [Netlify](https://netlify.com).
3.  Select "New Project" and choose your forked repository.
4.  Click **Deploy**.
5.  You will get a free URL (e.g., `grimm-protocol.vercel.app`) to share with friends.

### Option 2: Local Play
1.  Download the `index.html` file.
2.  Open it in any web browser (Chrome, Safari, etc.).

## 🔮 Customization

Want to add your own inside jokes or school-specific dares?

1.  Open `index.html`.
2.  Scroll down to the script section.
3.  Edit the `VERBS`, `TARGETS`, or `CURSES` arrays:

```javascript
const VERBS = [
    "High-five", 
    "Steal a pen from", 
    "Naruto run past" // <-- Add your own here
];
