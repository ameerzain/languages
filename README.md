# 🌍 Languages JSON Dataset

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

### JavaScript / TypeScript

```js
import languages from './languages.json';

console.log(languages);
```

### Python

```python
import json

with open('languages.json') as f:
    languages = json.load(f)

print(languages)
```

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
