# Yo-ho — сборка

Здесь только сборка и проверки программы Yo-ho (GitHub Actions). Код — в закрытом репозитории,
сборка берёт его по секрету `SRC_TOKEN` (только чтение). Выпуски и обновления — на Яндекс Диске
Deepworks Soft; сайт — https://deepworks-soft.github.io.

| Запуск | Что делает |
|---|---|
| `build.yml` | сборка ТВ (APK) и ПК (установщик), с `disk=yes` — подпись и выкладка на Диск (тестовый канал) |
| `promote.yml` | тестовая версия → всем |
| `analyze.yml`, `unit-test.yml` | проверка кода и тесты моста |
| `tv-check.yml`, `pc-check.yml` | стенды пульта и мыши, снимки — в ветки `tv-shots`, `pc-shots` |
| `disk-check.yml`, `disk-current.yml`, `key-check.yml` | проверки Диска и ключа подписи |
