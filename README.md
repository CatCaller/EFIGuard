# EfiGuard (19.02.2026)

This repository contains pre-compiled binaries for **EfiGuard**, a UEFI bootkit that disables PatchGuard and Driver Signature Enforcement (DSE) at boot time.

## Build Details
- **Compiler:** Visual Studio 2022
- **SDK:** Windows 11 SDK
- **BaseTools:** Compiled from latest TianoCore EDK II source (Feb 2026)
- **Architecture:** X64 (Release)

## Files Included
- `Loader.efi`: The EFI application used to load the driver.
- `EfiGuardDxe.efi`: The actual UEFI driver.
- `EfiDSEFix.exe`: Windows tool to toggle DSE after booting.

## Credits
Original project by [Mattiwatti](https://github.com/Mattiwatti/EfiGuard).
