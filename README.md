# Pizarra Infinita (Estilo Sci‑Fi)

Aplicación web para organizar proyectos en pizarras separadas, con nodos visuales conectables sobre un lienzo infinito.

## Funcionalidades

- Pizarras múltiples (una por proyecto).
- Elementos: nota, imagen, video/enlace y línea de tiempo.
- Línea de tiempo con **formulario** para añadir múltiples:
  - eventos (`nombre + fecha`)
  - periodos (`nombre + fecha inicio + fecha fin`)
- Redimensionado manual de nodos (notas, eventos, timelines, etc.) desde la esquina inferior derecha.
- Conexiones rectas entre nodos (modo **Conectar**).
- Pan (`Shift + arrastrar`) y zoom (rueda).
- Persistencia en `localStorage`.

## Ejecutar

```bash
python3 -m http.server 4173
```

Luego visita `http://localhost:4173`.
