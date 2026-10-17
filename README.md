# TP2 - Reporte de movimientos de Ecobici

**Materia:** Programación Orientada a Datos  
**Universidad:** Universidad Católica Argentina (UCA)  
**Trabajo:** Trabajo Práctico 2 - Individual  
**Autor:** [Nombre y apellido]

## 1. Descripción del proyecto

Este proyecto consiste en desarrollar una aplicación en Python que permita analizar los viajes realizados mediante el sistema de bicicletas públicas Ecobici de la Ciudad de Buenos Aires.

La aplicación procesará registros de viajes para obtener información sobre las entradas y salidas de bicicletas en las distintas estaciones durante un período determinado.

## 2. Problema

El sistema Ecobici registra numerosos viajes entre diferentes estaciones. Analizar estos movimientos manualmente puede resultar complicado, especialmente cuando existen registros incompletos, duplicados o incorrectos.

Por este motivo, se propone desarrollar una herramienta que permita organizar y procesar los datos para generar reportes claros sobre la actividad de cada estación.

## 3. Usuarios

La aplicación está dirigida a estudiantes, investigadores y personas interesadas en analizar el funcionamiento del sistema de bicicletas públicas Ecobici.

## 4. Solución propuesta

Se desarrollará una aplicación en Python que permitirá:

- Leer archivos de viajes en formato CSV y JSON.
- Validar los registros e identificar posibles errores.
- Seleccionar viajes dentro de un período determinado.
- Calcular la cantidad de salidas y llegadas por estación.
- Obtener el balance neto de movimientos de cada estación.
- Generar un reporte con los resultados.
- Registrar los viajes rechazados y sus motivos.

## 5. Resultados esperados

El programa generará un reporte que incluirá, para cada estación:

- Cantidad total de salidas.
- Cantidad total de llegadas.
- Balance neto, calculado como llegadas menos salidas.

Un balance positivo indicará que se registraron más llegadas que salidas, mientras que uno negativo indicará lo contrario.

## 6. Alcance y limitaciones

En esta primera versión, el programa analizará los movimientos de bicicletas registrados durante un período seleccionado.

Los viajes se seleccionarán según su fecha de inicio y se contabilizarán tanto su estación de origen como su estación de destino.

El balance obtenido no representará la cantidad real de bicicletas disponibles, ya que no se considerarán el inventario inicial ni los movimientos de reposición.

## 7. Estado del proyecto

Proyecto en desarrollo. Actualmente se encuentra en la etapa de definición del problema y planificación de la aplicación.

Las secciones correspondientes a los datos, la instalación, la ejecución, las pruebas y los resultados se completarán durante el desarrollo.
