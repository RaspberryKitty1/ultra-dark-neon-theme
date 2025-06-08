# Changelog

## [0.1.3] - 2025-06-08

### Note on Versioning

The version history was revised for clarity and better alignment with semantic versioning.  
Previously, versions were in the `0.0.x` range. These have been renumbered to `0.1.x` as follows:

| Old Version | New Version |
|-------------|-------------|
| 0.0.1       | 0.1.0       |
| 0.0.2       | 0.1.1       |
| 0.0.3       | 0.1.2       |
| 0.0.4       | 0.1.3       |

This changelog uses the updated numbering from this point forward.

### Changed

- Refined syntax highlighting for shell scripting: adjusted string and operator colors.
- Removed background colors from invalid token highlighting to reduce visual noise.
- Corrected the `editorIndentGuide` key (`background` → `background1`).

### Added

- Added syntax highlighting support for the following languages:
  - **Java**
  - **Kotlin**
  - **Swift**
  - **Rust**
  - **PHP**
  - **Ruby**

- Introduced customized color scopes for keywords, types/classes, and built-ins to enhance readability in these languages.
- Included a `LICENSE` file using the MIT License.
- Added the `repository` field in `package.json`:  
  [`https://github.com/RaspberryKitty1/ultra-dark-neon-theme`](https://github.com/RaspberryKitty1/ultra-dark-neon-theme)

### Notes

- This update significantly broadens language support while preserving the theme’s signature neon-dark style.
- Housekeeping improvements make the project more compliant with publishing standards and open-source best practices.

---

## [0.1.2] - 2025-04-14

### Added

- Included an image asset in the theme release to improve Marketplace and README visuals.

### Notes

- No changes to theme colors or syntax highlighting.
- Minor update focused on enhancing theme presentation.

---

## [0.1.1] - 2025-04-14

### Added

- Extended theme support for various language scopes including Python, Shell, JSON, NGINX, and HTML/XML tags.
- Added specific syntax highlighting for decorators, function calls, class/type names, import/export keywords, and control flow keywords.
- Introduced color customizations for invalid/deprecated tokens and escape sequences for better error visibility.

### Improved

- Enhanced overall color palette for improved readability and consistency across multiple languages.
- Added font styles (italic, underline, bold) for better syntax differentiation.

### Notes

- This release improves language support and visual clarity while maintaining the original neon-dark aesthetic.

---

## [0.1.0] - 2025-04-14

### 🎉 Initial Release

- First public release of the **Ultra Dark Neon** theme for VS Code.
- Introduced signature neon color palette on a pure black background.
- Language syntax support for:
  - JavaScript, Python, JSON, Bash  
  - HTML, CSS, Markdown  
  - C, C++, Go, Scala, Dart, Elixir, Clojure  
  - NGINX config files
- Specialized highlighting for:
  - Functions, variables, parameters, constants  
  - HTML tags and attributes  
  - Python decorators and docstrings  
  - C/C++ placeholders and preprocessors  
  - Markdown links, headings, quotes, and formatting
- Includes styling for structural UI elements like:
  - Activity bar, terminal, status bar, tabs, sidebar, popups
