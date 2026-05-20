# MINI_PC

Proyecto de Mini PC desarrollado con ESP32 y pantalla TFT ILI9341.

## Componentes

- ESP32
- TFT ILI9341
- Touch Screen
- Batería
- Módulo SD

## Funciones

- Menú interactivo
- Navegación táctil
- Aplicaciones
- Interfaz gráfica

## Diagrama de Flujo

```mermaid
flowchart TD

A[Inicio] --> B[Encender ESP32]
B --> C[Inicializar TFT]
C --> D[Mostrar Menu]
D --> E[Esperar Usuario]
E --> F[Ejecutar Aplicacion]
F --> G[Actualizar Pantalla]
G --> H[Fin]
```
