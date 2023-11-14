# Apuntes de inteligencia artificial en español

Recopilatorio de apuntes sobre conceptos de inteligencia artificial.

* **Conceptos básicos**
  * [Datos vs información vs conocimiento](definiciones/DF_01_Datos_vs_informacion.ipynb)
  * [Ciencia de datos, aprendizaje automático y aprendizaje profundo](definiciones/DF_02_DS_ML_DL.ipynb)
  * [Tipos de aprendizaje automático](definiciones/DF_03_ML_types.ipynb)

* **Estadística**
  * [Estadística definición](estadistica/ST_01_Estadistica_definicion.ipynb)
  * [Población vs muestra](estadistica/ST_02_Poblacion_muestra.ipynb)
  * [Variables definición](estadistica/ST_03_Variables_definicion_tipos.ipynb)

## Exportar notebook a HTML

```bash
jupyter nbconvert --to html --TagRemovePreprocessor.remove_input_tags remove-input file_name.ipynb
```

Al exportar el notebook a PDF ignora el HTML embebido en las celdas de _markdown_ ([bug conocido](https://github.com/jupyter/nbconvert/issues/552)), como por ejemplo en que se usa para ajustar el tamaño y la posición de las imágenes.
