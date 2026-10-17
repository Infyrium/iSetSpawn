# Команды и права iSetSpawn

Колонка «По умолчанию»: **все** — право есть у каждого игрока, **операторы** — только у операторов,
**никто** — право нужно выдать через LuckPerms.

Если в `config.yml` стоит `settings.requirePermission.spawn: false`, `/spawn` на себя доступна всем.
`isetspawn.spawn.others` и `isetspawn.setspawn` нужны всегда.

## Команды

| Команда | Синонимы | Что делает | Право |
|---|---|---|---|
| `/spawn` | — | Телепорт на спавн | `isetspawn.spawn` |
| `/spawn <игрок>` | — | Отправить игрока на спавн | `isetspawn.spawn.others` |
| `/setspawn` | — | Поставить спавн там, где вы стоите | `isetspawn.setspawn` |

## Права

| Право | Что даёт | По умолчанию |
|---|---|---|
| `isetspawn.spawn` | `/spawn` | операторы |
| `isetspawn.spawn.others` | `/spawn <игрок>` | операторы |
| `isetspawn.setspawn` | `/setspawn` | операторы |
