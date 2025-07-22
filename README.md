# 🧭 Anchor

**Anchor** is a minimalist browser homepage and PWA for ADHD brains.  
It shows you one task and a countdown timer — nothing else.  
Every time you open a new tab, you're reminded of what you're doing and how long you committed to focus.

---

## 💡 Why?

- ADHD brains struggle with time blindness, task-switching, and reorienting after distractions.
- Anchor acts as a **cognitive anchor** — a ritualized point of return whenever your brain derails.
- It's not an extension. It's a website. Set it as your homepage, or install it to your device.

---

## 🔧 Features

- [x] One active task input  
- [x] Optional “why am I doing this?” note  
- [x] 25-minute countdown timer  
- [x] Task lock during countdown  
- [x] Timer based on real time (not intervals)  
- [x] PWA: installable on iOS/macOS via Safari  
- [x] LocalStorage persistence  

---

## 🛠 Stack

- Next.js 15 (App Router)  
- Tailwind CSS  
- TypeScript  
- shadcn/ui  
- LocalStorage (no backend)  

---

## 🚀 Development

```bash
pnpm install
pnpm dev
```
Then open http://localhost:3000

📱 Safari Setup

macOS:

Safari → Preferences → General
Set homepage and new tab to: https://anchor.yourdomain.com
iOS:

Open the site in Safari
Tap “Share” → Add to Home Screen
Launch from Home Screen for full-screen mode
🔐 Privacy

No accounts, no analytics, no data leaves your device.
This is a tool for your brain, not a product.

📄 License

MIT — feel free to fork, remix, and share.

