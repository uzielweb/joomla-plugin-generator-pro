# Joomla Extension Generator Professional

A powerful browser-based generator for Joomla 5/6 Plugins and Modules. Create standardized, MVC-compliant extensions with professional architecture.

## 🚀 Launch Generator
[Open Generator Tool](https://uzielweb.github.io/joomla-plugin-generator-pro/)

## ✨ Key Features
- **Modern Joomla 5/6 Architecture**: Uses the Service/Provider pattern and native Joomla namespaces.
- **Modular Templates**: Quick starts for Content, System, User, and Custom plugins.
- **Multilingual Support (i18n)**: Automatically generates `.ini` language files for PT, EN, and ES.
- **Field Generator**: Visual creator for XML Form Fields (text, select, color, media, etc.).
- **Advanced Logic**:
    - **MVC/Service Pattern**: Proper separation of concerns.
    - **AJAX Support**: Native Joomla AJAX interface integration.
    - **Database (JDatabaseQuery)**: Secure database interaction boilerplate.
- **Developer UI**: Dark-mode interface with real-time code preview and file tree.

## 📁 Generated Structure
```text
plg_type_name/
├── services/           # Provider.php (Joomla 5+ standard)
├── src/                # Extension Namespace
├── tmpl/               # Frontend layouts
├── language/           # Multilingual .ini files
└── name.xml           # Manifest file
```

## 🛠 How to Use
1. Set the extension type (Module or Plugin).
2. Define namespaces and metadata.
3. Configure parameters and form fields.
4. Preview and download the installable `.zip` package.

---
Developed by [Antigravity AI](https://github.com/uzielweb)
