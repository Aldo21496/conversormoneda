# Proyecto de Conversión de Monedas

Este proyecto es una aplicación Java que permite convertir cantidades de dinero entre diferentes monedas utilizando la API de ExchangeRate-API. La aplicación soporta las siguientes conversiones:

- Dólares estadounidenses (USD) a Pesos argentinos (ARS)
- Pesos argentinos (ARS) a Dólares estadounidenses (USD)
- Dólares estadounidenses (USD) a Reales brasileños (BRL)
- Reales brasileños (BRL) a Dólares estadounidenses (USD)
- Dólares estadounidenses (USD) a Pesos colombianos (COP)
- Pesos colombianos (COP) a Dólares estadounidenses (USD)

## Características

- Menú interactivo para seleccionar el tipo de conversión.
- Entrada del usuario para la cantidad de dinero a convertir.
- Uso de la API de ExchangeRate-API para obtener las tasas de conversión actuales.
- Formato de resultado con dos decimales.
- Manejo de entradas no válidas del usuario.
- Loop de menú hasta que el usuario decida salir.

## Requisitos

- Java 17 o superior
- Biblioteca GSON para el manejo de JSON

## Instalación

1. Clona el repositorio:
    ```bash
    git clone https://github.com/tu-usuario/nombre-del-repositorio.git
    ```
2. Navega al directorio del proyecto:
    ```bash
    cd nombre-del-repositorio
    ```
3. Asegúrate de tener la biblioteca GSON. Si usas Maven, puedes agregar la siguiente dependencia en tu archivo `pom.xml`:
    ```xml
    <dependency>
        <groupId>com.google.code.gson</groupId>
        <artifactId>gson</artifactId>
        <version>2.8.8</version>
    </dependency>
    ```

## Uso

1. Compila el proyecto:
    ```bash
    javac Convertir.java
    ```
2. Ejecuta el proyecto:
    ```bash
    java Convertir
    ```
3. Sigue las instrucciones en pantalla para seleccionar el tipo de conversión y la cantidad a convertir.

## Ejemplo de Uso

```plaintext
Seleccione una opción:
1. Convertir de USD a ARS
2. Convertir de ARS a USD
3. Convertir de USD a BRL
4. Convertir de BRL a USD
5. Convertir de USD a COP
6. Convertir de COP a USD
0. Salir
