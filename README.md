# USB Drivers for Android

**Windows program that connects your Android phone to a PC** – it detects the phone, installs the official USB driver and fixes the most common connection problems.

## ⬇️ Download

**[Download the latest version](../../releases/latest)** → `UsbDriversForAndroid.exe` (no installation needed, Windows 10/11 64-bit)

## What it does

- Detects the phone as soon as it is plugged in and shows its mode: file transfer (MTP), photos (PTP), USB debugging (ADB), fastboot, tethering and service modes (Qualcomm EDL, MediaTek, Samsung Download).
- Installs the official, signed **Google USB Driver** – also for phones of other brands (Xiaomi, OnePlus, Motorola, …). The download checksum is verified.
- Repairs the Windows MTP driver, removes stale device entries, restarts the ADB server.
- Android Platform-Tools (adb, fastboot) with one click, plus wireless debugging pairing.
- Links only to official driver pages of manufacturers.
- 16 languages. No ads, no tracking.

Works together with the **USB Drivers** app for Android, which shows on the phone why the computer can't see it (for example a charge-only cable).

## First start

The program is not code-signed yet, so Windows SmartScreen may show *"Windows protected your PC"*. Click **More info → Run anyway**. Installing drivers asks for administrator rights (UAC prompt).

Verify the file (optional) in PowerShell:

```powershell
Get-FileHash .\UsbDriversForAndroid.exe -Algorithm SHA256
```

and compare it with `SHA256SUMS.txt` attached to the release.

## Privacy

[Privacy policy](https://kaczorek89.github.io/usb-drivers-for-android/privacy-policy.html) · Contact: scizers@gmail.com

---

## 🇵🇱 Po polsku

**Program dla Windows, który łączy telefon z Androidem z komputerem** – wykrywa telefon, instaluje oficjalny sterownik USB i naprawia najczęstsze problemy z połączeniem.

**[Pobierz najnowszą wersję](../../releases/latest)** → `UsbDriversForAndroid.exe` (bez instalacji, Windows 10/11 64-bit).

Przy pierwszym uruchomieniu Windows SmartScreen może pokazać „System Windows ochronił ten komputer” – kliknij **Więcej informacji → Uruchom mimo to**. Instalacja sterowników prosi o uprawnienia administratora.
