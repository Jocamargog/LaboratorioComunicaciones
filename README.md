# Laboratorios de Comunicaciones

Este repositorio contiene dos laboratorios de comunicaciones implementados en Python utilizando un receptor RTL-SDR.

## Contenidos

- `laboratorio1/`
  - `Reconocimiento_del_Espectro-2.py`: Captura muestras IQ en 106 MHz y genera la densidad espectral de potencia del canal, guardando la gráfica del espectro como imagen PNG.[file:21]
  - `LAB1_pseudocodigo.md`: Descripción en seudocódigo del flujo del laboratorio 1.[file:21]

- `laboratorio2/`
  - `Demodulacion_Final-1.py`: Demodula una emisora FM estéreo, extrae canales L y R, reproduce el audio, muestra espectrograma y FFT, y realiza un análisis de ancho de banda teórico (Carson) vs. estimado.[file:22]
  - `LAB2_pseudocodigo.md`: Descripción en seudocódigo del flujo del laboratorio 2.[file:22]

## Requerimientos

- Python 3.x
- Paquetes:
  - `numpy`
  - `scipy`
  - `matplotlib`
  - `sounddevice`
  - `pyrtlsdr` (o `rtlsdr`)
- Receptor RTL-SDR compatible.