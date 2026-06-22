# Plataformas Tecnológicas — Theos Place

Inventario visual de las herramientas y servicios digitales del Departamento de TI de la Asociación Theos Place. Es una página estática (`index.html`) que lista cada plataforma con su descripción, cuenta asociada, estado y costo.

## Qué hace

- Muestra las plataformas agrupadas por categoría: Web/Infraestructura/Datos, Diseño & Código, Automatización, Marketing, IA y Pagos.
- Resume el total de plataformas, el promedio mensual y la estimación anual de costos.
- Permite filtrar las plataformas por categoría.

## Cómo abrirlo

No necesita build ni dependencias. Abrí el archivo directamente:

```bash
open index.html
```

O serví la carpeta con cualquier servidor estático si lo preferís:

```bash
python3 -m http.server 8000
# luego abrí http://localhost:8000
```

## Estructura

- `index.html` — todo el contenido, estilos y scripts en un solo archivo.

## Cómo actualizar el inventario

Editá `index.html` directamente. Cada plataforma es una fila dentro de la tabla de su sección. Cuando agregués, quités o cambiés el costo de una plataforma, acordate de actualizar también los totales del encabezado (cantidad de plataformas, promedio mensual y estimado anual).

## Notas

- La fecha del inventario está en el encabezado (actualmente: Junio 2026).
- Los íconos y fuentes (DM Mono) se cargan desde Google Fonts, así que requiere conexión a internet para verse exactamente como fue diseñado.
