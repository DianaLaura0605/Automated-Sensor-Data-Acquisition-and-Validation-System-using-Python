# Sistema Automatizado de Simulación, Adquisición y Validación de Datos de Sensores

## Descripción general
Este proyecto implementa un sistema automatizado para la simulación, adquisición, almacenamiento y visualización de datos provenientes de sensores, utilizando Python. El sistema está diseñado como un proyecto introductorio orientado a instrumentación, automatización y análisis de señales, siguiendo una estructura clara y escalable.

El proyecto simula sensores físicos, almacena los datos generados en un archivo estructurado y genera gráficas automáticas para la validación visual del comportamiento de las señales.

---

## Objetivos del proyecto
- Simular la adquisición de datos de sensores físicos
- Automatizar el proceso de muestreo y almacenamiento
- Guardar los datos en formato CSV
- Visualizar las señales mediante gráficas generadas automáticamente
- Aplicar buenas prácticas de programación y estructura de proyecto

---

## Sensores simulados
El sistema incluye la simulación de los siguientes sensores:

- **Sensor de temperatura**  
  Rango simulado: 20 °C – 30 °C

- **Sensor de presión**  
  Rango simulado: 95 kPa – 105 kPa

Los valores se generan de forma pseudoaleatoria para emular condiciones reales de medición.

---

## Estructura del proyecto

```text
sensor-validation-system/
│
├── adquisicion/
│   └── adquisicion_datos.py
│
├── imagenes/
│   ├── sensor_temperatura.png
│   └── sensor_presion.png
│
├── datos_simulados.csv
├── requirements.txt
└── README.md
