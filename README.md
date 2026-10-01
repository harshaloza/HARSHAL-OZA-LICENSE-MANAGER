<div align="center">

<img src="https://harshal-oza-nx-license-website.pages.dev/nexora-mark.png" alt="" width="96" height="96">

# NEXORA

**NX Toolkit & Licence Manager — by Harshal Oza**

Professional tools for Siemens NX, and the Windows application that installs
them and manages your licence.

[**⬇ Download the latest version**](https://github.com/harshaloza/HARSHAL-OZA-LICENSE-MANAGER/releases/latest/download/HarshalOzaToolkitAndLicense.msi)
 · [Website](https://harshal-oza-nx-license-website.pages.dev/)
 · [All releases](https://github.com/harshaloza/HARSHAL-OZA-LICENSE-MANAGER/releases)
 · [Support](https://harshal-oza-nx-license-website.pages.dev/support/)

</div>

---

## What this repository is

This repository is the **download and update channel** for the NEXORA Windows
application. It holds the installer for each release and nothing else — there is
no source code here.

The application you install checks this channel on start-up, so once NEXORA is
installed you do not need to come back here: it updates itself, verifying each
download against the SHA-256 hash published with the release.

---

## Install it

1. Download **HarshalOzaToolkitAndLicense.msi** from the link above.
2. **Close Siemens NX** before running the installer.
3. Run it and approve the Windows administrator prompt.
4. Open NEXORA from the Start menu. The Dashboard shows your **Machine ID**.

The application itself is free to install, and so is NX Backup and Restore. The
NX tools need a licence, which you buy for the Machine ID shown on your
Dashboard — on the [website](https://harshal-oza-nx-license-website.pages.dev/buy/)
or inside the application.

**Requirements:** Windows 10 or 11, 64-bit · a supported Siemens NX installation
· about 200 MB of disk space · administrator rights to install. No separate
.NET runtime is needed.

---

## The tools it installs

| Tool | NX versions | Licence |
|---|---|---|
| NX Backup and Restore | Any installed NX version | Free |
| NX 12 Classic Toolbar | NX 12.0 | Paid |
| RenameCAMops | Any NX version | Paid |
| Cavity Mill Mixed Cutting | Any NX version | Paid |
| Material Size BOM | Any NX version | Paid |
| Setup Sheet | Any NX version | Paid |

One licence covers every tool on one computer. The Post Processor is listed in
the application as coming soon. Full descriptions:
[nexora tools](https://harshal-oza-nx-license-website.pages.dev/tools/).

---

## Your licence

- **One computer.** A licence is issued for the Machine ID of the computer you
  bought it for, and activates only there.
- **Move it yourself.** Use Transfer on the Subscription page to move a paid
  licence to another computer. The expiry date goes with it, unchanged.
- **Back it up.** Save Backup Key writes `HARSHAL_OZA_LICENSE.key`. Keep it: it
  restores your licence after a Windows reinstall, with no need to contact
  support.
- **Connect now and then.** Your licence renews itself quietly in the
  background. A computer that never reaches the internet keeps working for
  **five days** and then pauses until it connects once. The expiry date you paid
  for never changes, and `LICENSE NEEDS CHECKING` means exactly that — one
  connection, nothing to buy.

---

## Help

- **FAQ:** <https://harshal-oza-nx-license-website.pages.dev/faq/>
- **Support:** <https://harshal-oza-nx-license-website.pages.dev/support/>
- **Email:** harshaloza66@gmail.com — answered within 2 business days

Please include your NEXORA version (About page) and your NX version. **Never
send your licence key or payment details by email**; your payment reference is
enough.

> GitHub Issues here are not monitored for support. Use the email above.

---

## Legal

NEXORA is **independently developed software**. It is not affiliated with,
endorsed by or sponsored by Siemens Digital Industries Software. Siemens and NX
are trade marks of Siemens AG or its affiliates, used here only to describe
compatibility. NEXORA neither provides nor replaces a Siemens NX licence — you
need your own properly licensed NX installation.

The software is **licensed, not sold**, and is not open source. See
[LICENSE](LICENSE) in this repository, and the full terms:

- [Terms & Conditions](https://harshal-oza-nx-license-website.pages.dev/legal/terms/)
- [Refund & Cancellation Policy](https://harshal-oza-nx-license-website.pages.dev/legal/refund/)
- [Privacy Policy](https://harshal-oza-nx-license-website.pages.dev/legal/privacy/)

© 2026 Harshal Oza, trading as MoldXpert Technologies, Rajkot, Gujarat, India.
All rights reserved.

<sub>The installer is named `HarshalOzaToolkitAndLicense.msi` for historical
reasons: NEXORA was called Harshal Oza Toolkit & License until V2.1.27, and the
file name is what every installed copy already looks for when it updates.</sub>
