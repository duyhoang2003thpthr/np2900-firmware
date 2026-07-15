# MTC NP2900 — Firmware

Official firmware release repository for the **MTC NP2900** (Mono Laser Printer).

## Update via Application (Recommended)

Use the **MTC NP2900 Update** application for Windows: the app automatically detects the printer,
checks the version, and downloads/installs the latest firmware. Digital signature verification
is performed automatically at every step.

## Manual Update

1. Download the `capt_update_vX.Y.Z_ENCRYPTED.bin` file from the **Releases** section (latest version).
2. Turn off the printer. Connect the USB cable to the computer.
3. **Hold the Paper button** on the printer while turning on the power — the computer will
   display a USB drive named `LBP2900-FW`.
4. Copy the downloaded `.bin` file to that drive. The printer automatically verifies,
   updates, and restarts.
5. Open the `LBP2900_LOG.TXT` file on the drive (re-enter update mode) to view the
   version and update history.

## Safety

- Release files are **encrypted and digitally signed**; the printer accepts only genuine
  firmware — corrupted or modified files are rejected, so the printer cannot be damaged
  by an incorrect update file.
- The `manifest.json` / `manifest.json.sig` files in each Release are intended for the
  update application (version and integrity checks); manual users do not need to use them.

---
© MTC. For warranty inquiries, please contact the place of purchase.
