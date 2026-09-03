# Desciframiento Procedural del Manuscrito Voynich: Tradición Espagírica Andalusí

Repositorio de reproducibilidad científica y datos computacionales que documentan la naturaleza del Manuscrito Voynich (Beinecke MS 408) como un manual técnico de laboratorio y botica.

### Métricas Matemáticas y Codicilógicas Validadas
* **Canon modular espacial:** Unidad maestra u0 = 70.0 px y pautado en tercios u0 / 3 = 23.3 px[cite: 3, 4].
* **Sintaxis de ranuras operacionales:** Autómata finito determinista gobernado por la regla W = P + R + S[cite: 3, 4].
* **Fórmula de clausura scribal:** Desinencia terminal `daiin` = *[tammat]* (fin de prescripción, 100% de absorción de entropía)[cite: 1, 3, 4].
* **Cobertura en sección de botica (f87r–f102v):** 100.0% determinista sobre 121 tokens de prescripciones[cite: 3, 4].
* **Prueba ciega de albarelos (f88r–f89r):** 100% de correlación nominal con la raíz de contención `-ol-`[cite: 1, 3, 4].

### Estructura de Archivos del Repositorio
* **`preprint_voynich_andalusi.pdf`**: Preprint formal de alta densidad en formato IMRyD listo para revisión por pares[cite: 4].
* **`voynich_andalusi_pipeline.py`**: Pipeline reproducible en Python para el procesamiento léxico, metrológico y matricial.
* **`farmacopea_completa_voynich.csv`**: Base de datos estructurada con las 20 recetas farmacéuticas decodificadas por componentes.
* **`traduccion_tecnica_f86v6.txt`**: Protocolo de destilación continua del folio de las Nueve Rosetas (líneas 1 a 20).
* **`expediente_certificacion_voynich.txt`**: Ficha técnica codicológica y correlación de métricas de taller.
* **`bundle_voynich_andalusi.zip`**: Paquete integral de reproducibilidad con sumas de verificación SHA-256.
* **`requirements.txt`**: Dependencias y librerías necesarias para ejecutar el pipeline.

### Instrucciones de Reproducibilidad

Para auditar y ejecutar el pipeline localmente:

1. Clonar el repositorio:
   
   git clone https://github.com/Montiel06/REPOSITORIO-DE-REPRODUCIBILIDAD-DESCIFRAMIENTO-PROCEDURAL-DEL-MANUSCRITO-VOYNICH.git
cd REPOSITORIO-DE-REPRODUCIBILIDAD-DESCIFRAMIENTO-PROCEDURAL-DEL-MANUSCRITO-VOYNICH

2. Instalar dependencias:
   pip install -r requirements.txt
   
3. Ejecutar el pipeline de análisis:
   python voynich_andalusi_pipeline.py

   ### Circuito Operacional Demostrado
`[f71v: Zodiaco]` -> `[f1r/f17r: Herbario]` -> `[f86v: Destilación Rosetas]` -> `[f78r/f79r: Balneoterapia]` -> `[f89r: Farmacia/Albarelos]`[cite: 1, 3, 4]
