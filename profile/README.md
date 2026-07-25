# infiniti-mainline

Mainline Linux and U-Boot for the **OnePlus 15** (CPH2749, Qualcomm
SM8850 "Kaanapali" — internally codenamed *infiniti*).

- [`linux`](https://github.com/infiniti-mainline/linux) — device work on
  top of FantomTchi7's kaanapali mainline tree: display (cmd-mode
  DSC 1.2), touch, Wi-Fi/Bluetooth, battery telemetry.
- [`u-boot`](https://github.com/infiniti-mainline/u-boot) — mainline
  U-Boot chainloaded from ABL: panel console, read-only UFS, boots NixOS
  via extlinux.

Upstream-first: everything here is aimed at eventual submission to
mainline Linux and U-Boot. Contributions welcome — see each repo's
CONTRIBUTING.md (DCO, no CLA).
