# dashboard-energia-fv
# 🌞 Dashboard de Análisis Fotovoltaico con Python

<img width="1598" height="762" alt="image" src="https://github.com/user-attachments/assets/be1a1eb6-89bf-41b7-b3fe-468720faec00" />


## 📌 Descripción
Dashboard interactivo para análisis de plantas solares fotovoltaicas, utilizando datos sintéticos generados programáticamente con Python. Perfecto para:
- Practicar análisis de datos en energía renovable
- Demostrar habilidades en Data Science
- Visualizar patrones de generación/consumo solar

## 🛠 Tecnologías Utilizadas
| Área | Herramientas |
|------|-------------|
| **Generación de Datos** | Python (Pandas, NumPy) |
| **Análisis** | Scikit-learn (Random Forest), Estadística |
| **Visualización** | Plotly, Plotly Dash |
| **Frontend** | HTML5, CSS3, Bootstrap 5 |
| **Despliegue** | GitHub Pages / Streamlit |

## 📊 Gráficas Incluidas
1. **Generación vs Consumo** (Comparación mensual)
2. **Eficiencia de Paneles** (Relación con temperatura)
3. **Distribución Horaria** (Curva típica diaria)
4. **Matriz de Correlación** (Variables clave)
5. **Modelo Predictivo** (Random Forest - MAE: 89 kWh)

## 🚀 Instalación
```bash
# Clonar repositorio
git clone https://github.com/tu-usuario/analisis-fotovoltaico.git

# Instalar dependencias
pip install -r requirements.txt

# Generar datos sintéticos (opcional)
python generar_datos.py

# Ejecutar dashboard local
python app.py
```
## 📂 Estructura de Archivos
```text
/proyecto-fotovoltaico
├── /data
│   ├── datos_planta_solar.csv       # Datos diarios generados
│   └── predicciones_solar.csv       # Resultados del modelo
├── /graficas
│   ├── produccion_consumo.html      # Gráfica interactiva 1
│   └── eficiencia_paneles.html      # Gráfica interactiva 2
├── app.py                           # Aplicación principal
├── generar_datos.py                 # Script generación datos
└── requirements.txt                 # Dependencias
```
## 🌟 Características Clave
Datos sintéticos con patrones realistas (radiación, temperatura, mantenimiento)

Modelo predictivo con R²: 0.94

Visualizaciones interactivas con tooltips

Diseño responsive (móvil/desktop)

Paleta de colores profesional (#18a3cf, #39badb, etc.)

## 📝 Notas Importantes
## ⚠️ Este proyecto utiliza datos sintéticos generados programáticamente para fines educativos. No representa una instalación solar real.

## 🤝 Contribuciones
¡Bienvenidas sugerencias! Abre un issue o envía un pull request para:

Mejorar el modelo predictivo

Añadir nuevos tipos de gráficas

Optimizar el frontend
