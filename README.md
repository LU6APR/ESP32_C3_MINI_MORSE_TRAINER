# ESP32_C3_MINI_MORSE_TRAINER
ESP32 C3 MINI MORSE TRAINER / OSCILATOR FOR IAMBIC KEYS

Keyer Iámbico + Decodificador CW con ESP32-C3 Mini
 Autor: LU6APR Pablo Ramos.
________________________________________
1. DESCRIPCIÓN DEL PROYECTO
Este proyecto consiste en la construcción de un Keyer Iámbico electrónico con decodificador de código Morse integrado, basado en el microcontrolador ESP32-C3 Super Mini.
El dispositivo permite:
•	Transmitir código Morse mediante una paleta iámbica (dos palancas: punto y raya)
•	Decodificar automáticamente el código Morse enviado
•	Mostrar el texto decodificado en una pantalla OLED (4 líneas)
•	Ajustar la velocidad de transmisión (WPM)
•	Espaciado automático después de 1 segundo de pausa
•	Borrado automático de pantalla al completar 4 líneas
•	Borrado manual con pulsación corta del botón

<img width="1971" height="1354" alt="circuit_image" src="https://github.com/user-attachments/assets/04f94726-7019-4d6b-8713-7bc5f921db1e" />

Copiar codigo en arduino ide, seleccionar puerto y ESP32 C3 mini, en mi caso use el LOLIN C3 MINI, compilar y subir al esp32 c3 mini.

Nota: el proyecto puede armarse sin la pantalla, y aun funcionara como oscilador para keys iambicos...
