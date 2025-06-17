# HoYoFetch Bot

A simple Revolt bot that fetches the latest Hoyoverse gift codes using the Hoyocode API.

---

### Credits

> ⚠ This bot uses the [Hoyocode API](https://github.com/seriaati/hoyo-codes) provided by `seriaati/hoyo-codes` to retrieve the latest codes.

---

### Commands

- `!fetchGI` — Get the latest Genshin Impact codes.
- `!fetchHSR` — Get the latest Honkai: Star Rail codes.
- `!fetchZZZ` — Get the latest Zenless Zone Zero codes.

---

### Notes

1️⃣ **Game Coverage:**  
Currently supports Genshin Impact, Honkai: Star Rail, and Zenless Zone Zero.  
_Tears of Themis and Honkai Impact 3 are not supported due to API limitations._

2️⃣ **Server Compatibility:**  
The bot only works for Global servers (Asia, America, EU, and HW/TW/MO servers).  
⚠ Mainland China servers (Irminsul, Celestia) are not supported.

3️⃣ **Code Update Timing:**  
The bot uses the Hoyocode API, so there may be a short delay before new codes appear depending on when the API updates.

4️⃣ **Funny Reward Messages:**  
Sometimes you may see messages like:  
> “We asked Paimon and she replied that it's probably primogems.”  
This simply means the API found a code but didn't provide reward details. The code is still valid and redeemable.

5️⃣ **Downtime / Support:**  
If the bot goes offline, please contact `suichanwaa` — most likely the MacBook running the bot was closed or rebooted 😄

---

### Deployment

1. Install Node.js (v16 or higher)
2. Install dependencies:  
```bash
npm install
