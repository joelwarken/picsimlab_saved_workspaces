# PICSimLab Saved Workspaces

![PICSimLab](https://img.shields.io/badge/PICSimLab-Simulator-blue)
![License](https://img.shields.io/badge/license-MIT-green)

A collection of pre-compiled binary files (`.hex`/`.elf`) and workspace configurations for **[PICSimLab](https://github.com/lcgamboa/picsimlab)**.

---

## 🚀 Quick Start: Load a Binary in PICSimLab

### 1. Clone or Download

```bash
git clone https://github.com/yourusername/picsimlab_saved_workspaces.git
```

Or download the ZIP file and extract it.

---

### 2. Open PICSimLab

Launch the application.

---

### 3. Load the Workspace (Easiest Method)

- Go to **`File > Open Workspace`**
- Navigate to the desired project folder (e.g., `arduino_uno/`)
- Select the `.pzw` file
- Click **Open**
- Press **Run** ▶️

---

### 4. Manual Method: Load Only the Binary

If you prefer to configure the board manually:

**A. Select the Board**
- In PICSimLab, go to **`Board > Select Board`**
- Choose the correct board (e.g., Arduino Uno, PIC16F877A, etc.)

**B. Load the HEX/ELF File**
- Go to **`File > Load Hex`**
- Navigate to the project folder
- Select the `.hex` or `.elf` file
- Click **Open**

**C. Run**
- Press the **Power/Start** button or **`Ctrl + R`**

---

## 📁 Folder Structure

```
📦 picsimlab_saved_workspaces
 ┣ 📂 arduino_uno
 ┃  ┣ 📜 blink.hex
 ┃  ┗ 📜 arduino_uno.pzw
 ┣ 📂 pic16f877a
 ┃  ┣ 📜 lcd_display.hex
 ┃  ┗ 📜 pic16f877a_lcd.pzw
 ┗ 📜 README.md
```

Each folder contains:
- `.hex` or `.elf` – Pre-compiled binary (ready to load)
- `.pzw` – Full workspace (board + binary + peripherals)

---

## 💡 Tips

- **.pzw files** = workspace snapshot (recommended)
- **.hex/.elf files** = firmware only (requires manual board setup)
- Enable oscilloscope, serial terminal, or other tools via **`Tools`** menu
- Workspaces were saved using PICSimLab **0.8.x** – newer versions are fully compatible

---

## 📄 License

