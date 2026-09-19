# Kord Icons

Icon set korišten u prototipu. Baziran na [Remix Icon](https://remixicon.com/).

## Naming
Svaki fajl je `Icon-<name>-<style>.svg` gdje je `<style>` **`line`** (outlined) ili **`fill`** (filled). U prototipu se koristi isključivo `line` varijanta.

## Format
- 24×24 viewBox
- Jedan `<path>` element s `fill="#8F97AE"` (siva) — za inline injection zamijeni s `fill="currentColor"` da ikona naslijedi boju kontejnera.

## Kako se koriste u prototipu
Ikone su inline-ane u `index.html` preko `ICONS` biblioteke i `<i data-ic="name">` markera koji se runtime injektuje u SVG (`renderInlineIcons()`).

## Kako ih koristiti direktno (bez copy-paste)
Svaki fajl je dostupan preko jsDelivr CDN:
```
https://cdn.jsdelivr.net/gh/jelenanj/kord-prototype@main/icons/Icon-<name>-line.svg
```
Primjeri:
- `https://cdn.jsdelivr.net/gh/jelenanj/kord-prototype@main/icons/Icon-home-4-line.svg`
- `https://cdn.jsdelivr.net/gh/jelenanj/kord-prototype@main/icons/Icon-calendar-todo-line.svg`

## Ključne ikone (mapping iz prototipa)
| Kontekst              | Icon                        |
|-----------------------|-----------------------------|
| Početna               | `home-4-line`               |
| Financije             | `money-euro-circle-line`    |
| Smjene                | `calendar-todo-line`        |
| Lokacije              | `community-line`            |
| Događaji              | `calendar-event-line`       |
| Zaposlenici           | `group-line`                |
| Upravitelji           | `user-settings-line`        |
| Predlošci             | `file-list-2-line`          |
| Oznake                | `price-tag-3-line`          |
| Podružnice            | `node-tree-line`            |
| Postavke              | `settings-3-line`           |
| Obavijesti            | `notification-3-line`       |
| Odjava                | `logout-box-line`           |
| Broj smjena u ćeliji  | `calendar-check-line`       |
| NFC obilazak          | `rfid-line`                 |
| Info hint             | `information-line`          |
| Greška / warning      | `error-warning-line`        |
| Edit                  | `pencil-line`               |
| Delete                | `delete-bin-line`           |
