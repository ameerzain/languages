# 🌍 Languages JSON Dataset

![JSON](https://img.shields.io/badge/Format-JSON-blue)
![Languages](https://img.shields.io/badge/Languages-100%2B-green)
![Open Source](https://img.shields.io/badge/Open%20Source-Yes-brightgreen)
![License](https://img.shields.io/badge/License-MIT-yellow)
![Repo Size](https://img.shields.io/github/repo-size/ameerzain/languages)

A clean, lightweight, and developer-friendly JSON dataset containing a curated list of world languages with their standardized language codes.

This repository is designed to be **simple**, **reusable**, and **framework-agnostic**, making it ideal for applications that need language selection, localization, translation, or internationalization support.

---

## 📦 Contents

* `languages.json` – A JSON array of language objects with:

  * `name` – Human‑readable language name
  * `code` – Standard language code (commonly used in APIs and i18n libraries)

Example:

```json
{
  "name": "English",
  "code": "en"
}
```

---

## ✨ Features

* ✅ 100+ commonly used global languages
* ✅ Clean and consistent JSON structure
* ✅ Ready to use in frontend & backend projects
* ✅ Suitable for dropdowns, filters, and localization settings
* ✅ Easy to extend and maintain

---

## 🚀 Use Cases

This dataset can be used in:

* 🌐 Internationalization (i18n) & localization
* 📝 Language selector dropdowns
* 🤖 Translation & AI applications
* 📱 Mobile and web apps
* 🧩 Configuration files
* 🔌 API integrations (Google Translate, OpenAI, etc.)

---

## 🛠️ How to Use

## 🌐 Public API / Raw JSON Access

This repository can be used as a **public read-only API** by accessing the raw JSON file hosted on GitHub.

### 🔗 Raw JSON URL
[https://raw.githubusercontent.com/ameerzain/languages/main/languages.json](https://raw.githubusercontent.com/ameerzain/languages/main/languages.json
)

### 📌 Usage Examples

#### JavaScript (Fetch API)

```js
fetch('https://raw.githubusercontent.com/ameerzain/languages/main/languages.json')
  .then(response => response.json())
  .then(data => console.log(data));
```

#### Python (Fetch API)

```python
import requests

url = "https://raw.githubusercontent.com/ameerzain/languages/main/languages.json"
languages = requests.get(url).json()

print(languages)
```
ℹ️ Note:
This dataset is served via GitHub Raw and is suitable for light to medium usage.
For high-traffic production environments, consider caching or self-hosting the file.

### HTML (Dropdown Example)

```html
<select>
  <option value="en">English</option>
  <option value="fr">French</option>
</select>
```

---

## 📊 Data Format

```json
[
  {
    "name": "English",
    "code": "en"
  },
  {
    "name": "French",
    "code": "fr"
  }
]
```

---

## 🤝 Contributing

Contributions are welcome!

You can:

* Add missing languages
* Improve naming consistency
* Add region‑specific variants
* Fix incorrect codes

Please open a pull request or raise an issue for discussion.

---

## 📄 License

This project is open‑source and available under the **MIT License**.

You are free to use, modify, and distribute it in personal or commercial projects.

---

## 👤 Author

**Ameer Zain**
GitHub: [https://github.com/ameerzain](https://github.com/ameerzain)

If you find this repository useful, consider giving it a ⭐ to support the project.

---

Happy coding! 🚀
