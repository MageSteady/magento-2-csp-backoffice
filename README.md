

# MageSteady CSP Backoffice

## Description

The MageSteady CSP Backoffice module for Magento 2 allows you to manage and edit the Content Security Policies (CSP) directly from the admin panel, instead of modifying XML files.

This module is particularly useful for teams where non-developers manage tagging strategies through tools like Google Tag Manager or directly from the Design configuration in the Magento backoffice.

## Installation

1.  Require the module via Composer: `composer require magesteady/csp-backoffice`
2.  Enable/install the module: `bin/magento setup:upgrade`

## Usage

1. Navigate to the Magento admin panel.
2. Go to MageSteady > Security > Content Security Policy.
3. Add, edit, or remove CSP policies as needed. You can also import from existing XML rules.
4. Go to Stores > Configuration > MageSteady > CSP Backoffice.
5. Enable the module.
6. Flush the cache.

## Compatibility

-   Magento Open Source/Adobe Commerce: 2.4.x and above

## Code Quality

This module is built with respect for Magento 2’s coding guidelines, ensuring:
- Stable, maintainable codebase.
- Compatibility with future Magento updates.
- Clean implementation following Magento's architectural principles.

This module is also thoroughly optimized for performance and should not impact your stores' general speed.

## Contributing

Contributions, issues, and feature requests are welcome!

Feel free to open an issue or submit a pull request on GitHub at [https://github.com/MageSteady/magento-2-csp-backoffice](https://github.com/MageSteady/magento-2-csp-backoffice).

## License

This module is licensed under the GNU General Public License v3.0. Refer to the LICENSE file for details.

## Disclaimer

Use this module at your own risk.

While it provides convenience, improper configuration may lead to security vulnerabilities.

We advise you to read this documentation for a better understanding of CSP security concerns: https://cheatsheetseries.owasp.org/cheatsheets/Content_Security_Policy_Cheat_Sheet.html

We strongly encourage you to forbid CSP rules edition by people that are unaware of the security consequences through ACL roles.

Please always keep your store up to date to prevent any unwanted modification of this module's database table.

Always test changes thoroughly in a staging environment before deploying to production.
