# TFM-redes-tensoriales-para-bioheat
*Redes tensoriales para resolver EDP*

En este repositorio encontrarás los notebook, programados en julia, correspondiente al trabajo **Resolución de la Ecuación de biocalor mediante redes tensoriales**, realizado por Antoni Bancells Fernández como TFM del Máster en Computación Cuántica de la UNIR. Podrás encontrar:
* Ejemplos preliminares con *Modelo_Heisenberg_XXZ*, para aprender a programar con la librería ITensor
   + DMRG
   + TEDB
   + TDVP
* Implementación de métodos clásicos para resolver la ecuación de biocalor. Todos empiezan con 0 (00, 01, ..., hasta 07):
   + Filtrado
   + Biocalor lineal estacionario
   + Biocalor no lineal estacionario
   + Evolución temporal de biocalor lineal mediante Crank-Nicolson
   + Evolución temporal de biocalor no lineal mediante aproximaciones de Picard y Crank-Nicolson
   + Evolución temporal de biocalor no lineal mediante distintos métodos numéricos
