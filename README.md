# DNS Switch for macOS

A lightweight, native menu bar utility designed to **instantly toggle between DNS providers**, **manage custom profiles**, and **flush the system DNS cache** with a single click.

---

### 🚀 Key Features

* **One-Click Toggles:** Effortlessly switch between predefined presets including **Cloudflare**, **Google**, **AdGuard**, and **Quad9**.
* **Custom Profiles:** Configure, save, and manage dedicated **primary and secondary IPv4** server addresses.
* **Global Hotkey:** Trigger instant DNS switching from anywhere on macOS via `Cmd + Shift + D`.
* **DNS Cache Flush:** Includes a built-in utility to clear the local macOS resolver cache (`dscacheutil`) and force active routing updates.
* **Native & Lightweight:** Built entirely with **Swift** and **SwiftUI** for a minimal CPU/memory footprint and seamless macOS desktop integration.

---

### 🛠️ Installation & First Run

Because the application is distributed unsigned and directly interacts with system network interfaces, follow these standard steps:

1. **Download:** Download `DNS.Switch.zip` from the latest **Releases** tab.
2. **Install:** Extract the archive and move **DNS Switch.app** to your `/Applications` directory.
3. **Bypass Gatekeeper:** 
   * Right-click (or Control-click) **DNS Switch.app** and select **Open**.
   * When prompted with the unsigned developer dialog, click **Open** to confirm.
4. **Permissions Setup:**
   * **Admin Privileges:** macOS will request administrator credentials when applying changes, as modifying network resolvers requires elevated rights.
   * **Accessibility Access:** To enable the global hotkey shortcut, grant access under **System Settings** → **Privacy & Security** → **Accessibility**.

---

### 🔒 Privacy & Security Architecture

* **Transparent Execution:** Fully open-source and auditable.
* **Native Wrappers:** Operates strictly as a clean GUI wrapper around the standard macOS `/usr/sbin/networksetup` binary.
* **Zero Telemetry:** No background data collection, no external API calls, and zero traffic inspection. All configurations remain local to your machine.
