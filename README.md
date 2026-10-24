# Photo2Tegram • Apple Shortcuts Link Generator

A clean, mobile-friendly iOS-styled web application built with Tailwind CSS that allows users to install the **Photo2Tegram** Apple Shortcut and securely configure their Telegram credentials.

---

## 🔗 Official Shortcut Link

- **iCloud Shortcut**: [https://www.icloud.com/shortcuts/4b961690cb304bd7a08312b3d2f17337](https://www.icloud.com/shortcuts/4b961690cb304bd7a08312b3d2f17337)

---

## 🚀 How It Works

1. **Step 1: Install Shortcut**  
   Tap **"Get 'Photo2Tegram' Shortcut"** to download and install the shortcut directly from iCloud into the iOS Shortcuts app.

2. **Step 2: Enter Telegram Credentials**  
   Enter your:
   - **Telegram Bot Token** (from `@BotFather`)
   - **Chat ID** (from `@userinfobot` or your chat)

3. **Step 3: Run & Configure**  
   Tap **"Generate Link"** &rarr; Tap the prominent green **"Open in Apple Shortcuts"** button.  
   This triggers:
   ```text
   shortcuts://run-shortcut?name=Photo2Tegram&input=text&text={"botToken":"...","chatID":"..."}
   ```
   The shortcut parses the JSON dictionary and saves the credentials securely on your device.

---

## 🌐 Free Hosting Options

This app is a 100% self-contained static HTML file (`index.html`):

- **Netlify Drop** *(Fastest — 10 seconds)*: Drag and drop this folder to [app.netlify.com/drop](https://app.netlify.com/drop).
- **GitHub Pages**: Push this repo to GitHub & enable Pages in Settings.
- **Cloudflare Pages**: Drag and drop via [Cloudflare Pages](https://pages.cloudflare.com).
