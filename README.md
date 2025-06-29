# 📊 Análisis de Rendimiento - Alura Store

## 🎯 Descripción del Proyecto

Este proyecto tiene como objetivo ayudar al Sr. Juan a tomar una decisión estratégica sobre qué tienda de su cadena **Alura Store** debe vender para iniciar un nuevo emprendimiento. A través del análisis de datos de ventas, rendimiento y reseñas de las 4 tiendas, identificaremos la tienda menos eficiente y presentaremos una recomendación basada en datos.

## 🏪 Contexto del Negocio

**Alura Store** es una cadena de 4 tiendas que necesita optimizar su portafolio. El análisis se enfoca en:
- Evaluar el rendimiento financiero de cada tienda
- Analizar la satisfacción del cliente
- Identificar patrones de ventas y productos
- Determinar eficiencia operativa

## 🎯 Objetivos

### Objetivo Principal
Identificar qué tienda debe ser vendida basándose en métricas de rendimiento y eficiencia.

### Objetivos Específicos
- Analizar ingresos por tienda
- Evaluar categorías más vendidas
- Examinar reseñas y satisfacción del cliente
- Identificar productos estrella
- Analizar tiempos de envío promedio
- Crear visualizaciones claras y comprensibles

## 🛠️ Tecnologías Utilizadas

- **Python 3.8+**
- **Pandas** - Manipulación y análisis de datos
- **Matplotlib** - Visualización de datos
- **Seaborn** - Visualizaciones estadísticas avanzadas
- **NumPy** - Operaciones numéricas
- **Google Colab** - Desarrollo interactivo

## 📁 Estructura del Proyecto

```
alura-store-analysis/
│
├── data/
│   ├── raw/                    # Datos originales sin procesar
│   ├── processed/              # Datos procesados y limpios
│   └── external/               # Datos externos adicionales
│
├── notebooks/
│   ├── 01_exploratory_analysis.ipynb    # Análisis exploratorio
│   ├── 02_data_cleaning.ipynb           # Limpieza de datos
│   ├── 03_visualization.ipynb           # Creación de gráficos
│   └── 04_final_analysis.ipynb          # Análisis final y recomendaciones
│
├── src/
│   ├── __init__.py
│   ├── data_processing.py      # Funciones de procesamiento
│   ├── visualization.py        # Funciones de visualización
│   └── analysis.py            # Funciones de análisis
│
├── reports/
│   ├── figures/               # Gráficos generados
│   └── final_recommendation.md # Recomendación final
│
├── requirements.txt           # Dependencias del proyecto
├── README.md                 # Este archivo
└── .gitignore               # Archivos a ignorar en Git
```

## 📊 Métricas de Análisis

### 1. Métricas Financieras
- **Ingresos totales** por tienda
- **Ingresos promedio** por transacción
- **Margen de beneficio** (si disponible)
- **Tendencias de crecimiento**

### 2. Métricas de Producto
- **Categorías más vendidas**
- **Productos estrella**
- **Rotación de inventario**
- **Diversidad de productos**

### 3. Métricas de Cliente
- **Puntuación promedio de reseñas**
- **Número total de reseñas**
- **Distribución de calificaciones**
- **Tasa de satisfacción**

### 4. Métricas Operativas
- **Tiempo promedio de envío**
- **Eficiencia logística**
- **Volumen de transacciones**

## 📈 Visualizaciones Planificadas

### Gráficos Obligatorios (Mínimo 3)

1. **Gráfico de Barras**: Comparación de ingresos por tienda
2. **Gráfico Circular**: Distribución de categorías más vendidas
3. **Gráfico de Dispersión**: Relación entre reseñas y ventas
4. **Gráfico de Líneas**: Tendencias temporales de ventas
5. **Histograma**: Distribución de tiempos de envío
6. **Box Plot**: Análisis de variabilidad en ingresos

## 🚀 Cómo Ejecutar el Proyecto

### 1. Clonar el Repositorio
```bash
git clone https://github.com/tu-usuario/alura-store-analysis.git
cd alura-store-analysis
```

### 2. Crear Entorno Virtual
```bash
python -m venv venv
source venv/bin/activate  # En Windows: venv\Scripts\activate
```

### 3. Instalar Dependencias
```bash
pip install -r requirements.txt
```

### 4. Ejecutar Colab
```bash
Google colab
```

### 5. Seguir el Orden de Análisis
1. `01_exploratory_analysis.ipynb`
2. `02_data_cleaning.ipynb`
3. `03_visualization.ipynb`
4. `04_final_analysis.ipynb`

## 📋 Lista de Verificación

### Análisis de Datos
- [ ] Cargar datos CSV con Pandas
- [ ] Explorar estructura de datos
- [ ] Limpiar y preparar datos
- [ ] Calcular métricas clave
- [ ] Identificar patrones y tendencias

### Visualizaciones
- [ ] Crear al menos 3 gráficos diferentes
- [ ] Incluir gráfico de barras
- [ ] Incluir gráfico circular
- [ ] Incluir gráfico de dispersión
- [ ] Asegurar claridad visual
- [ ] Añadir títulos y etiquetas

### Recomendación Final
- [ ] Analizar resultados
- [ ] Identificar tienda menos eficiente
- [ ] Justificar decisión con datos
- [ ] Escribir recomendación clara
- [ ] Incluir próximos pasos

## 📊 Estructura de Datos Esperada

```python
# Ejemplo de estructura de datos
datos_tienda = {
    'tienda_id': [1, 2, 3, 4],
    'nombre_tienda': ['Tienda A', 'Tienda B', 'Tienda C', 'Tienda D'],
    'ingresos_totales': [float],
    'num_transacciones': [int],
    'puntuacion_promedio': [float],
    'total_reseñas': [int],
    'tiempo_envio_promedio': [float],
    'categoria_principal': [str]
}
```

## 🤝 Contribución

Este proyecto es parte de un desafío educativo. Para contribuir:

1. Fork el proyecto
2. Crea una rama para tu feature (`git checkout -b feature/nueva-funcionalidad`)
3. Commit tus cambios (`git commit -m 'Añadir nueva funcionalidad'`)
4. Push a la rama (`git push origin feature/nueva-funcionalidad`)
5. Abre un Pull Request

## 📝 Notas Importantes

- **Enfoque en Datos**: Todas las decisiones deben estar respaldadas por análisis de datos
- **Visualización Clara**: Los gráficos deben ser fáciles de interpretar
- **Recomendación Práctica**: La decisión final debe ser actionable para el Sr. Juan
- **Documentación**: Documenta cada paso del análisis

## 🏆 Criterios de Éxito

- ✅ Análisis completo de las 4 tiendas
- ✅ Mínimo 3 visualizaciones diferentes
- ✅ Recomendación clara y justificada
- ✅ Código limpio y documentado
- ✅ Conclusiones basadas en datos

## 📞 Contacto

**Desarrollador**: [Tu Nombre]  
**Email**: [tu-email@ejemplo.com]  
**LinkedIn**: [tu-perfil-linkedin]

---

*Este proyecto forma parte del desafío de análisis de datos de Alura Store. El objetivo es demostrar habilidades en análisis de datos, visualización y toma de decisiones basada en datos.*
