# killign-rEFInd

A minimal, black & white rEFInd theme.

![screenshot](screenshot.png)

---

## 📦 Installation

### 1. Clone the Repository

```bash
git clone https://github.com/killign/killign-rEFInd.git
cd killign-rEFInd
```

### 2. Copy Theme to rEFInd Directory

Make sure your EFI partition is mounted. Common paths include `/boot/efi`, `/boot`, or `/efi`.

```bash
sudo mkdir -p /boot/efi/EFI/refind/themes/killign-rEFInd
sudo cp -r * /boot/efi/EFI/refind/themes/killign-rEFInd/
```

> Adjust the destination path if your EFI is mounted elsewhere.

---

## ⚙️ Configuration

### 1. Edit `refind.conf`

```bash
sudo nano /boot/efi/EFI/refind/refind.conf
```

### 2. Add the Theme Include

Add this line at the bottom:

```ini
include themes/killign-rEFInd/theme.conf
```

### 3. Save and Reboot

```bash
sudo reboot
```

---

## ✅ Result

Your rEFInd bootloader should now display the **killign** theme — clean, minimal, and monochrome.

---

## 💬 Feedback

Feel free to open an issue or submit a pull request if you'd like to contribute or suggest improvements.

---
