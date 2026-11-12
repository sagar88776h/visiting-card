# Digital visiting card – MD. Shimal Badsha

QR-based digital visiting card for MD. Shimal Badsha, Branch Sales Executive, Bandhan Bank (Gakulnagar branch).

## Files
- `index.html` – the card page people see after scanning the QR
- `qr.html` – open `/qr.html` on the live site, paste the live link, download the QR image for printing

## How to edit
Open `index.html` and change only the `P = { ... }` block near the bottom:
- `instagram`, `facebook`, `googleReview` – paste links (leave `""` to hide)
- `whatsapp` – the number that has WhatsApp (country code, no +)
- `photo` – put `shimal.jpg` in this folder and set `photo: "shimal.jpg"`
- `services` – the topics shown under "Ask me about"

## Deploy
Import this repo on Vercel (Framework preset: Other). No build step needed.
