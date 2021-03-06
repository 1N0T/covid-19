![logo](https://raw.github.com/1N0T/images/master/global/1N0T.png)
# Jupyter notebook con gráficas evolución covid-19
Diversos gráficos con los datos diarios publicados por **Centro Europeo para la Prevención y el Control de las Enfermedades**

Si se sigue manteniendo la convención de la denominación, el notebook seleccionará el fichero más reciente.

 > **OJO !!!** me he encontrado con algún cambio de formato del fichero **excel**, de un día para otro. Por lo que podría ser que se repitiera en el futuro.

También he añadido datos recopilados por **Datadista** del **Ministerio de Sanidad, Consumo y Bienestar Social**.

### Dependencias.
Para ejecutar el notebook necesitas instalar.
 * jupyter notebook.
 * pandas.
 * matplotlib.
 * seaborn (se hace un uso meramente cosmético, se podría eleminar del notebook).
 * scipy (para la curva sigmoide).
 * xlrd (para procesar los ficheros excel).
 * Pillow (para insertar imagen de fondo).
 
### Resultado.
Este es el aspecto del resultado que puedes obtener.
![img01](https://raw.github.com/1N0T/images/master/covid-19/covid-19-spain.png)
![img01](https://raw.github.com/1N0T/images/master/covid-19/covid-19-modelo-matematico-spain.png)
![img01](https://raw.github.com/1N0T/images/master/covid-19/covid-19.png)
![img01](https://raw.github.com/1N0T/images/master/covid-19/covid-19-molins.png)
![img01](https://raw.github.com/1N0T/images/master/covid-19/covid-19-catalunya-altas.png)
![img01](https://raw.github.com/1N0T/images/master/covid-19/covid-19-mundial.png)

### Aplicación interactiva.
Tambíén he publicado una aplicación **vuejs** con la que se pueden consultar, para cada municipio de Catalunya, la evolución de positivos diarios (PCR + test rápidos).

https://1n0t.github.io/covid-19

![img01](https://raw.github.com/1N0T/images/master/covid-19/covid-19-municipios-catalunya.png)

