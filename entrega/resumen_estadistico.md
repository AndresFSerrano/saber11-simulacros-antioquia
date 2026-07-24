# Resumen estadistico del Puntaje Global

Variable analizada: puntaje global del simulacro Saber 11, escala 0 a 500.
Consolidado de los cinco paquetes del grupo: 101 instituciones de 63 municipios de Antioquia.

De los 4654 registros recolectados entran 4180 al analisis. Se excluyen 473 registros de la
segunda aplicacion de Rionegro, porque son los mismos estudiantes del Simulacro 1 y contarlos dos
veces romperia la independencia de las observaciones, y 1 registro con puntaje 0 que corresponde a
un estudiante ausente. Ninguno se borro: la hoja 2_Datos del Excel los conserva marcados.

## Consolidado

| Grupo | n | Media | Mediana | Desviacion | Varianza | Minimo | Maximo |
|---|---|---|---|---|---|---|---|
| CONSOLIDADO | 4180 | 191.51 | 183.00 | 54.20 | 2937.47 | 40.0 | 439.7 |

## Por fuente

| Fuente | Aporta | n | Media | Mediana | Desviacion | Varianza | Minimo | Maximo |
|---|---|---|---|---|---|---|---|---|
| UdeA | Andres | 165 | 292.58 | 289.30 | 55.06 | 3031.97 | 140.0 | 439.7 |
| Envigado | Andres | 938 | 209.75 | 207.00 | 55.74 | 3106.80 | 60.0 | 382.0 |
| Tablazo | Andres | 22 | 222.50 | 226.55 | 32.15 | 1033.67 | 151.4 | 281.8 |
| Rionegro | David | 450 | 215.26 | 209.30 | 59.82 | 3578.18 | 40.4 | 418.5 |
| Semestre Cero | Santiago | 2605 | 174.18 | 170.00 | 40.08 | 1606.74 | 40.0 | 335.0 |

## Distribucion de frecuencias

Clases de ancho 25 puntos. La frecuencia esperada se calcula con la normal propuesta,
X ~ Normal(191.51, 2937.47).

| Clase | Marca | Frecuencia observada | Frecuencia relativa | Frecuencia esperada normal |
|---|---|---|---|---|
| 0 a 25 | 12.5 | 0 | 0.0000 | 3.3 |
| 25 a 50 | 37.5 | 4 | 0.0010 | 13.6 |
| 50 a 75 | 62.5 | 29 | 0.0069 | 45.2 |
| 75 a 100 | 87.5 | 51 | 0.0122 | 122.0 |
| 100 a 125 | 112.5 | 193 | 0.0462 | 265.8 |
| 125 a 150 | 137.5 | 678 | 0.1622 | 468.1 |
| 150 a 175 | 162.5 | 873 | 0.2089 | 666.5 |
| 175 a 200 | 187.5 | 798 | 0.1909 | 767.1 |
| 200 a 225 | 212.5 | 587 | 0.1404 | 713.6 |
| 225 a 250 | 237.5 | 392 | 0.0938 | 536.7 |
| 250 a 275 | 262.5 | 258 | 0.0617 | 326.2 |
| 275 a 300 | 287.5 | 128 | 0.0306 | 160.3 |
| 300 a 325 | 312.5 | 105 | 0.0251 | 63.7 |
| 325 a 350 | 337.5 | 48 | 0.0115 | 20.4 |
| 350 a 375 | 362.5 | 16 | 0.0038 | 5.3 |
| 375 a 400 | 387.5 | 14 | 0.0033 | 1.1 |
| 400 a 425 | 412.5 | 4 | 0.0010 | 0.2 |
| 425 a 450 | 437.5 | 2 | 0.0005 | 0.0 |

## Probabilidades con la normal propuesta

| Evento | Probabilidad normal | Frecuencia observada | Diferencia |
|---|---|---|---|
| P(X <= 150), riesgo alto | 0.2218 | 0.2285 | +0.0066 |
| P(150 < X <= 250), rango medio | 0.6379 | 0.6340 | -0.0039 |
| P(X > 250), desempeno alto | 0.1403 | 0.1376 | -0.0027 |
| P(X > 300), acceso competitivo | 0.0227 | 0.0452 | +0.0226 |
| P(X > 350), becas de excelencia | 0.0017 | 0.0086 | +0.0069 |

## Cobertura por intervalos de desviacion estandar

| Intervalo | Observado | Normal teorica | Diferencia |
|---|---|---|---|
| mu +/- 1 sigma | 0.7220 | 0.6827 | +0.0393 |
| mu +/- 2 sigma | 0.9435 | 0.9545 | -0.0110 |
| mu +/- 3 sigma | 0.9921 | 0.9973 | -0.0052 |

## Lectura

La normal ajustada describe razonablemente el centro de la distribucion. En el rango de 150 a 250
puntos, donde esta la mayor parte de los estudiantes, el modelo predice 63.8% y se observa
63.4%, una diferencia de menos de medio punto porcentual. Lo mismo ocurre por debajo de
150 y por encima de 250.

El ajuste se rompe en la cola derecha. El modelo predice 2.27% de estudiantes por encima
de 300 puntos y se observa 4.52%, o sea el doble; por encima de 350 la diferencia es de
cinco veces. La distribucion tiene asimetria positiva (0.766) y curtosis por encima de la
normal (0.973), y la mediana (183.00) queda por debajo de la media (191.51),
que es el patron tipico de una cola derecha larga.

La razon esta en la tabla por fuente y no es un defecto de los datos: el consolidado es una mezcla de
poblaciones con medias muy distintas. Semestre Cero aporta 62% de la muestra con media 174.18 y
la desviacion mas baja del grupo, y concentra la masa en las clases de 125 a 175. Los grupos UdeA, con
media 292.58, forman la cola derecha. Una mezcla de normales con medias separadas no es normal, y por
eso el ajuste global funciona en el centro pero subestima los extremos. Cada fuente por separado es
mas simetrica que el conjunto.
