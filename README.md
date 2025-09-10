# Programación orientada a objetos (POO) en caso ficticio

# Resumen del Proyecto
Este proyecto aborda el desafío de optimizar la capacidad de carga en la bodega de equipaje de la aerolínea ficticia "ValpoFly". El objetivo principal es desarrollar una solución analítica que permita anticipar la capacidad de carga disponible con un mínimo de 4 horas de antelación a cada vuelo, permitiendo así maximizar el uso del espacio y generar oportunidades de negocio adicionales, como el transporte de carga extra.

---

# Metodología y Enfoque
La solución se centra en la Programación Orientada a Objetos (POO) como pilar fundamental para la creación de un prototipo robusto, modular y escalable.

  - **Generación de Datos Sintéticos:** Se utilizó un enfoque de POO para crear la clase CreadorDatosSinteticos en Python. Esta clase encapsula toda la lógica necesaria para generar datos sintéticos representativos de vuelos, pasajeros y equipaje, simulando un entorno de datos real y permitiendo la reproducibilidad del experimento.

  - **Análisis y Lógica de Negocio:** Se implementaron métodos para procesar los datos generados, calcular el peso y volumen total del equipaje por vuelo y compararlo con las capacidades máximas de la aeronave.

  - **Índice de Potencial de Carga (IPC):** Como parte del prototipo, se conceptualiza un IPC, un indicador clave para que el área de operaciones pueda tomar decisiones rápidas y eficientes sobre la capacidad sobrante.

  - **Visualización de Datos:** Se emplearon librerías como Matplotlib y Seaborn para analizar la distribución de los datos sintéticos y validar que el escenario simulado fuera coherente.

---

# Demostración de Conocimientos en Programación Orientada a Objetos (POO)
Este proyecto demuestra un sólido entendimiento de los principios de la POO aplicados a un problema de ciencia de datos:

  - **Encapsulamiento:** La clase CreadorDatosSinteticos agrupa y oculta la complejidad de la generación de datos, exponiendo una interfaz sencilla para su uso.

  - **Modularidad y Reutilización:** La estructura en clases y métodos permite que el código sea fácil de mantener, probar y reutilizar en diferentes contextos o con nuevas fuentes de datos.

  - **Escalabilidad:** El diseño orientado a objetos facilita la expansión del proyecto, como la integración con bases de datos reales, la implementación de modelos de machine learning o su despliegue en un entorno de producción.

---

# Tecnologías Utilizadas
- Lenguaje: Python

- Librerías Principales: Pandas, UUID, Matplotlib, Seaborn

- Entorno de Desarrollo: Jupyter Notebook

---

# Próximos Pasos y Escalabilidad
El notebook también plantea una hoja de ruta para llevar este prototipo a un entorno de producción, incluyendo:

- La conexión a bases de datos operacionales.

- El uso de orquestadores de tareas como Apache Airflow para automatizar la ejecución del análisis.

- La implementación de un modelo de Machine Learning para predecir la demanda de carga.

- La creación de un dashboard en tiempo real (ej. Power BI) para la visualización de los resultados.
