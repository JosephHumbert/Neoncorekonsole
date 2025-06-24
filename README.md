# 🎮 NeonCoreKonsole — HTML5 Fantasy Console

https://traditionpixel.itch.io/neoncorekonsole

A retro-style mini game console that runs entirely in your browser. Just drop a ZIP cartridge and start playing.

## 💾 Cartridge = 1 JS game file + up to 10 PNG sprites
No server, no install — 100% client-side.

## 🧱 Core Features
Fixed resolution (320×180), sharp pixel rendering

Gamepad-style controls (keyboard, mouse, touch)

ZIP cartridge loader: 1 JS + max 10 PNG files

Simple API: canvas, sprites[], input, drawImage(), loop()

Instant load via eval() (no sandboxing)

## 🚫 Limitations
Invalid if ZIP has >10 PNG or ≠1 JS

No external network access

Executes JS as-is (potentially unsafe)

## 🔁 How to Use
Open the console page in your browser

Click “Insert Cartridge (.zip)”

Enjoy your game instantly!
