# Генератор карточек для школьного дежурства, готовых для печати на принтере

## Важно

- Изображения генерируются в формате А4

## Разработка

### Шрифты

Используя [glyphhanger](https://github.com/zachleat/glyphhanger) нужно оптимизировать шрифты:

```sh
glyphhanger --US_ASCII --whitelist=аАбБвВгГдДеЕёЁжЖзЗиИйЙкКлЛмМнНоОпПрРсСтТуУфФхХцЦчЧшШщЩыЫэЭюЮяЯьЬъЪ --subset=*.ttf --formats=woff2
```

### Изображения

Изображения должны быть в формате png, 618 пикселей в высоту и 1063 в длину.
