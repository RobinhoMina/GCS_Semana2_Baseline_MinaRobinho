# SRS v1 – Sistema de Turnos (Baseline Candidate)

## Alcance
Sistema mínimo para registrar y listar turnos, con validación básica.

## Requisitos Funcionales (RF)
REQ-001: El sistema permitirá registrar un turno con nombre y fecha.
REQ-002: El sistema permitirá listar todos los turnos registrados.
REQ-003: El sistema permitirá eliminar un turno por identificador.
REQ-004: El sistema validará que los campos obligatorios no estén vacíos.
REQ-005: El sistema mostrará un mensaje de confirmación al registrar un turno.

## Requisitos No Funcionales (RNF)
RNF-001: El sistema deberá responder en menos de 2 segundos en operaciones básicas.
RNF-002: El sistema deberá mantener una estructura modular y legible para facilitar mantenimiento.
RNF-003: El repositorio deberá permitir reconstruir exactamente la versión liberada mediante tags.
