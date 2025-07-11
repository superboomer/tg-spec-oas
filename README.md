# Telegram API Specifications

[![Update Specifications](https://github.com/superboomer/tg-spec-oas/actions/workflows/update-tg-specs.yml/badge.svg)](https://github.com/superboomer/tg-spec-oas/actions/workflows/update-tg-specs.yml)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Automatically updated Telegram API specifications in OpenAPI 3.1.0 format.

## 📋 Description

This repository contains up-to-date specifications for:
- **Bot API** - HTTP interface for creating Telegram bots
- **Gateway API** - HTTP interface for The Telegram Gateway

Specifications are automatically updated every 12 hours using [`tg-spec-cli`](https://github.com/superboomer/tg-spec-cli).

## 📁 Repository Structure

```
📁 Repository Root
├── botapi-latest.json          # 🆕 Latest Bot API version
├── gateway-latest.json         # 🆕 Latest Gateway API version
├── 📁 botapi/                  # 📚 Bot API version archive
└── 📁 gateway/                 # 📚 Gateway API version archive
```

## 📦 Download Latest Specifications

You can download the latest Bot API or Gateway API specification files directly using `curl`:

### Bot API
```sh
curl -L -o botapi-latest.json \
  https://raw.githubusercontent.com/superboomer/tg-spec-oas/master/botapi-latest.json
```

### Gateway API
```sh
curl -L -o gateway-latest.json \
 https://raw.githubusercontent.com/superboomer/tg-spec-oas/master/gateway-latest.json
```

## 📚 Useful Links

- [Telegram Gateway API Documentation](https://core.telegram.org/gateway/api)
- [Introduction to Gateway](https://core.telegram.org/gateway)
- [Telegram Bot API Documentation](https://core.telegram.org/bots/api)
- [Introduction to Bots](https://core.telegram.org/bots)
- [tg-spec-cli](https://github.com/superboomer/tg-spec-cli) - Utility for generating specifications
- [OpenAPI Specification](https://swagger.io/specification/)

## 📄 License

This project is distributed under the MIT License. See [LICENSE](LICENSE) file for details.

---

**Note**: This repository contains automatically generated specifications. For official documentation, always refer to [core.telegram.org](https://core.telegram.org/bots/api).