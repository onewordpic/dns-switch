**DNS Switch for macOS 🛡️**

A lightweight, native menu bar utility designed to instantly toggle between DNS providers, manage custom profiles, and flush the system DNS cache with a single click.

**🚀 Key Features**

One-Click Toggles: Effortlessly switch between Cloudflare, Google, AdGuard, and Quad9.

Custom Profiles: Add and save your own primary and secondary IPv4 addresses.

Global Hotkey: Use Cmd + Shift + D to toggle your DNS from anywhere on your Mac.

DNS Cache Flush: Includes a built-in utility to clear the system cache and force new routes.

Native & Fast: Written in Swift and SwiftUI for a minimal footprint and "Liquid Glass" aesthetic.

🛠️** Installation & First Run**

Because this app is unsigned and modifies system network settings, follow these steps to get started:

Download: Grab the DNS.Switch.zip from the Releases tab.

Move to Applications: Unzip and drag the app into your /Applications folder.

Bypass Gatekeeper: Right-click the app and select Open. You will see a warning; click Open again. (This is required for independent, unsigned software).

Permissions:

Admin Password: macOS will ask for your password when you connect/disconnect. This is required because changing DNS is a system-level action.

Accessibility: To use the Global Hotkey, you must allow the app in System Settings > Privacy & Security > Accessibility.

🔒 Privacy & Security
This app is open source. It works by acting as a native wrapper for the macOS /usr/sbin/networksetup command. It does not track your traffic or collect any data.
