<div align="center">

# 🌍 i18nrs

[![Crates.io](https://img.shields.io/crates/v/i18nrs)](https://crates.io/crates/i18nrs)
[![Crates.io Downloads](https://img.shields.io/crates/d/i18nrs)](https://crates.io/crates/i18nrs)
![Crates.io License](https://img.shields.io/crates/l/i18nrs)
[![made-with-rust](https://img.shields.io/badge/Made%20with-Rust-1f425f.svg?logo=rust&logoColor=white)](https://www.rust-lang.org/)
[![Rust](https://img.shields.io/badge/Rust-1.79%2B-blue.svg)](https://www.rust-lang.org)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/wiseaidev)

[![Join our Discord](https://dcbadge.limes.pink/api/server/b5JbvHW5nv)](https://discord.gg/b5JbvHW5nv)

<!-- absolute url for docs.rs cause assets is excluded from crate -->
![logo](https://raw.githubusercontent.com/opensass/i18n-rs/refs/heads/main/assets/logo.webp)

</div>

## 🎬 Demo

<!-- absolute url for docs.rs cause assets is excluded from crate -->
![i18n-rs-demo](https://raw.githubusercontent.com/opensass/i18n-rs/refs/heads/main/assets/demo.gif)

| Framework | Live Demo |
| --- | --- |
| Yew | [![Netlify Status](https://api.netlify.com/api/v1/badges/b213132a-d8b6-494b-8a5f-7290682a1a95/deploy-status)](https://i18n-rs.netlify.app) |
| Dioxus | TODO |
| Leptos | TODO |

## 📜 Intro

i18nrs is a lightweight and powerful internationalization library for Wasm-based frameworks like **Yew**, **Dioxus**, and **Leptos**. It provides seamless tools to manage translations, change languages, and localize your applications.

## 🤔 Why Use i18nrs?

The following features make i18nrs a must-have for your Wasm-based projects:

1. **🌐 Multi-Language Support**: Effortlessly support multiple languages in your application with a flexible configuration system.
1. **📦 Easy Integration**: Simple setup and integration with Wasm frameworks like Yew, Dioxus, and Leptos.
1. **🔄 Dynamic Language Switching**: Change languages on the fly and persist the selection using `LocalStorage` or `SessionStorage`.
1. **⚙️ JSON-Based Translations**: Load translations from JSON files with full validation.
1. **🗝️ Nested Key Translation**: Use nested keys like `menu.file.open` for organized and structured translations.

## 🛠️ Features

- **Configuration Management**: Centralized configuration for languages and translation data.
- **Browser Storage Support**: Store and retrieve the selected language using `LocalStorage` or `SessionStorage`.
- **Fallback System**: Automatically falls back to the default language if a key is missing.
- **Advanced Key Resolution**: Supports dot-separated keys for nested translations (e.g., `settings.profile.name`).

## 📚 Yew Usage

<!-- absolute url for docs.rs cause YEW.md is not included in crate -->
Refer to [our guide](https://github.com/opensass/i18n-rs/blob/main/YEW.md) for integrating i18nrs with your Yew app.

## 🧬 Dioxus Usage (TODO)

<!-- absolute url for docs.rs cause DIOXUS.md is not included in crate -->
Refer to [our guide](https://github.com/opensass/i18n-rs/blob/main/DIOXUS.md) for integrating i18nrs with your Dioxus app.

## 🌱 Leptos Usage (TODO)

<!-- absolute url for docs.rs cause LEPTOS.md is not included in crate -->
Refer to [our guide](https://github.com/opensass/i18n-rs/blob/main/LEPTOS.md) for integrating i18nrs with your Leptos app.

## 🤝 Contributions

Contributions are welcome! Whether it's bug fixes, feature requests, or adding support for new frameworks, we would love your help to make i18nrs better.

1. Fork the repository.
1. Create a new branch for your feature/bugfix.
1. Submit a pull request for review.

## 📜 License

<!-- absolute url for docs.rs cause LICENSE.md is not included in crate -->
i18nrs is licensed under the [MIT License](https://github.com/opensass/i18n-rs/blob/main/LICENSE.md). You are free to use, modify, and distribute this library in your projects.
