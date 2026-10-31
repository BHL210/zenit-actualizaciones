# Proyecto Zenit — Actualizaciones

Parches BPS de Pokémon Edición Zenit para una copia propia de Pokémon HeartGold (español).

**No se distribuyen ROMs originales, datos de partidas ni archivos BIOS.**

## Catálogo de actualizaciones
- [manifest.json](./manifest.json): versiones y hashes SHA-256.
- [patches](./patches): archivos BPS de cada versión, siempre contra la misma ROM base.

URL directa del catálogo para Zenit Play:
`https://raw.githubusercontent.com/BHL210/zenit-actualizaciones/main/manifest.json`

Si activas GitHub Pages en **Settings → Pages → Deploy from a branch → main / root**, también podrás usar:
`https://bhl210.github.io/zenit-actualizaciones/manifest.json`

## Añadir versiones
Publica cada nueva versión como `patches/Zenit_v0.08.bps`, generada **desde la ROM original** y actualiza `manifest.json` con `id`, `name`, `description`, `url` y `sha256`. No sobrescribas archivos de versiones anteriores.

## Partidas
Guarda normalmente dentro del juego y exporta un archivo `.sav` antes de cada actualización importante. Los estados instantáneos pueden no ser compatibles entre versiones.
