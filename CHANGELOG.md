# Changelog

Todas las notas de cambios de `django-toon-rest`.

## 0.1.3 – 2025-11-16
- Agregado alias `version` en `__init__.py` (apunta a `__version__`).
- Mantiene import limpio (sin requerir settings de Django al importar el paquete).

## 0.1.2 – 2025-11-16
- Evitado importar `TOONRenderer` en `__init__.py` para permitir `import django_toon_rest` sin configurar Django.
- Publicación en PyPI: uso recomendado `from django_toon_rest.renderers import TOONRenderer`.

## 0.1.1 – 2025-11-16
- Primera versión pública funcional del renderer TOON.
- Manejo de `Decimal` a `float` antes de serializar con `json-toon`.
- Proyecto de ejemplo `django_test` y tests básicos.
