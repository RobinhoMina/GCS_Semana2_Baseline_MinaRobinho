# GCS Semana 2 – Baseline v1.0

## Objetivo del proyecto
Implementar un repositorio como depósito de elementos de configuración y crear una línea base (Baseline v1.0) con trazabilidad, auditabilidad y reproducibilidad.

## Proyecto (caso simple)
Sistema mínimo de ejemplo: “Hello baseline” (código base versionado).

## Estructura del repositorio
- docs/SRS: Requisitos del sistema (SRS)
- docs/SDD: Diseño del sistema (SDD)
- src: Código fuente mínimo
- tests: Evidencia o placeholder de pruebas
- config: Configuración controlada (ejemplo)
- scripts: Scripts auxiliares

## Cómo ejecutar (si aplica)
Ejemplo (Python):
1) Abrir terminal en la carpeta del repo  
2) Ejecutar:
   python src/main.py

Salida esperada:
Hello Baseline v1.0

## Cómo crear la línea base (Baseline v1.0)
1) Verificar que SRS_v1, SDD_v1, src y config.example estén listos.
2) Crear tag:
   git tag -a v1.0 -m "Baseline v1.0: SRS+SDD approved + minimal build"
3) Subir tag:
   git push origin v1.0
4) Crear Release v1.0 en GitHub y describir el contenido aprobado.

