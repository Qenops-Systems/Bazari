# Bazari
![Bazari Theme Screenshot](screenshot.jpg)

**A Modern WordPress theme for WooCommerce, online stores, and modern e-commerce websites.**

Bazari is a modern, versatile e-commerce theme designed to create professional online stores with seamless shopping experiences. It provides a dedicated foundation for Qenops-specific customization while taking advantage of Blocksy's modern design system, performance features, WooCommerce integration, and WordPress block editor compatibility.

Designed with online businesses and digital storefronts in mind, Bazari provides a flexible foundation for building modern, responsive, and professional e-commerce websites with WordPress and WooCommerce.

## Features

* Built as a **Blocksy child theme**
* Modern and responsive design foundation
* Advanced **WooCommerce** support through Blocksy
* Compatible with the WordPress Block Editor
* Designed for online stores and e-commerce websites
* Suitable for:

  * Online shops
  * Retail businesses
  * Product catalogs
  * E-commerce brands
  * Digital stores
  * Small and growing businesses
  * Product-focused websites
* Maintains compatibility with the Blocksy customization ecosystem
* Provides a dedicated foundation for Qenops-specific customizations
* Keeps custom modifications separate from the parent theme

## Why Bazari?

Bazari is designed to provide a clean and flexible foundation for building modern e-commerce websites without modifying the Blocksy parent theme directly.

By using a child-theme architecture, Bazari can introduce Qenops-specific customizations while continuing to benefit from the functionality provided by Blocksy.

The theme is particularly suited to websites where **WooCommerce and product presentation are central to the website experience**.

## Parent Theme

Bazari is a child theme of **Blocksy**.

The Blocksy parent theme provides the underlying theme framework, design system, customization options, and WooCommerce integration upon which Bazari is built.

### Important

Bazari requires the **Blocksy parent theme** to be installed.

The parent theme must remain installed while Bazari is active.

Bazari does not replace the Blocksy parent theme; instead, it extends it through the WordPress child-theme architecture.

## Requirements

* WordPress
* PHP 7.0 or later
* Blocksy parent theme
* WooCommerce for e-commerce functionality

Additional plugins may be required depending on the functionality implemented on a particular website.

## Installation

### 1. Install Blocksy

Install the Blocksy parent theme through the WordPress administration dashboard or upload it to:

```text
wp-content/themes/blocksy/
```

**Do not delete the Blocksy parent theme after installing Bazari.**

### 2. Install Bazari

Upload Bazari to:

```text
wp-content/themes/Bazari/
```

Alternatively, install the theme through:

**Appearance → Themes → Add New → Upload Theme**

### 3. Install WooCommerce

For e-commerce functionality, install and activate WooCommerce.

### 4. Activate Bazari

From the WordPress dashboard:

**Appearance → Themes → Bazari → Activate**

Bazari will become the active theme while Blocksy remains installed as the parent theme.

## Theme Structure

Bazari is intentionally maintained as a lightweight child theme.

```text
Bazari/
├── functions.php
├── screenshot.png
└── style.css
```

The child theme inherits the functionality and styling framework of Blocksy unless specific functionality is overridden or extended by Bazari.

## Customization

Bazari can be customized using the functionality provided by Blocksy and WordPress.

Depending on the website configuration, customization can include:

* Site layout
* Typography
* Colors
* Header and footer
* Navigation
* WooCommerce layouts
* Product pages
* Shop and catalog pages
* Blog layouts
* Responsive settings

Qenops-specific functionality and customizations can be added to the child theme without modifying the Blocksy parent theme directly.

## Development

Bazari is maintained as a child theme to keep custom development separate from the Blocksy parent theme.

This allows the parent theme to be updated while reducing the risk of losing customizations made specifically for Bazari.

### Repository

The source code for Bazari is maintained by **Qenops** on GitHub:

**Qenops Systems — Bazari**

https://github.com/Qenops-Systems/Bazari

## Version

**Current Version:** 1.0.3

## Compatibility

### PHP

Bazari requires:

**PHP 7.0 or later**

### WordPress

Bazari is designed for modern WordPress installations and is compatible with the WordPress Block Editor.

### WooCommerce

Bazari is designed to work with WooCommerce and benefits from Blocksy's WooCommerce integration.

## License

Bazari is distributed under the:

**GNU General Public License v3.0 or later**

See the `LICENSE` file for the complete license terms.

## Credits

### Qenops

Bazari is developed and maintained by **Qenops**.

Website:

https://qenops.co.ke

### Blocksy

Bazari is built as a child theme of **Blocksy**.

Blocksy provides the underlying theme framework and functionality upon which Bazari is built.

Please refer to the Blocksy project for information regarding the parent theme's licensing, documentation, and original components.

---

**Bazari**
Developed by **Qenops**
A modern foundation for WordPress e-commerce websites.
