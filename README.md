<p align="center">
  <img src="preview.png" alt="Sway Desktop Preview" width="800"/>
</p>
# 🛠 dotfiles

My handpicked **[Arch Linux + Sway]** window manager environment — minimal, keyboard-driven, and designed for productivity.

---

## 🎹 Mod Key
- `$mod = Mod4` → usually the **Super/Windows** key

---

## 🖥️ Launch Apps

| Keybind            | Action                                   |
|--------------------|-------------------------------------------|
| `Ctrl + Alt + T`   | Launch terminal (`kitty`)                 |
| `$mod + Space`     | Launch app menu (`wofi --show drun`)      |
| `$mod + L`         | Lock screen                               |
| `$mod + Shift + C` | Reload config                             |
| `$mod + Shift + Q` | Exit Sway (with `swaynag` confirmation)   |
| `$mod + Esc`       | Restart Waybar                            |

---

## 🚀 Workspace Management

### 🔄 Switch to Workspace
| Keybind        | Workspace              |
|----------------|------------------------|
| `$mod + 1..0`   | Go to workspace 1–10  |

### 🧳 Move to Workspace
| Keybind              | Action                            |
|----------------------|-----------------------------------|
| `$mod + Shift + 1..0`| Move window to workspace 1–10     |

---

## 📦 Window Focus & Movement

| Keybind                   | Action                      |
|---------------------------|-----------------------------|
| `$mod + Arrow Keys`       | Move focus (← ↓ ↑ →)        |
| `$mod + Shift + Arrows`   | Move window (← ↓ ↑ →)       |
| `$mod + A`                | Focus parent container      |

---

## 🪟 Window Layout

| Keybind                | Action                |
|------------------------|-----------------------|
| `$mod + S`             | Stacking layout       |
| `$mod + W`             | Tabbed layout         |
| `$mod + E`             | Toggle split layout   |
| `$mod + F`             | Toggle fullscreen     |
| `$mod + Shift + Space` | Toggle floating       |
| `$mod + Shift + -`     | Send to scratchpad    |
| `$mod + -`             | Toggle scratchpad     |

---

## ↔️ Resize Mode

### 🎯 Enter:
- `$mod + R`

### ⬅️ In Resize Mode:

| Key         | Action                     |
|-------------|----------------------------|
| Arrow Keys  | Shrink/Grow container      |
| Return / Esc| Exit resize mode           |

---

## 🔊 Volume & 🔆 Brightness

| Key                     | Action             |
|-------------------------|--------------------|
| `XF86AudioRaiseVolume`  | Volume +5%         |
| `XF86AudioLowerVolume`  | Volume -5%         |
| `XF86AudioMute`         | Toggle mute        |
| `XF86AudioMicMute`      | Toggle mic mute    |
| `XF86MonBrightnessUp`   | Brightness +5%     |
| `XF86MonBrightnessDown` | Brightness -5%     |

---

## 🧰 Utilities

| Keybind             | Action                                 |
|---------------------|----------------------------------------|
| `$mod + Shift + S`  | Screenshot (area) using custom script  |
| `$mod + V`          | Clipboard history (via `wofi + cliphist`) |

---

## 🖥️ Display & Wallpaper

- Output: `eDP-1` → `1920x1200`
- Wallpaper: `~/Pictures/wallpapers/a_river_near_a_town-moonlight.jpg`
- Adaptive Sync: ❌ Off

---

## 💤 Idle Behavior

- Lock after **5 min**
- Turn off display after **10 min**
- Lock before suspend

---

## 🖱️ Input Settings

### Touchpad:
- Tap-to-click: ✅
- Natural Scroll: ✅
- Middle Emulation: ✅

### Keyboard:
- Layout: `pt`

---

## 🎨 UI Theme

- **Font:** Fira Code Nerd Fonts Bold 18
- **Borders:** 4px
- **Gaps:** inner 7px, outer 5px

### 🎨 Colors

| Element            | Color     |
|--------------------|-----------|
| Background         | `#3c3836` |
| Text / Focus Color | `#ebdbb2` |
| Unfocused Window   | `#453a3a` |

---

## 🚀 Autostart Apps

- `waybar`
- `xwayland`
- `thinkpadbacklight.service`
- `gammastep -O 3200`
- `pulseaudio`
- `cliphist` (text & image clipboard history)

---

## ✅ Tips

- Run `swaymsg -t get_outputs` to list your monitor names.
- Check `man 5 sway`, `sway-input`, and `sway-bar` for advanced options.
- Customize your bar and menu with **Waybar**, **Wofi**, and **CSS**.

---

Feel free to star, fork, or adapt to your workflow 🚀
