# Cisco CLI Basics

---

## CLI vs GUI

**CLI (Command Line Interface)**
- Primary method used to configure Cisco devices
- Offers full control and detailed access to device configuration

**GUI (Graphical User Interface)**
- Uses graphical elements such as buttons and menus
- Easier for beginners but often limited compared to CLI

---

## Connecting to a Cisco Device

### Console Connection

- Direct manual connection from a computer to the device
- Used for initial setup and troubleshooting

**Requirements**
- Rollover (console) cable
- USB or serial adapter (if needed)
- Terminal emulator (e.g., PuTTY)

---

### Terminal Emulator Settings (Serial Connection)

| Setting | Value |
|------|------|
| Speed (Baud Rate) | 9600 |
| Data Bits | 8 |
| Stop Bits | 1 |
| Parity | None |
| Flow Control | None |

---

## Cisco IOS Command Modes

---

### User EXEC Mode

**Prompt**
```text
Router>
