# DATATHONHeyBalance

Documentación Técnica del Proyecto
Limpieza de Datos
Se realizó un proceso exhaustivo de limpieza de datos utilizando las bibliotecas Pandas y expresiones regulares (re). Este paso permitió normalizar, transformar y depurar los datos crudos para su posterior análisis.

Manejo de Valores Nulos
Se abordó la presencia de valores nulos aplicando métodos basados en probabilidades aritméticas, lo que permitió una imputación coherente de datos faltantes sin comprometer la integridad estadística del conjunto de datos.

Categorización mediante Análisis de Correspondencias Múltiples (MCA)
Se empleó un enfoque preciso de Análisis de Correspondencias Múltiples (MCA) para la categorización de variables cualitativas, lo que facilitó la reducción dimensional y la interpretación de patrones en los datos.

Modelado Predictivo con Machine Learning
En la etapa de análisis, se implementó un modelo de regresión lineal con el objetivo de predecir el saldo estimado de un usuario específico y evaluar si será capaz de cubrir sus gastos fijos mensuales.

Análisis Comparativo de Usuarios
Para identificar oportunidades de mejora en la salud financiera del usuario, se integró un segundo modelo de machine learning (por ejemplo, Random Forest Classifier o K-Nearest Neighbors) con el fin de comparar su perfil financiero con el de otros usuarios de características similares. Este análisis permitió detectar diferencias clave y generar recomendaciones personalizadas.

Interfaz de Usuario y Visualización
El desarrollo del frontend se llevó a cabo utilizando SwiftUI, incorporando además un widget informativo que ofrece al usuario una visualización en tiempo real de su desempeño financiero mensual.

Back-End y API
La API fue desarrollada con Express.js y desplegada a través de la plataforma Railway, permitiendo una comunicación eficiente entre el cliente y el servidor, así como el manejo seguro de los datos del usuario.

