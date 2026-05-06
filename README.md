# Joomla Plugin Generator Pro

A modern, browser-based scaffolding tool for Joomla 5 and 6 plugins.

## Features

- **Premium UI**: Dark-mode, high-fidelity interface inspired by professional developer tools.
- **Modern Joomla Architecture**: Generates code 100% compliant with Joomla 5/6 standards (PSR-4, Dependency Injection, Services).
- **Group-specific Events**: Automatically provides common events based on the selected plugin group (System, Content, User, Finder, etc.).
- **Multilingual UI**: Support for Portuguese (BR), English (GB), and Spanish (ES).
- **Standalone**: Works entirely in the browser using JSZip for package generation.

## How to Use

1. Fill in the plugin information (Name, Vendor, Version).
2. Select the plugin group and the events you want to implement.
3. (Optional) Configure parameters.
4. Preview the generated code.
5. Click **Download ZIP** to get your ready-to-install Joomla plugin.

## Technical Details

- **Namespaces**: Uses PSR-4 namespaces (`Vendor\Plugin\Group\Name`).
- **Entry Point**: Implements the modern `services/provider.php` pattern.
- **Class Structure**: Extends `CMSPlugin` and uses the modern Event Dispatcher.

## License

MIT License.
