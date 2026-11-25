<!-- lawwatch: written from data/checks by the check trail; edit the records, not this page -->

# Supervisión: qué se lee y qué resulta

[English](README.en.md)

Cómo supervisa global-law todos los países: [global-law monitoring/](https://github.com/lexifina/global-law/tree/main/monitoring). Esta página hace lo mismo solo para Canarias: cada vez que se lee una fuente oficial, cuándo y qué resultó (normas añadidas, modificadas y retiradas). La forma legible por máquina está en [data/checks/](../data/checks/) (JSON Lines, esquema `lexifina-check/1`), en `git log` como commits `Kind: check`, y mes a mes en [checks/](checks/).

**Última comprobación:** 2026-11-25 15:08 UTC, Legislación consolidada del BOE, comunidades autónomas (datos abiertos): 36 direcciones leídas; 0 añadidas, 0 modificadas, 0 retiradas; la comprobación falló; 25 sin publicar, 0 de ellas sin motivo. Avisos: `publish-lag`.

## Fuentes

| Fuente | Carpetas | Frecuencia | Última comprobación correcta | Último resultado | Estado |
| --- | --- | --- | --- | --- | --- |
| [Legislación consolidada del BOE, comunidades autónomas (datos abiertos)](https://www.boe.es/datosabiertos/api/api.php) | `estatuto-de-autonomia/`, `ley-*/`, `decreto-ley-*/`, `decreto-legislativo-*/`, `…` | diaria | 2026-11-23 13:50 UTC | la comprobación falló | vigilada |

## Los últimos 30 días

| Inicio (UTC) | Fuente | Leídas | Añadidas | Modificadas | Retiradas | Sin publicar (sin motivo) | Resultado | Commits |
| --- | --- | ---: | ---: | ---: | ---: | ---: | --- | ---: |
| [2026-11-25 15:07](checks/2026-11.md#es-boe-autonomico-20261125t150710z) | boe-autonomico | 36 | 0 | 0 | 0 | 25 (0) | la comprobación falló `publish-lag` | — |
| [2026-11-25 14:07](checks/2026-11.md#es-boe-autonomico-20261125t140718z) | boe-autonomico | 36 | 0 | 0 | 0 | 25 (0) | la comprobación falló `publish-lag` | — |
| [2026-11-25 13:07](checks/2026-11.md#es-boe-autonomico-20261125t130714z) | boe-autonomico | 36 | 0 | 0 | 0 | 25 (0) | la comprobación falló `publish-lag` | — |
| [2026-11-25 12:07](checks/2026-11.md#es-boe-autonomico-20261125t120712z) | boe-autonomico | 36 | 0 | 0 | 0 | 25 (0) | la comprobación falló `publish-lag` | — |
| [2026-11-25 11:07](checks/2026-11.md#es-boe-autonomico-20261125t110713z) | boe-autonomico | 36 | 0 | 0 | 0 | 25 (0) | la comprobación falló `publish-lag` | — |
| [2026-11-25 10:23](checks/2026-11.md#es-boe-autonomico-20261125t102347z) | boe-autonomico | 36 | 0 | 0 | 0 | 25 (0) | la comprobación falló `publish-lag` | — |
| [2026-11-25 09:07](checks/2026-11.md#es-boe-autonomico-20261125t090709z) | boe-autonomico | 36 | 0 | 0 | 0 | 25 (0) | la comprobación falló `publish-lag` | — |
| [2026-11-25 06:16](checks/2026-11.md#es-boe-autonomico-20261125t061618z) | boe-autonomico | 37 | 0 | 0 | 0 | 25 (0) | la comprobación falló `publish-lag` | — |
| [2026-11-24 15:11](checks/2026-11.md#es-boe-autonomico-20261124t151116z) | boe-autonomico | 37 | 0 | 0 | 0 | 25 (0) | la comprobación falló `publish-lag` | — |
| [2026-11-24 14:21](checks/2026-11.md#es-boe-autonomico-20261124t142140z) | boe-autonomico | 37 | 0 | 0 | 0 | 25 (0) | la comprobación falló `publish-lag` | — |
| [2026-11-24 12:58](checks/2026-11.md#es-boe-autonomico-20261124t125810z) | boe-autonomico | 37 | 0 | 0 | 0 | 25 (0) | la comprobación falló `publish-lag` | — |
| [2026-11-24 11:16](checks/2026-11.md#es-boe-autonomico-20261124t111633z) | boe-autonomico | 37 | 0 | 0 | 0 | 25 (0) | la comprobación falló `publish-lag` | — |
| [2026-11-24 10:12](checks/2026-11.md#es-boe-autonomico-20261124t101257z) | boe-autonomico | 37 | 0 | 0 | 0 | 25 (0) | la comprobación falló `publish-lag` | — |
| [2026-11-24 09:11](checks/2026-11.md#es-boe-autonomico-20261124t091143z) | boe-autonomico | 37 | 0 | 0 | 0 | 25 (0) | la comprobación falló `publish-lag` | — |
| [2026-11-24 08:11](checks/2026-11.md#es-boe-autonomico-20261124t081149z) | boe-autonomico | 37 | 0 | 0 | 0 | 25 (0) | la comprobación falló `publish-lag` | — |
| [2026-11-24 07:16](checks/2026-11.md#es-boe-autonomico-20261124t071620z) | boe-autonomico | 37 | 0 | 0 | 0 | 25 (0) | la comprobación falló `publish-lag` | — |
| [2026-11-23 13:50](checks/2026-11.md#es-boe-autonomico-20261123t135048z) | boe-autonomico | 36 | 0 | 0 | 0 | 25 (0) | sin cambios `publish-lag` | — |
| [2026-11-23 01:08](checks/2026-11.md#es-boe-autonomico-20261123t010807z) | boe-autonomico | 10 | 0 | 0 | 0 | 25 (0) | sin cambios `publish-lag` | — |

## Compruébelo usted mismo

```
python tools/checktrail.py                      # la última comprobación de cada fuente
python tools/checktrail.py --day 2026-11-23     # todas las comprobaciones de un día
python tools/checktrail.py --act <id>           # cuándo se vio y se publicó una norma
git log --grep='^Kind: check' --format='%ci %s'  # las comprobaciones en el historial
```

Solo tiene fuerza jurídica la publicación oficial (el «Boletín Oficial del Estado» y los diarios oficiales autonómicos); los textos de este repositorio son copias para leer y buscar.
