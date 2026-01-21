# Retail Payroll System

Módulo de liquidación salarial desarrollado en Java que automatiza el cálculo de haberes para personal de retail mediante el procesamiento de bonificaciones y deducciones legales.

## Funcionamiento
El sistema permite gestionar la nómina basándose en tres categorías laborales específicas:
1. **Repositor:** Cálculo de sueldo base ($15.890) con aplicación de bono porcentual del 10%.
2. **Cajero:** Procesamiento de haberes fijos mensuales ($25.630,89).
3. **Supervisor:** Liquidación de sueldo bruto ($35.560,20) con deducción automática del 11% por aportes jubilatorios.

## Características Técnicas
* **Control de flujo:** Implementación de estructuras `if-else` anidadas para la selección de categorías y validación de entrada.
* **Precisión monetaria:** Uso de tipos de datos de punto flotante para el manejo de divisas y porcentajes.
* **Interfaz de consola:** Captura de datos dinámica mediante la clase `Scanner`.

## Requisitos
* JDK 8 o superior.
* IDE compatible (NetBeans recomendado) o terminal de comandos.
