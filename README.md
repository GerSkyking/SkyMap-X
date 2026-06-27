# SkyMap-X

**SkyMap-X** is a tactical tablet mod for Arma Reforger inspired by ATAK and Arma 3's CTab. It adds an enhanced multi-mode gadget interface with GPS/map display, live camera feeds, chat, BFT tracking, and customizable settings — all accessible in-game while remaining multiplayer compatible.

> **Status: Open Alpha — Features and keybinds are subject to change.**

---

## Features

### Tablet Modes
| Mode | Description |
|------|-------------|
| **GPS** | Interactive map with player position, zoom, and brightness control |
| **Feed** | Live PIP (Picture-in-Picture) camera feed viewer with camera rotation control |
| **Chat** | In-game messaging interface |
| **Settings** | Per-player UI and device configuration |

### Display Variants
| Variant | Description |
|---------|-------------|
| **Big Mode** | ~85% screen overlay — full UI |
| **Mini Mode** | ~40% screen — compact corner display |
| **Handheld** | Tablet held in hands with direct interaction |

### Device System
SkyMap-X introduces attachable **Item Devices** that can act as:
- **Camera (SCX)** — PIP camera with rotation, zoom, pitch control, and live feed streaming
- **Tracker (STX)** — BFT map marker that broadcasts the item's position
- **HeadCam** — Body-mounted camera attached to the character's head
- Devices can combine multiple roles (Camera + Tracker simultaneously)

### Blue Force Tracking (BFT)
- Tracker devices broadcast GPS positions across faction channels
- Compatible tracker positions appear as map markers on other players' tablets
- Channel-based visibility system — only see what you're authorized to receive

### PIP Camera Control
- Remote camera feeds viewable in the Feed tab
- Pan (yaw/pitch), zoom, and brightness adjustable from the tablet
- Camera state synchronized across the network

---

## Keybinds

> Keybinds are primarily intended for testing and may change.

### Power & Core

| Keybind | Action |
|---------|--------|
| `Ctrl + F1` | Power On / Off / Reset |
| `L Ctrl + 1` | GPS Mode |
| `Ctrl + Q` | Mini Mode (~40% screen) |
| `Ctrl + E` | Big Mode (~85% screen) |

### Map Controls

| Keybind | Action |
|---------|--------|
| `Page Up / Page Down` | Zoom In / Out |
| `L Ctrl + Page Up / Page Down` | Brightness Up / Down |
| `R Ctrl + Arrow Keys` | Pan Map *(WIP)* |

---

## Handheld Interaction

The tablet can be taken into the player's hands and operated directly via the interaction system.

**To access:** Hold **R (Inspect)** while holding the tablet.

Available interactions:
- Power On / Off
- Zoom adjustment
- Brightness adjustment
- Switch UI mode (GPS / Feed / Chat / Settings)

**Planned for Handheld Mode:**
- Map panning
- Full Big Mode feature parity in handheld

---

## Notes

- Some features behave differently depending on the active display variant (Handheld / Mini / Big).
- The mod is **multiplayer compatible** — the server remains authoritative.
- Device channels determine visibility; only devices broadcasting on a matching receive channel appear on a player's tablet.
- Settings are saved per player and persist across missions.

---

## Compatibility

- **Game:** Arma Reforger
- **Engine:** Enfusion
- **Multiplayer:** Yes (server-authoritative)

---

*SkyMap-X is under active development. Feature requests and bug reports are welcome.*
