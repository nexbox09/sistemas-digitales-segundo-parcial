# Elevador de Dos Niveles - Máquina de Estados Finitos (FSM)

Este proyecto documenta el diseño de una Máquina de Estados Finitos (FSM) para un elevador de dos niveles. La FSM controla las transiciones entre los estados del elevador basándose en la entrada de botones dentro del elevador y en los pisos.

## Descripción de la FSM

La FSM del elevador se compone de varios estados que representan las diferentes posiciones y acciones del elevador, como estar detenido en un piso, moviéndose entre pisos, y abriendo puertas.

### Estados de la FSM

- **S0**: Detenido en el piso 1.
- **S1**: Detenido en el piso 1 con la puerta abriendo.
- **S2**: Subiendo del piso 1 al piso 2.
- **S3**: Detenido en el piso 2.
- **S4**: Detenido en el piso 2 con la puerta abriendo.
- **S5**: Bajando del piso 2 al piso 1.

### Transiciones de Estados

Las transiciones entre los estados se realizan en función de las señales de entrada, que son las solicitudes de movimiento desde los botones internos y externos del elevador.

![image](https://github.com/nexbox09/sistemas-digitales-segundo-parcial/assets/68700670/e7fa227c-84c6-4350-97d2-5e99485afb20)


### Diagrama de Transición de Estados

El diagrama de transición de estados visualiza las transiciones permitidas entre los estados basadas en las entradas actuales.

### Tabla de Transición de Estados

Esta tabla proporciona una representación tabular de las transiciones, mostrando el estado actual, la entrada, y el siguiente estado del elevador.

## Salidas de la FSM

La FSM genera varias salidas que controlan las acciones del elevador, como moverse hacia arriba o hacia abajo y abrir las puertas.

### Tabla de Salidas

Define las acciones correspondientes a cada combinación de estado actual y entrada, como moverse hacia arriba, moverse hacia abajo, y abrir las puertas.

### Indicadores de Salida

Proporciona información visual o auditiva sobre el estado actual del elevador, como indicadores de piso o direcciones de movimiento.

## Representación Gráfica

El proyecto incluye diagramas y circuitos que representan visualmente la estructura y el comportamiento de la FSM, facilitando la comprensión y el análisis del diseño del elevador.

## Uso

Este documento puede utilizarse como referencia para la implementación de una FSM en hardware o software, proporcionando una base sólida para el desarrollo de sistemas de control para elevadores o sistemas similares.


