[![Platform](https://img.shields.io/badge/Platform-%20Android%20%7C%20Android%20TV%20%7C%20iOS%20%7C%20macOS%20%7C%20Windows%20%7C%20Linux-informational.svg)](https://github.com/LXST-CODE/v2RayTun/wiki/home)
[![Android](https://img.shields.io/badge/Android-7%2B-informational.svg)](https://developer.android.com/about/versions/nougat)
[![iOS](https://img.shields.io/badge/iOS-16.0%2B-informational.svg)](https://go.dev/wiki/MinimumRequirements)
[![macOS](https://img.shields.io/badge/macOS-13.0%2B-informational.svg)](https://go.dev/wiki/MinimumRequirements)
[![Windows](https://img.shields.io/badge/Windows-10%2B-informational.svg)](https://docs.flutter.dev/reference/supported-platforms)
[![Arch](https://img.shields.io/badge/Arch-x64-informational.svg)](https://go.dev/wiki/MinimumRequirements)
[![Chat on Telegram](https://img.shields.io/badge/Chat%20on-Telegram-lightgray.svg)](https://t.me/v2raytun)

# v2RayTun — Proxy Client

**v2RayTun** — универсальный кроссплатформенный proxy-клиент, использующий [Xray core](https://github.com/XTLS/Xray-core) в качестве основного сетевого ядра. Проект включает отдельные приложения для различных операционных систем, среди которых **Android**, **Android TV**, **iOS**, **macOS**, **Windows** и **Linux**.

> Этот репозиторий предназначен для публикации информации о развитии проекта, выпуске новых версий, отслеживания ошибок, обсуждения предложений и хранения заметок, связанных с поддерживаемыми платформами.

---

## Releases

Актуальные сборки, история изменений и информация о новых версиях доступны через:

* [Telegram Releases](https://t.me/v2raytun/3)
* [GitHub Releases](https://github.com/LXST-CODE/v2RayTun/releases)

Также приложение распространяется через официальные магазины:

* [Google Play](https://play.google.com/store/apps/details?id=com.v2raytun.android)
* [App Store](https://apps.apple.com/us/app/v2raytun/id6476628951)

> [!NOTE]
> Версия приложения из App Store временно недоступна для пользователей из региона RU.

---

## Usage

> [!WARNING]
> Приложение не предоставляет встроенные конфигурации, готовые подписки, прокси-серверы или VPN-доступ!

Для начала работы необходимо самостоятельно импортировать собственные конфигурации или подписки в приложение.

После добавления необходимых данных клиент позволяет управлять подключениями и использовать выбранные настройки.

---

## Independent release tracks

**v2RayTun** использует независимые циклы выпуска для разных платформ и не придерживается единой общей версии для всех сборок.

Каждая платформа или группа платформ может иметь собственную нумерацию версий, дату релиза и особенности разработки.

| Release track       | Platforms           | Codebase       | Notes                                                                                                       |
| ------------------- | ------------------- | -------------- | ----------------------------------------------------------------------------------------------------------- |
| Android             | Android, Android TV | Kotlin         | Общая основа проекта с отдельными интерфейсами, поддержкой TV-режима и уникальными платформенными ресурсами |
| Desktop             | Windows, Linux      | Flutter / Dart | Общая кодовая база с различными вариантами упаковки, системными требованиями и настройками платформ         |
| iOS                 | iOS, iPadOS         | Swift          | Самостоятельная ветка разработки с отдельным процессом публикации через App Store                           |
| macOS Apple Silicon | macOS M2+           | Swift          | Специальная сборка для устройств Apple Silicon                                                              |
| macOS Intel         | macOS Intel         | Swift          | Отдельная версия для Mac-компьютеров с процессорами Intel                                                   |

---

## Roadmap

[Public Roadmap](https://github.com/users/LXST-CODE/projects/1) ведётся при помощи **GitHub Projects**.

В разделе дорожной карты могут отображаться:

* планы дальнейшего развития проекта;
* идеи новых функций;
* ограничения текущих версий;
* задачи, связанные с подготовкой релизов;
* предложения, находящиеся в рассмотрении или отклонённые.

---

## Issues and feedback

Раздел **GitHub Issues** используется для публикации:

* сообщений о найденных ошибках;
* предложений по добавлению функций;
* проблем, связанных с определёнными платформами;
* идей и рекомендаций по улучшению проекта.

При создании нового обращения рекомендуется использовать доступные шаблоны.

---

## Languages

Русскоязычные пояснения могут добавляться в отдельных разделах, если это помогает пользователям лучше понять информацию.

Основная структура репозитория, документация и организация материалов проекта поддерживаются на английском языке.
