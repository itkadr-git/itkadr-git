# Alex

[![Latest release](https://img.shields.io/github/v/release/itkadr-git/myrmidon?sort=semver&label=release)](https://github.com/itkadr-git/myrmidon/releases/latest)

I build [Myrmidon](https://github.com/itkadr-git/myrmidon) — an orchestration platform for AI agents.

At some point the existing tools stopped being enough, so I built my own. Myrmidon takes its inspiration from the μυρμηδόνες — the mythic people turned into ants. A real ant colony has no manager: the work organizes itself through traces left in a shared environment, not through orders. That's the model I want for AI agents — a colony coordinated by signals, not micromanagement.

**Contacts:** [itkadr@gmail.com](mailto:itkadr@gmail.com) · [Telegram @itkadr](https://t.me/itkadr)

## What Myrmidon can do

Myrmidon runs a team of AI agents on your own server, and holds it to the standards of a real one:

- **Isolation.** Every agent gets its own container, its own gateway key and its own memory bank — no shared credentials, no server secrets inside a run.
- **Accountability.** Every run, every dollar of model spend and every approval is on the board, where you can trace who did what and why.
- **Recovery.** A stalled run is resumed or handed back to the queue; a bad deploy is rolled back automatically. The colony keeps working while you sleep.

## Where the project is heading

The project is growing toward a full colony. The 1.6 line laid the foundation: per-role task queues, baseline metrics and evals, and a skill lifecycle where an agent's finding becomes a company skill only after review. Next up are custom castes and model providers managed right from the interface. Further out, the colony grows its own body — an orchestrated cluster across machines, hibernation for idle agents, a second site for survivability — and the codebase is gradually rewritten from specifications until no borrowed code remains.

That's the direction, not a promise: the details are in the [roadmap](https://github.com/itkadr-git/myrmidon/blob/main/docs/myrmidon/ROADMAP.md).

---

# Alex

[![Последний выпуск](https://img.shields.io/github/v/release/itkadr-git/myrmidon?sort=semver&label=%D0%B2%D1%8B%D0%BF%D1%83%D1%81%D0%BA)](https://github.com/itkadr-git/myrmidon/releases/latest)

Я делаю [Myrmidon](https://github.com/itkadr-git/myrmidon) — систему управления командой ИИ-агентов на своём сервере.

Мне стало мало готовых инструментов, и я сделал свой. Меня вдохновили мирмидоняне (греч. μυρμηδόνες) — мифические люди-муравьи. В муравейнике нет управляющего: работа налаживается сама, по меткам, оставленным в общей среде, а не по приказам. Для ИИ-агентов нужен тот же порядок: колонией управляют сигналы, а не мелочный контроль.

**Контакты:** [itkadr@gmail.com](mailto:itkadr@gmail.com) · [Telegram @itkadr](https://t.me/itkadr)

## Что умеет Myrmidon

Myrmidon ведёт команду ИИ-агентов на вашем сервере — и спрашивает с неё, как с настоящей:

- **Изоляция.** У каждого агента свой контейнер, свой ключ к моделям и своя память: никаких общих ключей, секреты сервера в прогон не попадают.
- **Подотчётность.** Каждый прогон, каждый потраченный на модели рубль и каждое согласование — на доске: видно, кто что сделал и почему.
- **Восстановление.** Зависший прогон поднимается сам или возвращается в очередь, неудачный выкат откатывается автоматически. Колония работает, пока вы спите.

## Куда идёт проект

Проект идёт к полноценной колонии. Линия 1.6 заложила основу: очереди задач по ролям, метрики и проверки на эталонных задачах, жизненный цикл навыков — находка агента становится навыком компании только после проверки. Дальше — собственные касты и провайдеры моделей прямо в интерфейсе. А ещё дальше колония отращивает себе тело: кластер из нескольких машин под управлением оркестратора, усыпление простаивающих агентов, вторая площадка на случай отказа — а код постепенно переписывается по спецификациям, пока в нём не останется заимствований.

Это направление, а не обещание: подробности — в [дорожной карте](https://github.com/itkadr-git/myrmidon/blob/main/docs/myrmidon/ROADMAP.md).

---

## Myrmidon

- **Repository / Репозиторий:** [itkadr-git/myrmidon](https://github.com/itkadr-git/myrmidon)
- **Latest release / Последний выпуск:** [myr-v1.6.5](https://github.com/itkadr-git/myrmidon/releases/tag/myr-v1.6.5) · [all releases / все выпуски](https://github.com/itkadr-git/myrmidon/releases)
- **Quick start / Быстрый старт:** [EN](https://github.com/itkadr-git/myrmidon/wiki/Quick-start) · [RU](https://github.com/itkadr-git/myrmidon/wiki/Quick-start.ru)
- **Deploy / Выкат:** [EN](https://github.com/itkadr-git/myrmidon/blob/main/docs/myrmidon/deploy.md) · [RU](https://github.com/itkadr-git/myrmidon/blob/main/docs/myrmidon/deploy.ru.md)
- **Guides / Руководства:** [docs/myrmidon/guides](https://github.com/itkadr-git/myrmidon/tree/main/docs/myrmidon/guides)
- **Contributing / Участие:** [CONTRIBUTING.md](https://github.com/itkadr-git/myrmidon/blob/main/CONTRIBUTING.md)
- **License / Лицензия:** MIT (based on / основан на [Paperclip](https://github.com/paperclipai/paperclip))
