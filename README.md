# OT Cyber Radar

Portal mobile-first con tres feeds:

- `data/ot.json`: incidentes OT / IoT / IIoT.
- `data/it.json`: incidentes IT.
- `data/tools.json`: noticias de herramientas OT.

Los feeds son append-only en operación normal: cada automatización agrega novedades verificadas, deduplica por ID/tema/fuente y conserva histórico. El frontend agrupa automáticamente por fecha y ofrece filtros 24 h / 7 días / 30 días / Todo.

## Regla editorial OT

No rellenar con CVE para completar cuota. Priorizar ataques confirmados, campañas, empresas/plantas comprometidas, ransomware con impacto operacional e incidentes de energía, agua, manufactura, transporte, mining, building OT, IoT/IIoT y CPS.

## Regla editorial herramientas

Publicar lanzamientos, releases, integraciones, adquisiciones, certificaciones/compliance y nuevas capacidades; priorizar fuente oficial del fabricante.
