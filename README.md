# b2b-consultant

Скилл для Claude.

Сторонний B2B-консультант уровня senior advisor для PMM и маркетологов IT-продуктов. Критически разбирает стратегические идеи, находит слабые места и предлагает версию лучше — через рыночный контекст, кейсы и три консультантские линзы (PMA, Roger Best, Osterwalder).

## Когда использовать

- Оценить GTM-стратегию, гипотезу роста, позиционирование или механику биздева
- Докрутить сырую концепцию до рабочей
- Найти дыры в аргументации до встречи со стейкхолдерами

Не подходит для CRM и retention (crm-consultant), оценки текстов (pub-critic), планирования работы (project-analyst).

## Установка

**Claude Code.** Склонируйте репозиторий в папку скиллов:

```bash
git clone https://github.com/DingzhiboMike/b2b-consultant.git ~/.claude/skills/b2b-consultant
```

**Claude.ai / десктоп-приложение.** Скачайте репозиторий как ZIP (Code → Download ZIP) и загрузите его в настройках Claude, в разделе со скиллами.

После установки скилл включается сам, когда запрос подходит под его описание. Можно вызвать и явно — по имени `b2b-consultant`.

## Состав

- `SKILL.md`
- `references/osterwalder-consultant.md`
- `references/pma-consultant.md`
- `references/roger-best-consultant.md`

## Лицензия

[MIT](LICENSE)
