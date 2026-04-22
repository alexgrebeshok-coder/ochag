# @ochag/family — Очаг AI

> **Семейный AI-компаньон**: Memory, Family Calendar, Voice Profile, Vault, Telegram Mini App

[![License: Apache 2.0](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](LICENSE)
[![Package](https://img.shields.io/badge/npm-%40ochag%2Ffamily-orange)](https://npm.pkg.github.com)

## Пакет

```ts
import { FamilyPlan, getUpcomingReminders, isTopicAllowed } from '@ochag/family'
```

## Модули

| Модуль | Описание |
|--------|----------|
| `types` | FamilyPlan, FamilyRole, VaultCategory, domain interfaces |
| `reminders` | getUpcomingReminders, getOverdueReminders, formatReminderMessage |
| `safety` | getEffectiveBlockedTopics, isTopicAllowed, hasExceededScreenTime |
| `vault` | parseVaultPayload, serializeVaultPayload, vaultSummary |

## Установка

```bash
npm install @ochag/family --registry=https://npm.pkg.github.com
```

## Часть экосистемы CEOClaw

- [@ceoclaw/engine](https://github.com/alexgrebeshok-coder/ceoclaw-engine) — AI engine (Apache 2.0)
- [@ochag/family](https://github.com/alexgrebeshok-coder/ceoclaw-ochag) — Семья (Apache 2.0)
- [@freeclaude/coder](https://github.com/alexgrebeshok-coder/ceoclaw-freeclaude) — Coder CLI (Apache 2.0)
