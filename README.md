# 🎹 Keytar Rokker

**© TrojanNemo, 2015–2025**  
*Dedicated to the rhythm gaming community*

---

## About

**Keytar Rokker** began as a personal project to learn how to parse **Rock Band 3 keytar data** and explore what could be done with it outside the game.

While the result is fairly polished (and dare I say, nice), it is ultimately a passion project.

Enjoy it for what it is:  
**another fun way to play with Rock Band equipment and custom songs.**

> ⚠️ This project is for fun and experimentation.  
> Expect some latency and a limited feature set — not perfection.

---

## Supported Hardware

As of this writing, Keytar Rokker works with:

- 🎸 **Xbox 360 Rock Band 3 keytar**  
  Connected wirelessly via the **Microsoft Xbox 360 Wireless Adapter for Windows**

- 🎹 **MIDI keyboard or RB3 keytar**  
  Connected via MIDI cable to the **Xbox 360 MIDI Pro Adapter (MPA)**

If you’ve confirmed compatibility with a different setup, I’d love to hear about it.

You can also play using:

- 🖱️ Mouse  
- ⌨️ Keyboard  

(Details below.)

---

## How to Play

Keytar Rokker supports **three different input methods**, each with slightly different behavior.

---

### 1️⃣ Keytar or MIDI Keyboard

#### Key Behavior

- All **25 keys** behave exactly as they do in Rock Band 3  
- Velocity-sensitive keys control note volume  
- Supports real-time octave shifting  

#### Wireless Xbox 360 Keytar Controls

- **Overdrive button** → Simulated sustain pedal  
- **Start** → Play / Pause  
- **Back** → Load song  
- **Left / Right** → Change sound type  
- **Up / Down** → Change octave  

#### QuickAccess Buttons

- **A / B / X / Y** instantly switch between preset sound + octave combinations  
- Customize via:  
  `Options → Customize QuickAccess buttons`

#### MIDI Pro Adapter Notes

- Only the **25 piano keys** transmit via MIDI  
- Button input must be done using the **MPA itself**

---

### 2️⃣ Mouse Controls

- Click keys to play notes  
- Click and drag for **glissando**  
- **Spacebar** simulates sustain pedal  
- Click sustain pedal icon to lock/unlock  
- Mouse wheel scrubs forward/backward in time  
- All UI buttons are clickable and include tooltips  

---

### 3️⃣ Keyboard Controls

- All 25 keys are mapped to keyboard shortcuts  
- View shortcuts:  
  `Options → Show keyboard shortcuts`  
- Customize shortcuts:  
  `Options → Customize keyboard shortcuts`  
- Spacebar functions as sustain pedal  
- Mouse wheel scrubs time, same as mouse mode  

---

## 🎼 Play-Along Mode

Enable Play-Along Mode by:

- Pressing **F5**  
- Selecting `Options → Play-along mode`  
- Dragging a **CON / LIVE** file onto Keytar Rokker  

### Features

- Plays audio while displaying the **Expert chart**  
- Chart visualization is best-effort and **not accurate enough for testing songs**  
- Supports:  
  - Expert  
  - Hard  
  - Medium  
  - Easy  
  - Right Hand Animation  
  - Left Hand Animation (if charted)  
- Switch charts **in real time** without stopping playback  

### Visual Customization

- Resize note highway by dragging the bottom-right edge  
- Adjust scroll speed using the scroll wheel  
  - Higher value = slower scroll  
  - Lower value = faster scroll  

---

## Options

- **Play-along mode** – Enables CON/LIVE playback  
- **Show range marker** – Displays current range shift from MIDI chart  
- **Silence keys track** – Mutes original keys audio if multitrack  
- **AutoPlay with chart** – Plays displayed chart automatically  
- **Show scroll speed control**  
- **Show chart selection dropdown**  

---

## Volume Control

- Adjust playback volume via the knob on the far right  
- Click the volume button next to the first LCD panel to mute temporarily  

---

## Sounds & Octaves

### Sounds

- Real **Steinway & Sons Model B** piano samples (all 88 keys)  
- **40 additional MIDI sounds**  
- Change sounds using:  
  - UI buttons  
  - Left / Right on keytar or MPA  

### Octaves

- 25 playable keys at a time  
- Full 88-key range supported:  
  - Lowest: **C1**  
  - Highest: **C8**  
- A0, A#0, and B0 are not playable (keytar limitation)  
- Change octaves using:  
  - UI buttons  
  - Up / Down on keytar or MPA  

---

## Customization

Most customization lives in the **`/res`** folder.

### Visuals

- Replace images (keep same name, size, format)  
- Customize:  
  - Range marker color  
  - LCD backlight colors (8 presets)  
  - Key highlight colors  

### Configuration

- Settings stored in `keytar.config`  
- Colors use hex format with alpha: `#AARRGGBB`  
- Set key colors to `#00000000` for no visual effect  

### Audio Samples

- Located in `/samples`  
- Supports `.ogg` (preferred) and `.wav`  
- Files labeled A0 (0) → C8 (87)  
- OGG recommended for performance (Quality 5 used by default)  

---

## Sustain Pedal — Your Lifeline

When things go wrong:

- Stuck notes  
- AutoPlay confusion  
- Audio overlap  

👉 **Click the sustain pedal icon**

Disabling sustain immediately cancels:

- Pending samples  
- Stuck notes  
- Active key presses  

Use it to reset and keep playing.

---

## Background Mode

When minimized, Keytar Rokker lives in the **system tray** and continues responding to keytar input — you don’t even need to look at it.

---

## Final Notes

This is a **fun side project**, not a professional instrument emulator.

Expect quirks. Enjoy the chaos. Play loud.

🎶 **Have fun!**

---

## Credits

- DJ Shepherd — X360 library  
- raynebc — MIDI expertise  
- Mark Heath — NAudio.MIDI  
  http://naudio.codeplex.com/  

- Ian Luck — BASS audio library  
  http://www.un4seen.com/  

- Bernd Niedergesaess — BASS.NET  
  http://bass.radio42.com/  

- SlimDX Group — SlimDX  
  http://www.slimdx.org/  

- David — Keytar input assistance  
  http://www.dwsk.co.uk/  

- Stephen Toub — MidiPlayer  
  http://blogs.msdn.com/b/toub/  

- University of Iowa — Piano samples  
  http://theremin.music.uiowa.edu/MISpiano.html  
