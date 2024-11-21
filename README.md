# 🏋️‍♂️ Predicción de Cancelación de Clientes en Model Fitness

## 📖 Descripción del Proyecto

Este proyecto tiene como objetivo principal predecir la **probabilidad de cancelación de clientes** en Model Fitness, una cadena de gimnasios. Además, busca identificar factores clave que influyen en la cancelación, segmentar a los clientes en grupos basados en sus características y comportamientos, y proponer estrategias para mejorar la **retención de clientes**.

## 💻 Demostración de Funciones y Aplicaciones

### **Parte 1: Análisis Exploratorio de Datos (EDA)**

#### Exploración Inicial
- Limpieza y preparación del dataset para garantizar datos consistentes y completos.
- Visualización de patrones relacionados con la cancelación, como frecuencia de visitas, edad y proximidad al gimnasio.

#### Identificación de Factores Clave
- **Proximidad al gimnasio:** Mayor retención entre clientes cercanos.
- **Duración del contrato:** Contratos más largos presentan menor tasa de cancelación.
- **Edad y frecuencia:** Clientes más jóvenes y con baja frecuencia de uso son más propensos a cancelar.

### **Parte 2: Modelado Predictivo**

#### Modelos Implementados
1. **Regresión Logística**
   - Exactitud: 92%
   - Precisión: 87%
   - Recall: 78%
2. **Bosques Aleatorios**
   - Exactitud: 91%
   - Precisión: 85%
   - Recall: 78%

Ambos modelos muestran un rendimiento sólido. La **regresión logística** es más eficiente y recomendada para su implementación.

#### Validación
- Análisis de las métricas de rendimiento para asegurar la confiabilidad de las predicciones.

### **Parte 3: Análisis de Clustering**

#### Identificación de Grupos de Clientes
Se encontraron **cinco clústeres** con características distintas:
- **Clústeres 1 y 2:** Clientes leales con baja tasa de cancelación.
- **Clúster 3:** Clientes de alta rotación que requieren atención prioritaria.
- **Clústeres 0 y 4:** Clientes con potencial de retención mediante estrategias personalizadas.

#### Aplicaciones del Clustering
- Desarrollo de estrategias específicas para cada segmento.
- Mejora de programas de fidelización y promociones.

### **Conclusión y Recomendaciones**
1. **Optimizar Contratos:** Incentivar la contratación de planes a largo plazo.
2. **Promociones Grupales:** Fortalecer iniciativas como "trae a un amigo" y programas corporativos.
3. **Atención a Clientes Jóvenes:** Diseñar experiencias que resuenen con este grupo.
4. **Incrementar la Frecuencia de Uso:** Introducir beneficios para clientes frecuentes, como clases exclusivas o recompensas.

---

## 🛠 Tecnologías Utilizadas
- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Scikit-learn**
- **SciPy**

---

## 📊 Resultados Clave
1. **Factores Críticos de Cancelación:**
   - Proximidad, duración del contrato, frecuencia de uso y promociones grupales son factores decisivos.
2. **Modelos Predictivos:**
   - La regresión logística es eficiente para predecir la cancelación de clientes.
3. **Segmentación:**
   - El análisis de clustering permite identificar grupos con diferentes necesidades y prioridades.

---

## 🤝 Contribuciones

¡Las contribuciones son bienvenidas!  
Si deseas colaborar:  
1. Abre un *issue* para reportar problemas o sugerir mejoras.  
2. Crea un *pull request* para proponer cambios.  

Gracias por tu interés en este proyecto. Juntos podemos hacerlo aún mejor. 😊
