# nomoreslop-design

Скилл для проектирования сайтов, веб-приложений и desktop/mobile интерфейсов: от предметного брифа и композиции до готовых решений, графики, движения и проверки результата.

## Установка

Нужны Node.js 22.20+ и агент с поддержкой скиллов. Установка через [Skills CLI](https://skills.sh/docs/cli):

```sh
npx skills add grodionn/nomoreslop-design
```

Для Codex в текущем проекте:

```sh
npx skills add grodionn/nomoreslop-design --skill nomoreslop-design --agent codex
```

Добавьте `--global` для установки во все проекты. При повторной установке проверьте предложенную CLI замену существующей копии.

## Использование

```text
Используй $nomoreslop-design для этой страницы.
```

Добавьте описание задачи и имеющиеся материалы. [Инструкции и библиотека](skills/nomoreslop-design/SKILL.md). Редакция 17.

## Проверка библиотеки

Вспомогательные инструменты работают на Python 3.10+ без сторонних пакетов:

```sh
python skills/nomoreslop-design/scripts/library.py check
python -m unittest discover -s skills/nomoreslop-design/tests -q
```

Вызов `library.py start --stage composition` показывает редакцию и путь загруженного скилла.

[MIT](LICENSE).
