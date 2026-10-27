# Hi, I'm Fokhrol Islam 👋

Founder and lead developer of **[Sabaq (ছবক)](https://sabaaq.com)**, a madrasa and school management platform used by **700+ institutions across Bangladesh**.

I build software for people who were never served by software before: madrasa teachers, office staff and guardians who run everything on paper, in Bangla, often on a cheap Android phone and a slow connection.

## What I work on

- **Sabaq web** · Laravel multi-tenant SaaS, one isolated site and database per institution, 370+ live tenants on one fleet, zero-downtime overlay deployments across the whole fleet from a single script.
- **Sabaq app** · Flutter app on the [Play Store](https://play.google.com/store/apps/details?id=com.sabaaq.sabaq_app) for staff and guardians: attendance, fees, results, prints, push notifications, offline-first writes, Bangla / English / Arabic.
- **Sabaq API** · a Sanctum `/api/v1` layer that mirrors the web application field for field, with contract gates that fail the build when the web changes under it.
- **Free trial pipeline** · self-serve trial sites created automatically, WhatsApp OTP verification, promotion to a paid tenant with one command.
- **WordPress & Elementor** · dozens of client sites, custom plugins (WooCommerce deposits, tier pricing, Brevo flows), speed and security clean-ups.

## Stack

`PHP` `Laravel` `MySQL` `Flutter` `Dart` `WordPress` `Elementor` `WooCommerce` `Linux / cPanel` `Bash` `Node.js`

## Open source

| Repo | What it is |
|---|---|
| [sabaq-madrasa-management](https://github.com/fokhrolislam/sabaq-madrasa-management) | Product overview, architecture notes and release history of Sabaq |
| [php-number-format-dart](https://github.com/fokhrolislam/php-number-format-dart) | PHP's `number_format($x, 2)` reproduced exactly in Dart, so a Flutter app never shows a different paisa than its Laravel backend |
| [bangla-utils-dart](https://github.com/fokhrolislam/bangla-utils-dart) | Bangla digits, month and weekday names, short taka amounts, and crash-safe parsing of API values that may arrive as strings |
| [flutter-risk-scans](https://github.com/fokhrolislam/flutter-risk-scans) | Small static scanners that catch the crashes Flutter apps only show in production: raw `as Map` casts, `AsyncValue.value`, missing double-submit guards |
| [wordpress-field-notes](https://github.com/fokhrolislam/wordpress-field-notes) | Measured WordPress, WooCommerce and Elementor traps from live client sites, with drop-in fixes (WP Super Cache basket leak guard, slug guard, WPCode from WP-CLI) |
| [site-visual-scan](https://github.com/fokhrolislam/site-visual-scan) | Playwright scan of every sitemap URL that reports pages which look broken: giant emoji, overflow, broken or oversized images, failed assets |
| [portfolio](https://github.com/fokhrolislam/portfolio) | Products, client builds, security clean-ups and tooling I have delivered |

## Contact

- 🌐 [sabaaq.com](https://sabaaq.com)
- 📱 [Sabaq on Play Store](https://play.google.com/store/apps/details?id=com.sabaaq.sabaq_app)
- 📍 Dhaka, Bangladesh
