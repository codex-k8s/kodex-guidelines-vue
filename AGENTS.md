# Vue Design Guidelines

Документы для frontend (Vue 3 + TypeScript).

- `check_list.md` — чек-лист перед PR для Vue изменений.
- `frontend_architecture.md` — размещение, структура приложения, границы ответственности.
- `frontend_data_and_state.md` — axios/Pinia/router/i18n/cookies/PWA/WebSocket правила.
- `frontend_error_handling.md` — модель и обработка ошибок на фронте.
- `frontend_code_rules.md` — правила кодирования (TS/Vue/импорты/комментарии).
- `libraries.md` — что выносить в `libs/{vue,ts,js}` и как.
- `../common/external_dependencies_catalog.md` — согласованный список внешних библиотек и инструментов.

Специфика `kodex`:
- целевой frontend приложения будет заново создан в каталоге, согласованном в новой архитектуре;
- вход в UI защищен GitHub OAuth;
- пользовательские настройки и права приходят из backend API (PostgreSQL как source of truth).
- Проектное планирование и документационная каноника задаются корневым `AGENTS.md` и актуальной проектной документацией, а не этим техническим гайдом.
