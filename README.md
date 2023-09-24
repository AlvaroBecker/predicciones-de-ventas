# Predicciones de Ventas 📈

Este proyecto tiene como objetivo analizar y predecir las ventas de productos en diferentes tiendas. Se realizan varios pasos de preprocesamiento, análisis exploratorio y modelado para llegar a las predicciones.

## Contenido 🌟

1. **Instalación de dependencias**
2. **Importación de bibliotecas**
3. **Carga de datos**
4. **Análisis exploratorio de datos (EDA)**
   - ¿Cuántas filas y columnas?
   - Tipos de datos en cada variable
   - Detección y eliminación de duplicados
   - Identificación y manejo de valores faltantes
   - Corrección de categorías inconsistentes
   - Estadísticas resumidas para columnas numéricas
5. **Preprocesamiento de datos**
   - Escalamiento
   - Codificación one-hot
   - Imputación
6. **Modelado y predicción**
7. **Visualización de resultados**

## Diccionario de datos

| Variable                     | Descripción                                                                                                    |
|------------------------------|----------------------------------------------------------------------------------------------------------------|
| Item_Identifier              | Identificación única del producto                                                                              |
| Item_Weight                  | Peso del producto                                                                                              |
| Item_Fat_Content             | Si el producto es bajo en grasa o regular                                                                      |
| Item_Visibility              | Porcentaje de la superficie total de exposición de todos los productos de una tienda asignada al producto concreto |
| Item_Type                    | Categoría a la que el producto pertenece                                                                       |
| Item_MRP                     | Precio máximo de venta al público (precio de catálogo) del producto                                           |
| Outlet_Identifier            | Identificación única de la tienda                                                                              |
| Outlet_Establishment_Year    | El año en que se estableció la tienda                                                                         |
| Outlet_Size                  | El tamaño de la tienda en cuanto al área total                                                                 |
| Outlet_Location_Type         | El tipo de área donde se encuentra la tienda                                                                   |
| Outlet_Type                  | Si el punto de venta es una tienda de comestibles o algún tipo de supermercado                                |
| Item_Outlet_Sales            | Ventas del producto en una tienda particular. Es la variable objetivo a predecir.                             |

## Instalación 💻

Para instalar las dependencias necesarias, ejecuta:

```
!pip install -r requirements.txt
```

## Uso 🚀

Para utilizar este proyecto, simplemente clona el repositorio y ejecuta el Jupyter Notebook `predicciones_de_ventas.ipynb`. Asegúrate de tener todas las dependencias instaladas.

## Contribuciones 🤝

Las contribuciones son bienvenidas. Si encuentras algún error o tienes alguna sugerencia, no dudes en abrir un issue o hacer un pull request.

## Contacto 💌

- **Nombre del autor:** alvarobeckerruiz@gmail.com
- **LinkedIn:** [https://www.linkedin.com/in/alvaro-becker-1335391b2/](https://www.linkedin.com/in/alvaro-becker-1335391b2/)
