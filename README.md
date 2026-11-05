No usar el módulo en paralelización a menos que se pretenda sostener en el tiempo hasta el final de las ejecuciones.
Al momento, el proceso de recuperación de instancias se basa en la forma del árbol de directorios. Al paralelizar
las optimizaciones de un solo modelo (una configuración específica de un algoritmo específico en un mismo día),
se crean varios archivos en una sola instancia del lvdsl, sin embargo, al iniciarlo con recuperación, el sistema
ignorará los archivos anteriores al último.
