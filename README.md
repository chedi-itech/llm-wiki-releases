# LLM Wiki — Releases

Official installers and the auto-update feed for **LLM Wiki**, a Windows desktop
Markdown knowledge base with a built-in AI assistant.

> This repository hosts only the published builds and the updater manifest. The
> application source lives in a separate, private repository.

---

## Download

**[⬇️ Download the latest version](https://github.com/chedi-itech/llm-wiki-releases/releases/latest)**

On the latest release, download the installer and run it:

| File | Use |
|------|-----|
| `LLM.Wiki_<version>_x64-setup.exe` | **Recommended** — NSIS installer |
| `LLM.Wiki_<version>_x64_en-US.msi` | MSI (for managed/enterprise installs) |

The installer upgrades any existing installation in place. Your notes, settings,
and theme are preserved (settings live in your user profile, not the install
folder).

---

## Automatic updates

LLM Wiki updates itself. Once you are running a version with the built-in
updater, you don't need to come back here:

- On launch, the app checks for a newer signed release and shows an **“Update
  available”** banner — click **Update now** to download, install, and relaunch.
- You can also check on demand any time by clicking the **version badge** in the
  top bar.

Updates are cryptographically signed; the app verifies each one against an
embedded public key before installing, so a tampered build can't be pushed to
you.

---

## Requirements

- **Windows 10 / 11 (64-bit)**
- **WebView2 runtime** — preinstalled on current Windows; the installer adds it
  if missing.

---

## Verifying a download (optional)

Each release includes `latest.json`, which carries the minisign signature the
app uses to verify the installer. The updater performs this check automatically;
manual verification isn't required for normal use.

---

*Releases here are produced automatically from the private source repository.*
