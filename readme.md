# Conversor de Divisas

Esta pequeña aplicación de Android te permite convertir una cantidad de euros a otras divisas utilizando un RecyclerView. La aplicación incluye un campo EditText para introducir la cantidad en euros y muestra el resultado de la conversión en una lista.

## Características

- Campo EditText para ingresar la cantidad en euros.
- RecyclerView con un adaptador personalizado.
- Elemento XML (row) para representar las vistas de la lista.
- Lista de divisas disponibles (AUD, USD) con sus respectivos valores de cambio respecto al euro.


## Instrucciones de Uso

1. Abre la aplicación en tu dispositivo Android.
2. Ingresa la cantidad en euros que deseas convertir en el campo EditText.
3. Observa la lista de divisas y sus valores de cambio actualizados automáticamente.

## Estructura del Proyecto

- **app/src/main/java/com/RecyclerView/conversordivisas:** Contiene los archivos fuente de la aplicación.
  - `MainActivity.java`: Actividad principal que maneja la lógica de la aplicación.
  - `DivisaAdapter.java`: Adaptador personalizado para el RecyclerView.

- **app/src/main/res/layout:** Contiene los archivos de diseño XML.
  - `activity_main.xml`: Diseño de la actividad principal con el campo EditText y el RecyclerView.
  - `item_divisa.xml`: Diseño del elemento de la lista (row) para mostrar cada divisa y su valor de cambio.

## Dependencias

```gradle
implementation 'com.android.support:recyclerview-v7:28.0.0'
