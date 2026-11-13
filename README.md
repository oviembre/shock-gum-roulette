# Shock Gum Roulette

A skater street dare game inspired by shocking gum pranks and Buckshot Roulette.  
Zero dependencies — one HTML file, open and play.

## Play locally
Open `index.html` in any browser.

## Deploy to GitHub Pages

```bash
git init
git add .
git commit -m "init: Shock Gum Roulette"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO.git
git push -u origin main
```

Then: **GitHub repo → Settings → Pages → Source: Deploy from branch → Branch: main → Save**

Your game goes live at: `https://YOUR_USERNAME.github.io/YOUR_REPO/`

## Deploy to Cloudflare Pages (Direct Upload — no GitHub needed)

1. Go to [https://dash.cloudflare.com/](https://dash.cloudflare.com/)
2. **Workers & Pages → Create → Pages → Upload assets**
3. Drag & drop `index.html`
4. Done — you get a `*.pages.dev` URL instantly

## Game Features

| | |
|---|---|
| 🎮 Style | LCD handheld aesthetic (Game & Watch / Tiger Electronics) |
| ⚙️ Core mechanic | Pick a gum → PULL SELF or HAND IT to rival |
| 💀 Trap types | Safe / Shock / Bug / Mega Trap / Lucky |
| 🛠️ Items | 8 skater-themed items across Common & Rare tiers |
| 🔊 Audio | Web Audio API synthesized 8-bit sound effects |
| 📦 Dependencies | Zero — single HTML file |
| 📱 Mobile | Touch-friendly, responsive layout |

### Item Reference

| Item | Name | Effect |
|------|------|--------|
| 🕶️ | SHADES | Peek at 1 random gum slot |
| 😷 | MASK | Remove 1 gum from box (unknown type) |
| 🛹 | DECK | Take 2 actions this turn |
| 🩹 | BANDAGE | Heal 1 ♥ |
| 🧤 | GLOVES | Block next trap (yourself only) |
| 📹 | DV CAM | Rival takes +1 damage this turn |
| 🧃 | JUICE | Gain a full bonus turn |
| 🪞 | MIRROR | Reflect rival's HAND IT back onto them |