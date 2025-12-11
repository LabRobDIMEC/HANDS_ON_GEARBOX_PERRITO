# Planetary gear reducer design design and control for Quadruped Robot.

## TEMARIO
Introducción.
Ejemplos de robots caminantes, reconocimiento de componentes.
Diseño de reductor planetario.
Armado de reductor planetario en grupos de 2-3 personas.
Control de actuador en lazo cerrado con Arduino.

Instructor: [Ulises Campodónico](https://github.com/uwulises)

The workshop addresses the design, calculation, assembly, and closed-loop control of a planetary gearbox to amplify BLDC motor torque. The workshop will cover parts identification, actuator assembly, and closed-loop commissioning using the SimpleFOC Arduino library.

## Design aspects for our perrito quadruped robot

This project was born in early 2024 at the [Mechanical Engineering Department](https://dimec.uchile.cl/) by Design of Mechanical Systems students.

<img src= perrito_iso.png width=600>

## Gearbox design

<img src= reductora_hombro.png width=200>

<img src= reductora_hombro_explotada.png width=500>


## Motor Control with SimpleFOC and drv8302+RPi Pico HAT

Check the [Position control document](motor_control/README.md) for position control using the SimpleFOC arduino Library.


### Part list

#### Bolsitas para pernos
- (4) M5x20 avellanado
- (4) Tuerca M5 seguro plástico
- (5) M4x50
- (10) Tuerca M4 seguro plástico 
- (5) M4x35
- (4) M4x12 avellanado
- (4) M4x12
- (4) M3x10 avellanado
#### Rodamientos por reductora
- (8) ID5 OD11 e5
- (2) ID60 OD78 e10
#### Partes por reductora
- (1) Pinza Exterior
- (1) Pinza Interior
- (1) Eje Ex-Pinza
- (1) Tapa Anclaje Motor Derecho
- (1) Tapa Anclaje Motor Izquierdo
- (1) Tapa Salida Motor
- (5) Espaciadores Motor
- (1) Soporte Encoder
- (2) Sol
- (8) Planetas
- (1) Corona
- (1) Base del sol
- (1) Portaplanetas 1ra Etapa
- (1) Brazo portaplanetas
- (1) Portaplanetas 2da Etapa
- (4) Pin planetas
- (1) Tapa caja reductora
#### Hardware por reductora
- (1) Driver DRV8302
- (1) Hat RPi Pico
- (1) Encoder AS5600
- (1) kit cables
