# RaceLine — Nürburgring Nordschleife

Herramienta interactiva para estimar si un vehículo de competición conserva adherencia en curvas seleccionadas del Nürburgring Nordschleife y recrear una vuelta animada en una línea de carrera esquemática.

## Modelo físico

- Aceleración centrípeta: `ac = v² / r`
- Fuerza centrípeta: `Fc = m v² / r`
- Fricción máxima: `Ff = μ m g`
- Condición de seguridad: `Ff ≥ Fc`
- Velocidad máxima: `vmax = √(μgr)`

## Escenarios y uso

Abre `index.html` en cualquier navegador moderno.

1. Escoge un escenario: F1, NASCAR, MotoGP, Le Mans o carretera.
2. Selecciona una curva del Nordschleife: Hatzenbach, Schwedenkreuz, Adenauer Forst, Karussell, Pflanzgarten o Döttinger Höhe.
3. Ajusta la masa, velocidad de entrada, fricción o gravedad para calcular el límite de cada vértice.
4. Pulsa **Iniciar vuelta** para ver el vehículo recorrer el circuito.

Los valores de cada escenario son aproximaciones educativas y no sustituyen un modelo de dinámica vehicular con carga aerodinámica, transferencia de peso, peralte y telemetría real.

