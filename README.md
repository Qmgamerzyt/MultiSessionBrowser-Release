# MultiSession Browser

A lightweight, privacy-focused Android browser with isolated browsing sessions, desktop mode, and smart URL bar suggestions. Built for users who need multiple independent browsing environments on a single device.

## What is MultiSession Browser?

MultiSession Browser is an Android web browser that creates fully isolated browsing sessions. Each session has its own cookies, storage, and history — perfect for managing multiple accounts, separating work and personal browsing, or testing websites in different states.

## Key Features

- **Session Isolation** — Each browsing session is completely separated with its own cookies, local storage, and cache. Switch between sessions without cross-contamination.
- **Desktop Mode** — Toggle desktop user-agent with automatic viewport scaling and MutationObserver-based viewport injection for full desktop site rendering.
- **Smart URL Bar Suggestions** — Real-time suggestions as you type, including search predictions, browsing history, and bookmarks. Powered by Google search.
- **Multi-Tab Browsing** — Open and manage multiple tabs within each session. Tab counter and quick-switch interface for efficient navigation.
- **Built-in Download Manager** — Download files directly in the browser with progress tracking and background download support.
- **Dark & Light Themes** — System-adaptive, light, and dark themes for comfortable browsing in any lighting condition.
- **Privacy Controls** — Enable or disable JavaScript, third-party cookies, safe browsing, and zoom on a per-session basis.
- **Custom User Agent** — Set a default user-agent mode or define your own custom user-agent string.
- **Session Management** — Create, rename, and delete sessions. Clear cookies, storage, cache, or history per session.

## Download

**[Download Latest APK](https://github.com/Qmgamerzyt/MultiSessionBrowser-Release/releases)**

**Requirements:** Android 9.0 (API 28) or higher

## How to Install

1. Download the APK from the [releases page](https://github.com/Qmgamerzyt/MultiSessionBrowser-Release/releases)
2. Open the downloaded APK file
3. Tap **Install** and wait for the installation to complete
4. Open MultiSession Browser from your app drawer

## Why Use MultiSession Browser?

- **Multiple Accounts** — Log into the same website with different accounts simultaneously without logging out.
- **Web Development & Testing** — Test websites in different session states, user-agents, and configurations.
- **Privacy Separation** — Keep your browsing activities separated between different contexts.
- **Lightweight** — Minimal resource usage compared to running multiple browser apps.

## Permissions

| Permission | Purpose |
|-----------|---------|
| `INTERNET` | Browse the web and load online content |
| `WRITE_EXTERNAL_STORAGE` | Save downloaded files (Android 9-9) |
| `FOREGROUND_SERVICE` | Keep downloads running in the background |

## Technology

- Built with native Android (Kotlin)
- Uses Android WebView for rendering
- Room database for history and bookmarks
- Coroutines for async operations
- Material Design 3 UI components

## Copyright

Copyright QM Gamerzメyt

## License

This is a private project. All rights reserved.
