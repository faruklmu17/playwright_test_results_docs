# 🔍 Playwright Browser Extension – Test Result Viewer

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](./LICENSE)

A Chrome extension that displays **Playwright test results** from a lightweight summary JSON file hosted on GitHub Pages, AWS S3, or any public URL. 

---

## 📦 Features (v1.8)

- ✅ **Smart Badge**: Shows passed/failed count (e.g., `42/1`) directly on the extension icon.
- ✅ **Failed Test Details**: Shows the names of failing tests right in the popup.
- ✅ **Dark/Light Mode**: Automatically adapts to your system's theme preference for optimal visibility.
- ✅ **AWS S3 Support**: Deploy test results to AWS S3 with complete setup instructions.
- ✅ **Private Repo Support**: Monitor private repositories by hosting your summary on GitHub Pages.
- ✅ **New Summary Format**: Supports a lightweight `test-summary.json` for lightning-fast updates.
- ✅ **Live Polling**: Auto-refreshes every **1 minute** to stay in sync with CI/CD.
- ✅ **Auto-Link Conversion**: Automatically converts GitHub UI links (`/blob/`) to raw links.
- ✅ **Error Awareness**: Shows a Gray `?` badge and a "No Tests Detected" warning if your test run crashes or has a syntax error.
- ✅ **Backward Compatible**: Still supports the full Playwright JSON report format.

---

## 🔧 How to Configure It

Visit our **[Official Documentation Page](https://faruklmu17.github.io/playwright_test_results_docs/browser_extension_support.html)** for the complete setup guide.

---

## 🔐 Security & Privacy Notes

* ✅ Your data stays local — the extension only fetches the JSON you configure.
* ✅ Does **not** require access to tabs or page content.
* ⚠️ Do **not** include sensitive data (like API keys or credentials) in your test results.

---

## 📄 License

This project is licensed under the MIT License — see the [LICENSE](./LICENSE) file for full details.

---

## 🙌 Credits

Created by [Faruk Hasan](https://github.com/faruklmu17)
Powered by [Playwright](https://playwright.dev/)

---

## ⚠️ Disclaimer

This extension is not affiliated with or endorsed by Microsoft or Playwright.
