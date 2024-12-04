# Laboratorio 2-b: *Canal*

Para el laboratorio 2B se supervisa que, con una frecuencia de corte mínima, el filtro solo permite el paso de la componente DC y bloquea los armónicos. Al aumentar la frecuencia del filtro, se empieza a permitir el paso de los armónicos, y con ello se genera una señal sinusoidal pura. A medida que la frecuencia sigue aumentando, aparecen más armónicos, creando una forma de onda cuadrada, según el principio de las series de Fourier.

Para determinar el nivel máximo de ruido tolerable en el sistema de audio, se ajusta el filtro para dejar pasar la señal de audio y observar el rango de frecuencias de la canción. Luego, se introdujo el ruido para identificar un rango con el mínimo ruido perceptible al escuchar la canción. Finalmente, se ajustó la frecuencia del filtro para optimizar la señal de audio y reducir al máximo el ruido.

*Filtro usado en el laboratorio:*

![Filtro pasa banda.jpeg](https://github.com/carlosandres2002/GNURADIO_LABCOMUIS_2024_2_E1B_G3/blob/main/Laboratorio%202/B/Filtro%20pasa%20banda.jpeg)

Los filtros son componentes fundamentales en el procesamiento de señales, utilizados para modificar o suprimir ciertas frecuencias de una señal en función de sus características. Dependiendo de la frecuencia de corte y la respuesta deseada que en este caso en particular es de 15 KHz

- Filtro Paso Bajo (Low-Pass Filter) : Permite el paso de frecuencias por debajo de una frecuencia de corte determinada, mientras que atenúa las frecuencias superiores a esa. Este tipo de filtro es útil para eliminar el ruido de alta frecuencia en una señal.
