# Legacy PHP Routing Fix

Debugging and stabilizing a legacy PHP hospital system by fixing critical routing failures.

This project reverse-engineers undocumented legacy PHP code to identify and repair broken routing logic that caused HTTP 404 errors across multiple internal modules.

---

## Problem

The legacy hospital system suffered from:

- undocumented PHP codebase
- broken internal routing
- incorrect URL path handling
- multiple HTTP 404 failures in production

These issues disrupted internal workflows used by hospital staff.

---

## Fix

The project restored system stability by:

- reverse-engineering the legacy PHP application structure
- reconstructing routing logic and internal URL handling
- fixing broken links and path resolution
- stabilizing modules without rewriting the entire system

---

## Architecture

```
Client Browser
      ↓
Apache Web Server
      ↓
Legacy PHP Application
      ↓
MySQL Database
```

Routing logic is handled through **Apache mod_rewrite** and corrected internal path resolution.

---

## Tech Stack

- PHP (Legacy)
- Apache
- MySQL
- URL Routing / mod_rewrite

---

## Project Structure

```
src/        refactored PHP source code
config/     application configuration
.htaccess   routing and URL rewrite rules
```

---

## License

MIT
