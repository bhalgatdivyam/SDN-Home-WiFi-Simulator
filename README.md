# SDN in Action: Online Gaming on Home Wi-Fi

An interactive, single-page HTML simulation that demonstrates how **Software-Defined Networking (SDN)** prioritises online gaming traffic over bulk downloads on a home Wi-Fi network.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

## Scenario

> Rohan is playing an online match. His brother starts downloading a huge game update on the same Wi-Fi. Rohan's game lags and he loses. **Let's see how SDN fixes it.**

## 6-Step Walkthrough

| Step | Plane | What Happens |
|------|-------|-------------|
| 1 | Application | Game app sends a priority request |
| 2 | Control | SDN Controller checks QoS rules |
| 3 | Control | Controller monitors link loads |
| 4 | Control | Controller picks the best (least congested) path |
| 5 | Controller → Switches | Flow rules pushed via OpenFlow |
| 6 | Data | Switches forward packets — game runs lag-free! |

## Features

- **Animated SVG network diagram** with live packet dots, path highlighting, and switch flashing
- **Step-by-step controls** — Previous / Next / Auto-play / Restart + keyboard arrow keys
- **Game speed bar** showing QoS improvement at each step
- **Zero dependencies** — pure HTML + CSS + vanilla JS, no build step needed

## Usage

Just open the HTML file in any modern browser:

```
open "index.html"
```

Or double-click the file in your file explorer.

## License

MIT
