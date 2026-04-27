# SRC-100 DrinkBox
### by [SimRacingCraftsmen](https://simracingcraftsmen.com)

<img width="690" height="460" alt="ChatGPT Image Apr 27, 2026, 01_47_19 PM" src="https://github.com/user-attachments/assets/41921673-f2be-45c5-ad21-2f0865e8d5bd" />


Control software for the **SRC-100 DrinkBox** — an in-cockpit hydration module for sim racing rigs. Bind any button, switch, button box input or keyboard key to control your drink pump directly from your cockpit.

---

## Features

- **Auto-connects** to the DrinkBox module on any COM port
- **Bind any input** — keyboard keys, button boxes, joystick buttons, pedal axes
- **Three modes per slot:**
  - **Toggle** — press once to turn on, press again to turn off
  - **Hold** — pump runs while input is held
  - **Burst** — pump fires for a set duration (ms) then stops automatically
- **All three slots can be bound simultaneously**
- **LED status indicator** with customisable colours per mode
- **Adjustable brightness** for the status LED
- **Minimizes to system tray (optional)** — runs silently in the background while racing
- **Settings saved automatically** — your bindings and colours are remembered
- **Hot-plug support** — connect devices before or after launching

---

## Requirements

- Windows 10 or Windows 11
- SRC-100 DrinkBox hardware module
- No additional software or drivers required

---

## Installation

1. Download the latest `DrinkBox.exe` from the [Releases](../../releases) page
2. Place it anywhere on your PC
3. Double-click to run

> **Note:** Windows SmartScreen may show a warning on first launch. Click **"More info"** then **"Run anyway"**. This is normal for unsigned software.

---

## How to Use

1. Plug in your SRC-100 DrinkBox module
2. Launch `DrinkBox.exe`
3. The app auto-connects — you'll see **Connected** in the status panel
4. Click **Bind Input** on any slot and press your desired button or key
5. The pump is now ready — minimize to tray and start racing

---

## LED Status (default)

| Colour | Meaning |
|--------|---------|
| 🔴 Slow red pulse | Module not connected — always red, cannot be changed |
| 🟢 Green | Ready |
| Custom colour | Pump active — shows the colour you chose for that slot |

### Customising LED Colours

Every slot has its own LED colour. To change it, simply **click the coloured dot (◉)** next to the slot status indicator (the one showing "unbound" or "ready"). This opens a colour picker where you can:

- Pick from a full colour grid
- Use the preset swatches
- Enter exact RGB values

Once you pick a colour, **the slot box in the app changes to that colour** so you always know which colour belongs to which function. When that slot's pump is active, the status LED on the module shows that same colour.

You can also customise the **idle colour** (shown when connected and ready but not pumping) by clicking the ◉ dot next to **"IDLE"** in the LED settings panel.

The **global brightness slider** adjusts the LED brightness for all functions at once.

---

## Support

For questions or support, send an email to support@simracingcraftsmen.com

---

*© SimRacingCraftsmen — All rights reserved*
