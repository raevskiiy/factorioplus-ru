# Factorio+ — Russian Localization / Русская локализация

[🇷🇺 Русский](#-русский) · [🇬🇧 English](#-english)

---

## 🇷🇺 Русский

Неофициальный русский перевод мода **[Factorio+](https://mods.factorio.com/mod/factorioplus)** (автор оригинального мода — Fishbus).

| | |
|---|---|
| Мод-локализация | `factorioplus-ru` |
| Версия | 0.2.99 (соответствует версии Factorio+) |
| Версия игры | Factorio 1.1 |
| Требуется | мод Factorio+ (`factorioplus >= 0.2.99`) |

### Что переведено

- предметы, оборудование, жидкости и рецепты;
- технологии и их описания;
- сущности (постройки, транспорт, враги, гнёзда) и их описания;
- настройки мода и описания настроек;
- пресеты генерации карты, ресурсы, бонусы улучшений, типы урона.

Всего переведено 389 строк оригинальной английской локализации.

### Установка

1. Скачайте архив `factorioplus-ru_0.2.99.zip` из раздела [Releases](../../releases).
2. **Не распаковывайте** его и положите в папку модов:
   - Windows: `%appdata%\Factorio\mods`
   - Linux: `~/.factorio/mods`
   - macOS: `~/Library/Application Support/factorio/mods`
3. Запустите игру и убедитесь, что мод `Factorio+ — русская локализация` включён в разделе «Моды».
4. В настройках игры выберите язык **Русский**.

### Замечания по переводу

- Термины подбирались по аналогии с терминологией ванильного Factorio, но официальный перевод не сверялся. Если вы заметили несоответствия, создайте issue или pull request.
- Для врагов мода использованы собственные названия: *blaster* — подрывник, *swarmer* — роевик, *tanker* — бронеход, *webber* — паутинник.
- В оригинале есть опечатки (`Raingun`, `Bohemoth`, `Guass`). В переводе они исправлены.
- Ключ `Compression-tech` в оригинале записан с заглавной буквы, а в описании технологии — со строчной. В переводе добавлены оба варианта, чтобы название отображалось корректно.

### Структура репозитория

```
factorioplus-ru/
├── info.json
└── locale/
    └── ru/
        └── config.cfg
```

### Участие в проекте

Нашли ошибку или хотите улучшить перевод? Откройте [issue](../../issues) или отправьте pull request. Правки вносятся в файл `locale/ru/config.cfg`.

При обновлении Factorio+ новые строки нужно добавлять в тот же файл, сохраняя структуру секций оригинала.

### Права и авторство

Оригинальный мод Factorio+ принадлежит его автору (Fishbus). Этот репозиторий содержит только перевод строк локализации и не включает код, графику или другие материалы оригинального мода.

---

## 🇬🇧 English

An unofficial Russian translation of the **[Factorio+](https://mods.factorio.com/mod/factorioplus)** mod (original mod by Fishbus).

| | |
|---|---|
| Localization mod | `factorioplus-ru` |
| Version | 0.2.99 (matches the Factorio+ version) |
| Game version | Factorio 1.1 |
| Requires | Factorio+ mod (`factorioplus >= 0.2.99`) |

### What is translated

- items, equipment, fluids and recipes;
- technologies and their descriptions;
- entities (buildings, vehicles, enemies, spawners) and their descriptions;
- mod settings and setting descriptions;
- map generation presets, resources, upgrade bonuses and damage types.

In total, 389 strings from the original English locale are translated.

### Installation

1. Download `factorioplus-ru_0.2.99.zip` from the [Releases](../../releases) page.
2. **Do not unzip it.** Put it into your mods folder:
   - Windows: `%appdata%\Factorio\mods`
   - Linux: `~/.factorio/mods`
   - macOS: `~/Library/Application Support/factorio/mods`
3. Launch the game and make sure the `Factorio+ — русская локализация` mod is enabled in the Mods menu.
4. In the game settings, set the language to **Russian**.

### Translation notes

- Terms follow the style of vanilla Factorio's Russian terminology, but they have not been checked against the official translation. If you spot inconsistencies, please open an issue or a pull request.
- Enemies added by the mod use custom names: *blaster* → «подрывник», *swarmer* → «роевик», *tanker* → «бронеход», *webber* → «паутинник».
- The original locale contains typos (`Raingun`, `Bohemoth`, `Guass`). They are corrected in the translation.
- In the original locale the technology name key is `Compression-tech` (capital C) while its description key is `compression-tech`. Both variants are included so the name displays correctly.

### Repository structure

```
factorioplus-ru/
├── info.json
└── locale/
    └── ru/
        └── config.cfg
```

### Contributing

Found a mistake or want to improve the translation? Open an [issue](../../issues) or submit a pull request. All changes go into `locale/ru/config.cfg`.

When Factorio+ is updated, add new strings to the same file and keep the section structure of the original locale.

### Rights and credits

The original Factorio+ mod belongs to its author (Fishbus). This repository contains only translated locale strings and does not include any code, graphics or other assets of the original mod.
