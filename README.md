# Bienvenido a cATprommer
Hola! Somos Dana y Salvador, sus compañeros y desarrolladores de este proyecto.

# Que es cATprommer?
Desarrollamos un programador para la memoria EEPROM AT28C64 diseñado para agilizar la clase de Arquitectura y Organización de Computadoras.

Nuestro proyecto incluye dos partes, una de hardware y una de software:
- **Hardware**: *cATprommer*
	Una placa de circuito impreso (PCB) que utiliza un Arduino Nano como cerebro para programar la EEPROM AT28C64.

- **Software**: *cATprommer - GUI* 
	Una interfaz de usuario sencilla que permite programar archivos .HEX utilizando nuestro hardware.

| **Hardware** | **Software** |
| - | - |
| <img src='https://github.com/mZynths/cATprommer/assets/30999576/f8f8c275-d7ef-4d56-9067-140f72535b92' width='300'> | <img src='https://github.com/mZynths/cATprommer/assets/30999576/80e47285-0c42-4ab4-8ca3-0c3757fb488b' width='300'> |

# Como instalar:
1. Instala los drivers para tu Arduino Nano [Link a las instrucciones de instalación](https://www.geekfactory.mx/tutoriales-arduino/driver-ch340-para-arduino-chinos-o-genericos/)
2. Descarga e instala la interfaz grafica [Haz click aquí para descargarla](https://github.com/mZynths/cATprommer/releases/latest/download/cATprommer_GUI_1.0.0_x64.msi)
3. Listo, tienes todo listo para estrenar tu programador!

# Como cargar un .hex utilizando el programador:
1. Conecta el Arduino y la memoria en la PCB como se muestra en la imagen:

<img src='https://github.com/mZynths/cATprommer/assets/30999576/80e099a6-6dc1-4c1f-a9ab-4b604d83de5e' width='300'>

3. Conecta el Arduino a tu computadora.
4. Abre la interfaz grafica.
<img src='https://github.com/mZynths/cATprommer/assets/30999576/8bbc6aea-9a04-4f41-94cd-1a5c7fbbaa7e' width='400'>

6. Haz click en "Buscar" y selecciona un archivo .hex:
<img src='https://github.com/mZynths/cATprommer/assets/30999576/c9e469e1-b7c4-4200-bfb5-342e1deed4e9' width='700'>

7. Haz click en "Escribir" y espera el mensaje "EEPROM programada con exito":
<img src='https://github.com/mZynths/cATprommer/assets/30999576/c15129d6-2240-40ff-a632-86d173cd5fbe' width='700'>

8. Listo! Ya puedes desconectar tu memoria.

