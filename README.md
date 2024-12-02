Trabajo final realizado en el marco del curso "Recuperación y Análisis de Texto con R" dictado en la Facultad de Ciencias Sociales (Udelar). 

Mpropongo realizar un análisis exploratorio de los discursos presidenciales argentinos desde la asunción de Mauricio Macri en 2015 hasta la actualidad. Dado el contexto técnico del curso no pretendo realizar un análisis interpretativo de corte teórico y me limitaré a una exploración de diferentes formas en que se puede explorar la temática y algunos comentarios descriptivos de estos.

El informe se estructurará siguiendo los requerimientos de la consigna, donde se explicará el proceso y las descripciones que se tomaron en el código. A su vez, la sección de análisis será estructurada en base a diferentes preguntas que irán surgiendo.

En términos generales se pretende responder cómo ha ido evolucionando la retórica presidencial argentina en los últimos tres periodos. Dado que la naturaleza discursiva de Javier Milei resulta particularmente llamativa se ahondara en la misma.

Utilicé múltiples recursos que requieren tiempo de procesamiento, por lo que trabajé en etapas agregando cambios sobre distintas bases. 
Se presentan a continuación los diferentes archivos. 

1. **rat_final.qmd**: Archivo principal, markdown con el codigo. 
2. **sentimiento.ipynb**: script en google colab con pysentimiento.
3. base_final.Rdata: Base resultante luego de todos los cambios generados en el preprocesamiento.
4. casarosada_anotada.Rdata: Base generada por Udpipe.
5.casarosada_final.Rdata: Base resultante antes de procesarlo con pysentimiento
6. casarosada_final_sentiment.csv: Base resultante luego de procesarlo con pysentimiento
7. casarosada_raw: Base inicial del scraping web







