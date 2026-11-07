# idham-portfolio

Single-page interactive portfolio of **Muhammad Idham Akbar** — cybersecurity engineering student (D4 RKS, Politeknik Negeri Cilacap) and offensive security researcher.

The concept: a red paper gun ("the money gun") sprays portfolio slips across the screen. Every certificate, project, and contact is a slip you can fire, catch, and inspect.

## Features

- Inline-SVG spray gun with recoil, muzzle flash, shell ejection, smoke and cursor aim
- Slip physics: gravity, drag, sinusoidal sway, 3D paper-flip while flying, eased landing into the tray
- Secret terminal — press `~` and try `help`, `whoami`, `cat contact.txt`, `sudo hire-idham`
- Scroll-driven animations (progress bar, gun drift, staggered reveals) with full `prefers-reduced-motion` support
- Custom eased scrolling, keyboard spraying (hold Space), milestone slips with confetti

## Stack

Vanilla HTML + CSS + JavaScript. No frameworks, no build step, no external images — the gun is one inline SVG.

## Run locally

```bash
python3 -m http.server 8488
# open http://127.0.0.1:8488/
```

## Contact

- Email: idhamygy@gmail.com
- GitHub: [@net1nfect](https://github.com/net1nfect)
