# Legacy PHP Routing Fix
**Structural refactoring and reverse-engineering of undocumented legacy PHP systems to resolve critical routing failures.**

## Overview
This project focuses on the recovery and optimization of a legacy PHP-based hospital management system. By reverse-engineering undocumented source code, the project identified and resolved critical routing failures and broken internal links. The refactoring process restored system stability, improved navigation logic, and extended the lifecycle of the existing infrastructure without requiring a complete rewrite.

## Technical Analysis

| Challenge | Solution |
| :--- | :--- |
| **Undocumented Code** | Performed full-scale reverse-engineering to map system architecture. |
| **Routing Failures** | Reconstructed URL handling and internal path logic. |
| **Legacy Compatibility** | Maintained support for older PHP environments while improving efficiency. |
| **System Reliability** | Restored broken functional modules within a high-stress clinical environment. |

## Tech Stack

| Component | Technology |
| :--- | :--- |
| **Backend** | Legacy PHP |
| **Web Server** | Apache (mod_rewrite) |
| **Database** | MySQL |
| **Methodology** | Reverse-engineering & Structural Refactoring |

## Project Structure

| Directory / File | Description |
| :--- | :--- |
| `src/` | Refactored PHP source files with corrected routing logic. |
| `config/` | Updated server and application configurations. |
| `.htaccess` | Managed URL rewriting and path redirection rules. |

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
