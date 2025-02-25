# Propedeutico 
*Hola Mundo*

**Hola Mundo**

## HOLA


En este repositorio encuentran el contenido para el propedéutico (*aka* prope) de la MCD en el ITAM impartido por el prof. Erick Palacios Moreno, github: [palmoreck](https://github.com/palmoreck).

### En [liga](https://drive.google.com/file/d/1A5FF9lOFYXb4CdbAQaOp79x1A-9-j36b/view?usp=sharing) encuentran el temario.

### En [liga2](https://hackmd.io/@palmoreck/rJQQIEmbv) una presentación de introducción al prope verano 2021.

### Con el siguiente botón pueden unirse\* al chat del verano del 2022 en [gitter](https://gitter.im/): [![Gitter](https://badges.gitter.im/prope-2022/community.svg)](https://gitter.im/prope-2022/community?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)


\***Se puede hacer el registro con su cuenta de [github](https://github.com/)**.

### En el prope utilizaremos la imagen de [docker](https://www.docker.com/) `palmoreck/jupyterlab_prope_r_kernel_tidyverse:3.4.3` cuya documentación la encuentran [aquí](https://github.com/palmoreck/dockerfiles/tree/master/jupyterlab/prope_r_kernel_tidyverse)\*. 

\* Tal imagen de *docker* se descarga con un `docker pull palmoreck/jupyterlab_prope_r_kernel_tidyverse:3.4.3` desde la terminal una vez hayan instalado *docker* en sus computadoras. Ver [herramientas/docker/](herramientas/docker/) para referencias de docker.

Para uso de la imagen de *docker* anterior ver [contenedor_de_docker_para_prope](contenedor_de_docker_para_prope.ipynb)

## Ramas del repositorio.

En este repositorio se han creado diferentes ramas que pueden ser accesadas como se aprecia en esta imagen:

<img width="320" alt="imagen" src="https://user-images.githubusercontent.com/3290689/83956287-05548100-a822-11ea-8398-12dc2bb8810f.png">

Seleccionar por ejemplo la rama **prope-2019-1** (u otra) para información del curso propedéutico de 2019.


**En [prope-2022](https://github.com/ITAM-DS/Propedeutico/tree/prope-2022) acceden a la rama del curso del verano 2022.**

## Breve explicación del repositorio en la rama main.

En la carpeta [Python](Python) encuentran temas del cálculo numérico en *Python3*.

En la carpeta [R](R) encuentran temas de probabilidad y estadística en *R*.

En la carpeta [herramientas](/herramientas) encuentran información de herramientas como [docker](https://www.docker.com/), [git](https://git-scm.com/) y [bash](https://www.gnu.org/software/bash/).

## Sobre las notas

Las notas de cada tema están escritas en [Jupyter notebooks](https://jupyter.org/). Ver [I python, You R, We Julia](https://blog.jupyter.org/i-python-you-r-we-julia-baf064ca1fb6) para algunas características de tales *notebooks*. Ver [notebook](https://jupyterlab.readthedocs.io/en/stable/user/notebook.html) para funcionalidad de los *notebooks*. Ver [Jupyter kernels](https://github.com/jupyter/jupyter/wiki/Jupyter-kernels) para una tabla de los [kernels](https://jupyter.readthedocs.io/en/latest/install-kernel.html) disponibles en *jupyter* (que hacen posible ejecutar instrucciones en el lenguaje *R*, por ejemplo, en tales notebooks).

### Para convertir una nota a pdf

Usar botón de [binder](https://mybinder.org/) [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/palmoreck/dockerfiles-for-binder/jupyterlab_prope_r_kernel_tidyverse?urlpath=lab/tree/Propedeutico)

Abrir una nueva terminal y ejecutar lo siguiente:

```
bash
cd <directorio donde está la nota>
jupyter-nbconvert --to webpdf <nombre de la nota>.ipynb
```

El pdf estará dentro del directorio en el que está la nota y se puede descargar dando click derecho en la barra lateral izquierda del *jupyterlab*.


<img width="350" alt="imagen" src="https://user-images.githubusercontent.com/3290689/127781146-b3176fe9-cce2-4404-a8f2-1d207ac337ab.png">  


## Interactividad

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/palmoreck/dockerfiles-for-binder/jupyterlab_prope_r_kernel_tidyverse?urlpath=lab/tree/Propedeutico) <--- con este botón de una forma interactiva se pueden ejecutar los notebooks de jupyter tanto para *Python3* como para *R* dentro de los directorios de [Python](Python) y de [R](R).

## Organización de github classroom

La organización [prope-2022-gh-classroom](https://github.com/prope-2022-gh-classroom) fue creada para alojar repositorios de [github classroom](https://classroom.github.com/) (ver [github education](https://github.com/education)). Esta organización será nuestro *playground* para el curso de verano 2022 :)


## Índice de notas

Cada número contiene información del tema respectivo, dar click en el tema de interés.

**[Python](Python)**

**Introducción:**

[1. Información general](Python/clases/1_introduccion/1_informacion_general.ipynb)

[2. Core Python](Python/clases/1_introduccion/2_core_python.ipynb)

[3. Funciones y módulos](Python/clases/1_introduccion/3_funciones_y_modulos.ipynb)

[4. Módulos: NumPy y Matplotlib](Python/clases/1_introduccion/4_modulos_numpy_matplotlib.ipynb)

**Cálculo Diferencial e Integral:**

[0. Módulo: SymPy](Python/clases/2_calculo_DeI/0_modulo_sympy.ipynb)

[1. Aproximación a derivadas e integrales de forma numérica](Python/clases/2_calculo_DeI/1_aproximacion_a_derivadas_e_integrales.ipynb)

[Ejemplo al no usar bloque de if name main en modulo](Python/clases/2_calculo_DeI/Ejemplo_al_no_usar_bloque_if_name_main_en_modulo.ipynb)

**Álgebra lineal:**

[0. Definiciones generales](Python/clases/3_algebra_lineal/0_definiciones_generales.ipynb)

[1. Ecuaciones lineales](Python/clases/3_algebra_lineal/1_ecuaciones_lineales.ipynb)

[2. Interpolación](Python/clases/3_algebra_lineal/2_interpolacion.ipynb)

[3. Mínimos cuadrados lineales](Python/clases/3_algebra_lineal/3_minimos_cuadrados.ipynb)

[4. SVD](Python/clases/3_algebra_lineal/4_SVD_y_reconstruccion_de_imagenes.ipynb)

**[R](R)**

**Introducción:**

[1. Información general](R/clases/1_introduccion/1_informacion_general.ipynb)

[2. Core R](R/clases/1_introduccion/2_core_R.ipynb)

[3. ggplot2](R/clases/1_introduccion/3_ggplot2.ipynb)

**Probabilidad:**

[1. Elementos de probabilidad](R/clases/2_probabilidad/1_elementos_de_probabilidad.ipynb)

[2. Propiedades de la probabilidad](R/clases/2_probabilidad/2_propiedades_de_la_probabilidad.ipynb)

[3. Métodos de conteo](R/clases/2_probabilidad/3_metodos_de_conteo.ipynb)

[4. Probabilidad condicional](R/clases/2_probabilidad/4_probabilidad_condicional.ipynb)

[5. Independencia](R/clases/2_probabilidad/5_independencia.ipynb)

[6. Teorema de Bayes](R/clases/2_probabilidad/6_teorema_de_Bayes.ipynb)

[7. Variables aleatorias](R/clases/2_probabilidad/7_variables_aleatorias.ipynb)

**Estadística:**

[1. Elementos de Estadística descriptiva](R/clases/3_estadistica/1_elementos_de_estadistica_descriptiva.ipynb)

[2. Distribuciones comunes](R/clases/3_estadistica/2_distribuciones_comunes.ipynb)

[3. Elementos de inferencia](R/clases/3_estadistica/3_elementos_de_inferencia.ipynb)

[4. Regresión lineal](R/clases/3_estadistica/4_regresion_lineal.ipynb)
