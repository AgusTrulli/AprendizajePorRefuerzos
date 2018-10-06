# RLDiplodatos

Repositorio oficial de la materia Aprendizaje por Refuerzos de la Diplomatura en Ciencias de Datos, Aprendizaje 
Automático y sus Aplicaciones.

# Cómo ejecutar los agentes RL

Para instalar el entorno virtual y poder ejecutar los laboratorios, se requiere:

1. Descargar Anaconda para Python 3.6 desde [https://www.anaconda.com/download/]().

2. Instalar el entorno virtual provisto, descargando el archivo tensorflow.yml y desde la consola ejecutar:

*conda env create -f tensorflow.yml*

3. (Opcional) Descargar un entorno (ej: [Pycharm](https://www.jetbrains.com/pycharm/download/)) para poder realizar un 
debug paso a paso de los agentes. Si bien se puede trabajar desde jupyter notebook, suele resultar mucho más sencillo 
debuguear los agentes desde un IDE.

4. Correr los agentes a partir de alguno de los scripts por ejemplo *frozenlake_main_script.py* o 
*cartpole_main_script.py*.

5. Para incorporar el nuevo kernel a Jupyter Notebook tiene que ejecutar los siguientes comandos:

*source activate tensorflow*

*python -m ipykernel install --name tensorflow*

*source deactivate*

6. Para incorporar el entorno tensorflow creado en Pycharm, seleccionarlo desde:

* File -> Settings -> Project -> Project interpreter -> Show all (seleccionado en lista de entornos) -> Add -> Conda environment -> Existing environment -> tensorflow
