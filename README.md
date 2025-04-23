# Operaciones de Matrices con TensorFlow.js

Este proyecto implementa una aplicación web interactiva que permite realizar operaciones con matrices utilizando TensorFlow.js. Los usuarios pueden generar matrices aleatorias, ajustar sus dimensiones y realizar operaciones como suma y multiplicación matricial, visualizando los resultados en tiempo real.

## Características

- Interfaz de usuario intuitiva para definir dimensiones de matrices
- Generación aleatoria de matrices con valores enteros
- Soporte para operaciones de suma y multiplicación de matrices
- Validación automática de compatibilidad de dimensiones para cada operación
- Visualización clara de matrices y resultados
- Implementado completamente con TensorFlow.js

## Requisitos

- Navegador web moderno con soporte para JavaScript
- Conexión a internet (para cargar la biblioteca TensorFlow.js desde CDN)

## Instalación

1. Clona este repositorio o descarga el archivo HTML
2. Abre el archivo HTML en tu navegador

No se requiere instalación de dependencias adicionales, ya que el proyecto carga TensorFlow.js directamente desde CDN.

## Uso

1. Define las dimensiones de ambas matrices usando los controles numéricos
2. Haz clic en "Generar Matrices" para crear matrices aleatorias con las dimensiones especificadas
3. Las matrices se mostrarán en la pantalla con valores aleatorios enteros
4. Selecciona la operación que deseas realizar:
   - **Sumar Matrices**: Solo disponible cuando ambas matrices tienen las mismas dimensiones
   - **Multiplicar Matrices**: Solo disponible cuando el número de columnas de la matriz 1 es igual al número de filas de la matriz 2
5. El resultado se mostrará en pantalla
6. Puedes realizar una nueva operación con el botón correspondiente
