# Laboratorio 04 - Tecnología Inalámbrica

## Efectos de Propagación a Gran Escala

**Integrantes:**

- Felipe Bustos López
- Francisco Polanco Alfaro

---

## Descripción

En este laboratorio se realizó una nueva campaña de mediciones de potencia recibida en un ambiente interior, como continuación del Laboratorio 03. La experiencia se desarrolló en el pasillo de Salas del nivel 5, utilizando una señal de frecuencia central de 2680 MHz.

El objetivo fue caracterizar el comportamiento de la pérdida de trayecto y del ensombrecimiento en este segundo escenario, para posteriormente comparar sus resultados con los obtenidos en el laboratorio anterior.

Las mediciones se realizaron variando la distancia entre el transmisor y el receptor, manteniendo constantes las condiciones principales del montaje. Los datos obtenidos fueron utilizados para aplicar el modelo de pérdida log-distance con ensombrecimiento log-normal.

---

## Equipamiento utilizado

Para realizar la experiencia se utilizaron los siguientes elementos:

- Generador de señales **Rohde & Schwarz SMC100A**.
- Analizador de espectro **Rohde & Schwarz FSH4**.
- 2 antenas omnidireccionales **Multiband Rubber Duck - Pasternack**, con ganancia de 4,5 dBi.
- Alargador eléctrico de 20 m.
- 2 conectores N-SMA.
- Huincha de medición para establecer las distancias entre el transmisor y el receptor.

---

## Condiciones de medición

| Parámetro | Valor |
|---|---:|
| Escenario | Pasillo de Salas, nivel 5 |
| Frecuencia de operación | 2680 MHz |
| Potencia transmitida | 0 dBm |
| Ganancia antena transmisora | 4,5 dBi |
| Ganancia antena receptora | 4,5 dBi |
| Distancia inicial | 1 m |
| Distancia máxima registrada | 24 m |
| Muestras utilizadas en el análisis | 50 |
| Rango utilizado en el análisis | 1 m a 23 m |
| Longitud de onda aproximada | 11,2 cm |
| Distancia de referencia | 1 m |

El analizador de espectro se configuró con una frecuencia central de 2680 MHz, un span de 5 MHz y una traza en modo Average. El registro de la potencia se realizó mediante un marcador ubicado en la frecuencia central.

---

## Actividad experimental

La campaña de medición se realizó desplazando progresivamente el generador de señales a lo largo del pasillo, mientras el analizador de espectro permaneció fijo en su posición inicial.

Entre 1 m y 3,9 m se realizaron mediciones cada 10 cm. Posteriormente, se realizaron mediciones cada 1 m desde los 4 m hasta los 24 m.

La evidencia disponible permite respaldar las mediciones realizadas en las distintas posiciones del pasillo. Para el análisis presentado en el informe se utilizaron las primeras 50 muestras, correspondientes al rango de 1 m a 23 m. La medición correspondiente a 24 m fue conservada como evidencia experimental, pero no fue incluida en el conjunto de datos utilizado para el ajuste.

---

## Resultados

Los datos experimentales fueron procesados para obtener la pérdida de trayecto correspondiente a cada distancia.

A partir del modelo de pérdida log-distance con ensombrecimiento log-normal se determinaron los parámetros necesarios para caracterizar el escenario y posteriormente compararlo con los resultados obtenidos en el Laboratorio 03.

El informe incluye:

- Cálculo de pérdida de trayecto.
- Ajuste del modelo log-distance.
- Exponente de pérdida de trayecto.
- Pérdida de referencia.
- Ensombrecimiento.
- Media y desviación estándar.
- Coeficiente de determinación.
- Comparación entre los escenarios del Laboratorio 03 y Laboratorio 04.
- Análisis conjunto de los datos.
- CDF del ensombrecimiento.

Los valores finales y gráficos correspondientes se encuentran desarrollados en el informe del laboratorio y en el archivo Excel de procesamiento.

---

## Evidencia experimental

La carpeta `Evidencia/` contiene las fotografías obtenidas durante la experiencia.

Las imágenes corresponden a los registros realizados con el analizador de espectro para las distintas distancias de medición, desde 1 m hasta 24 m, incluyendo las mediciones intermedias realizadas entre 1 m y 3,9 m.

La evidencia permite respaldar los valores de potencia utilizados en el procesamiento de los datos y documentar las condiciones del montaje experimental.

---

## Archivo de datos

El archivo Excel utilizado para almacenar y procesar las mediciones se encuentra en:

`Excel/Lab4_Ensombrecimiento.xlsx`

Este archivo contiene los datos experimentales y los cálculos utilizados para obtener los resultados presentados en el informe.

> El archivo temporal `~$Lab4_Ensombrecimiento.xlsx` es generado automáticamente por Excel y no debe incluirse en el repositorio.

---

## Informe

El informe completo del laboratorio se encuentra en:

`Informe/Lab04_TI.pdf`

El documento contiene:

- Resumen.
- Palabras clave.
- Introducción.
- Marco teórico.
- Generador de señales.
- Analizador de espectro.
- Modelo de ensombrecimiento log-normal.
- Metodología.
- Equipamiento utilizado.
- Montaje experimental.
- Procedimiento de medición y procesamiento de datos.
- Resultados y discusión.
- Pérdida de trayecto.
- Parámetros del modelo.
- Análisis del ensombrecimiento.
- Comparación entre escenarios.
- Evidencia de las mediciones.
- Conclusiones.
- Referencias.

---

## Organización del repositorio

La estructura del repositorio es:

```text
LAB04/
│
├── README.md
│
├── Excel/
│   └── Lab4_Ensombrecimiento.xlsx
│
├── Evidencia/
│   ├── 1m.jpg
│   ├── 1.1m.jpg
│   ├── 1.2m.jpg
│   ├── ...
│   ├── 3.9m.jpg
│   ├── 4m.jpg
│   ├── 5m.jpg
│   ├── ...
│   ├── 23m.jpg
│   └── 24m.jpg
│
└── Informe/
    └── Lab04_TI.pdf
```

Las fotografías de la carpeta `Evidencia/` corresponden a los registros obtenidos durante la experiencia y se mantienen como respaldo de las mediciones realizadas.

---

## Repositorio

El informe, los datos utilizados para el procesamiento y las evidencias experimentales se encuentran disponibles en el repositorio de GitHub:

**Repositorio de GitHub:**

https://github.com/sephppx/Laboratorio-04-Tecnologia-Inalambrica

---

## Autores

**Felipe Bustos López**

**Francisco Polanco Alfaro**

**Tecnología Inalámbrica, 2026**
