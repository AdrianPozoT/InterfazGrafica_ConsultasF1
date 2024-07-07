# Proyecto de Consulta de Resultados de Constructores y Conductores

Este proyecto consiste en una aplicación JavaFX que consulta una base de datos para mostrar los resultados de constructores y conductores en dos interfaces similares.

## Estructura del Proyecto

El proyecto está organizado de la siguiente manera:


- `ConstructorMain.java`: Clase principal para la interfaz de resultados de constructores.
- `Main.java`: Clase principal para la interfaz de resultados de conductores.
- `ConstructorResult.java`: Modelo para los resultados de constructores.
- `DriverResult.java`: Modelo para los resultados de conductores.
- `ConstructorsRepository.java`: Repositorio para consultar los resultados de constructores.
- `DriversRepository.java`: Repositorio para consultar los resultados de conductores.
- `SeasonRepository.java`: Repositorio para consultar las temporadas disponibles.
- `database.properties`: Archivo de configuración para la conexión a la base de datos.

## Ejecución

1. Asegúrate de tener Java 8 o superior instalado.
2. Clona este repositorio.
3. Configura la conexión a la base de datos en `database.properties`.
4. Ejecuta `ConstructorMain` para ver los resultados de constructores o `Main` para los resultados de conductores.

## Dependencias

- JavaFX: Utilizado para la interfaz gráfica.
- MySQL Connector: Para la conexión a la base de datos.

## Vistas de las Interfaces Gráficas

![Captura de pantalla 2024-07-07 150032](https://github.com/AdrianPozoT/InterfazGrafica_ConsultasF1/assets/168159379/05d8745c-321c-48d1-94b3-77ba08c13517)


![Captura de pantalla 2024-07-07 150121](https://github.com/AdrianPozoT/InterfazGrafica_ConsultasF1/assets/168159379/9ed1c44a-5fd5-4d5b-8179-82d63c2161cb)


