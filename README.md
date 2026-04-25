# @ochag/family

> Lightweight shared package for **Ochag** reminders, family safety rules, and vault payload helpers.

[![License: Apache 2.0](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](LICENSE)
[![Package](https://img.shields.io/badge/npm-%40ochag%2Ffamily-orange)](https://npm.pkg.github.com)

## Роль репозитория

Этот репозиторий хранит небольшой standalone package `@ochag/family`, а не полный end-user продукт.

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

## Что экспортируется

- `reminders` — upcoming/overdue reminder helpers
- `safety` — child-safety policy helpers
- `vault` — vault payload serialization helpers
- `types` — public family domain types

## Часть экосистемы

- [ceoclaw](https://github.com/alexgrebeshok-coder/ceoclaw) — private dashboard product repo
- [pyrfor](https://github.com/alexgrebeshok-coder/pyrfor) — runtime / engine repo
- [freeclaude](https://github.com/alexgrebeshok-coder/freeclaude) — main FreeClaude CLI / workspace
- [ceoclaw-freeclaude](https://github.com/alexgrebeshok-coder/ceoclaw-freeclaude) — lightweight shared FreeClaude package repo
