# RaceLine — simulador de curvas en circuito

Herramienta interactiva para estimar si un vehículo de competición conserva adherencia en cada curva de un circuito esquemático.

## Modelo físico

- Aceleración centrípeta: `ac = v² / r`
- Fuerza centrípeta: `Fc = m v² / r`
- Fricción máxima: `Ff = μ m g`
- Condición de seguridad: `Ff ≥ Fc`
- Velocidad máxima: `vmax = √(μgr)`

## Escenarios y uso

Abre `index.html` en cualquier navegador moderno.

1. Escoge un escenario: F1, NASCAR, MotoGP, Le Mans o carretera.
2. Selecciona una curva del circuito (C1–C5).
3. Ajusta la masa, velocidad de entrada, fricción o gravedad para calcular el límite de cada vértice.

Los valores de cada escenario son aproximaciones educativas y no sustituyen un modelo de dinámica vehicular con carga aerodinámica, transferencia de peso, peralte y telemetría real.

