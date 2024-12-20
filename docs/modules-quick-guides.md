# Module Guides

This document provides detailed installation, configuration, and usage instructions for key Drupal 9 modules recommended for a university website.

---

## Table of Contents

1. [Menu Link Attributes](#menu-link-attributes)
2. [Search API](#search-api)
3. [XML Sitemap](#xml-sitemap)
4. [Media Library](#media-library)
5. [Image Optimize](#image-optimize)
6. [Content Moderation](#content-moderation)
7. [Accessibility Tools](#accessibility-tools)
8. [TFA (Two-Factor Authentication)](#tfa-two-factor-authentication)
9. [Honeypot](#honeypot)

---

## 1. Menu Link Attributes

### Description
Enables adding custom attributes (e.g., `title`, `rel`, `class`, `id`) to menu links for enhanced navigation and accessibility.

### Installation
```bash
composer require drupal/menu_link_attributes
```
```bash
drush en menu_link_attributes -y
```

### Configuration
1. Navigate to `Structure > Menus`.
2. Edit any menu item.
3. Use the additional fields (e.g., `Title`, `Class`) to customize attributes.

---

## 2. Search API

### Description
Provides a flexible framework for creating search solutions with advanced filtering and faceting capabilities.

### Installation
```bash
composer require drupal/search_api
```
```bash
drush en search_api -y
```

### Configuration
1. Navigate to `Configuration > Search API`.
2. Add a new search server and configure an index.
3. Use views to display search results with filters and faceted search options.

---

## 3. XML Sitemap

### Description
Automatically generates XML sitemaps for better search engine indexing.

### Installation
```bash
composer require drupal/xmlsitemap
```
```bash
drush en xmlsitemap -y
```

### Configuration
1. Navigate to `Configuration > XML Sitemap`.
2. Configure settings for content types, taxonomy, and menu links.
3. Submit the sitemap URL to search engines (e.g., Google Search Console).

---

## 4. Media Library

### Description
Enhances media management by providing an intuitive media library interface.

### Installation
```bash
composer require drupal/media_library
```
```bash
drush en media_library -y
```

### Configuration
1. Navigate to `Content > Media`.
2. Add and organize media assets using folders or categories.
3. Configure the Media Library widget for content editors.

---

## 5. Image Optimize

### Description
Optimizes images for faster loading and better performance.

### Installation
```bash
composer require drupal/imageapi_optimize
```
```bash
drush en imageapi_optimize -y
```

### Configuration
1. Navigate to `Configuration > Media > Image Toolkit`.
2. Set up optimization pipelines for WebP conversion and lazy loading.

---

## 6. Content Moderation

### Description
Provides workflows for content review and approval processes.

### Installation
```bash
composer require drupal/content_moderation
```
```bash
drush en content_moderation -y
```

### Configuration
1. Navigate to `Configuration > Content moderation`.
2. Define workflows (e.g., Draft, Review, Published).
3. Assign workflows to content types.

---

## 7. Accessibility Tools

### Description
Helps ensure compliance with accessibility standards (e.g., WCAG 2.1).

### Installation
```bash
composer require drupal/accessibility
```
```bash
drush en accessibility -y
```

### Usage
1. Run accessibility checks on your content using the module’s reporting tools.
2. Fix highlighted issues to improve site accessibility.

---

## 8. TFA (Two-Factor Authentication)

### Description
Adds two-factor authentication to enhance account security.

### Installation
```bash
composer require drupal/tfa
```
```bash
drush en tfa -y
```

### Configuration
1. Navigate to `Configuration > People > TFA`.
2. Enable TFA for specific roles or users.
3. Configure authentication methods (e.g., OTP, email verification).

---

## 9. Honeypot

### Description
Prevents spam submissions on forms by adding a hidden field trap.

### Installation
```bash
composer require drupal/honeypot
```
```bash
drush en honeypot -y
```

### Configuration
1. Navigate to `Configuration > People > Honeypot`.
2. Enable Honeypot on specific forms.
3. Adjust settings for maximum protection (e.g., time-based validation).

---

This document ensures you can effectively install, configure, and utilize each module for a seamless university website experience. Feel free to expand with additional modules or deeper configuration details as needed.
