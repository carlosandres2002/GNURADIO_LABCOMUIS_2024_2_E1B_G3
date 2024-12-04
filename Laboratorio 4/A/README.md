# Laboratorio 4-a: *Emisoras FM*

Este laboratorio se centró en el análisis de emisoras de radio en la región de Bucaramanga o cercanas a Bucaramanga utilizando la página de Radiofusión Sonora de Colombia y GNU Radio. Inicialmente, se identificaron emisoras cercanas y se extrajeron sus características principales, como el audio monoaural (L+R), la señal piloto para receptores estéreo, el canal L-R (estéreo) y subportadoras adicionales para transmisiones complementarias. Toda esta información se registró detalladamente en un archivo Excel, incluyendo las frecuencias de operación de cada emisora.

Se determino el ancho de banda de las emisoras utilizando GNU Radio y un analizador de espectros. Aunque el ancho de banda ideal se aproxima a 200 kHz, los análisis detallados mostraron valores más cercanos a 160 kHz al aplicar la regla de los 20 dB, revelando diferencias entre las estimaciones teóricas y las mediciones prácticas. Este contraste permitió comprender mejor el comportamiento real de las señales en el espectro radioeléctrico.

![Captura desde 2024-12-04 17-43-09](https://github.com/user-attachments/assets/43fc5b01-f75b-4326-85dd-38a1af3bcbf1)


![Captura desde 2024-11-13 17-10-44](https://github.com/user-attachments/assets/0060483b-fa3e-404e-933d-695426b28133)
Cómo se puede apreciar en esta imagen donde esta emisora tiene una frecuencia 102.5 MHz, donde contiene la señal L+R, contiene señal piloto, contiene la Señal L-R, pero no contiene la señal RBDS
