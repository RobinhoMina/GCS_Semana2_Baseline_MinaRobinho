# SDD v1 – Diseño del Sistema (Baseline Candidate)

## Arquitectura (simple)
Arquitectura por capas:
- Presentación (salida por consola)
- Lógica de negocio (gestión de turnos)
- Datos (lista en memoria para versión mínima)

## Componentes
1. main.py
   - Ejecuta el flujo principal del programa.
2. TurnoService (conceptual)
   - Contiene funciones: crear_turno(), listar_turnos(), eliminar_turno().
3. Estructura de datos
   - Lista de turnos en memoria (para baseline v1.0).

## Decisiones técnicas
- Lenguaje: Python, por simplicidad y rápida demostración.
- Persistencia: en memoria (se deja como pendiente almacenamiento real).
- Pruebas: placeholder en carpeta /tests para evidenciar intención de testing.

## Restricciones
- Este diseño corresponde a un prototipo mínimo para establecer baseline v1.0.
