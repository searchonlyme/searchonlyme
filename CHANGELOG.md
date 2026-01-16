# Changelog

All notable changes to SearchOnly will be documented in this file.

See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

## [1.0.0](https://github.com/AggOnly/searchonly/releases/tag/v1.0.0) (2026-01-17)

### Features

* **search**: AI-powered OnlyFans creator search with 2M+ profiles
* **filters**: Advanced filtering by ethnicity, body type, age, price, and more
* **photo-search**: Upload a photo to find similar creators using AI
* **near-me**: Location-based creator discovery
* **i18n**: Full internationalization support (EN, ES, PT, FR, DE, JA, KO)
* **seo**: Optimized meta titles and descriptions for all pages

### Performance

* Nginx reverse proxy with gzip compression and caching
* Cloudflare CDN integration
* Meilisearch for fast full-text search
* PostgreSQL with optimized indexes

### Security

* Content Security Policy (CSP) headers
* Rate limiting (30r/s API, 100r/s general)
* DMCA compliance and profile removal system
