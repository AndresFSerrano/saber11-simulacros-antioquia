# Simulacros Saber 11 en Antioquia

Datos de simulacros Saber 11 aplicados en Antioquia. Entrega 1, Unidad 2 de Matematica para
Ciencias de la Computacion (Grupo 7, J02).

Variable de interes: Puntaje Global, escala 0 a 500. Areas en escala 0 a 100.

Datos de menores de edad: solo entran archivos anonimizados, sin nombres, documentos ni
codigos de estudiante.

## Contenido

Consolidado de los cinco paquetes del grupo:

- `entrega/Matematica_U2_consolidado.xlsx` libro de entrega, cinco hojas.
- `entrega/resumen_estadistico.md` cifras descriptivas, histograma y probabilidades.
- `datos/consolidado_saber11_completo.csv` los 4654 registros unificados.
- `datos/instituciones_completo.csv` las 101 instituciones con municipio, sector y ubicacion.
- `referencia/` Saber 11 oficial 2022-2, dataset `kgxf-xxbe` de datos.gov.co.

Los archivos por integrante se conservan como quedaron al entregarlos:
`consolidado_saber11.csv` (Andres), `consolidado_saber11_david.csv`,
`consolidado_saber11_santiago.csv` y sus maestros de instituciones.

## Criterios del consolidado

De los 4654 registros recolectados entran 4180 al analisis:

- Rionegro aplico dos simulacros a los mismos estudiantes. Se analiza el Simulacro 1, igual que
  en las demas fuentes, para que cada estudiante entre una sola vez (473 registros excluidos).
- Un registro con puntaje 0 corresponde a un estudiante ausente, no a una medicion valida.

Nada se borro. La hoja `2_Datos` conserva las 4654 filas con la columna `en_analisis` y el
motivo de exclusion; cambiar esa marca recalcula todo el libro.

## Puntaje global

| Fuente | Aporta | n | Media | Mediana | Desv. estandar |
|---|---|---|---|---|---|
| UdeA | Andres | 165 | 292.58 | 289.30 | 55.06 |
| Envigado | Andres | 938 | 209.75 | 207.00 | 55.74 |
| Tablazo | Andres | 22 | 222.50 | 226.55 | 32.15 |
| Rionegro | David | 450 | 215.26 | 209.30 | 59.82 |
| Semestre Cero | Santiago | 2605 | 174.18 | 170.00 | 40.08 |
| **Consolidado** | | **4180** | **191.51** | **183.00** | **54.20** |
