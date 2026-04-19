# Aprendizaje Automático con Learning ML

Demostraciones de aprendizaje automático mediante clasificación de imágenes y de números, usando [Learning ML](https://learningml.org/), una aplicación desarrollada por Juan David Rodríguez García.

Elaborado por [Mireia Ribera](https://eared.org/) para la asignatura **IA y accesibilidad** del [Máster de Formación Permanente en Accesibilidad digital para educación, comunicación y diseño](https://eared.org/).

Se trabaja con dos datasets:

- **`flores/`** — Clasificación de flores con el dataset Iris.
- **`mascotas/`** — Clasificación de imágenes de gatos y perros con el Oxford-IIIT Pet Dataset.

## Instrucciones de uso (LearningML)

URL directa del editor de LearningML:

- https://learningml.org/lml-editor/

### Flores (`flores/`)

1. Abre el editor: https://learningml.org/lml-editor/
2. Carga el dataset JSON: https://raw.githubusercontent.com/MireiaUB/jugandoIA/main/ml/flores/Iris.json
3. Valida el modelo con ejemplos de: https://raw.githubusercontent.com/MireiaUB/jugandoIA/main/ml/flores/validaciones-iris.txt
4. Puedes probar, por ejemplo, estas entradas del archivo de validación:
	- `5.0,3.2,1.2,0.2` -> `Iris-setosa`
	- `5.6,2.7,4.2,1.3` -> `Iris-versicolor`
	- `6.2,3.4,5.4,2.3` -> `Iris-virginica`

### Mascotas (`mascotas/`)

1. Abre el editor: https://learningml.org/lml-editor/
2. Carga el dataset JSON: https://raw.githubusercontent.com/MireiaUB/jugandoIA/main/ml/mascotas/GatoPerro.json
3. Valida con imágenes de la carpeta `val` del repositorio:
	- Ejemplo gato: https://raw.githubusercontent.com/MireiaUB/jugandoIA/main/ml/mascotas/val/gato/13.jpg
	- Ejemplo perro: https://raw.githubusercontent.com/MireiaUB/jugandoIA/main/ml/mascotas/val/perro/1065.jpg

## Fuentes de los datasets

### Flores (`flores/`) — Dataset Iris

Fisher, R.A. (1936). The use of multiple measurements in taxonomic problems. *Annals of Eugenics*, 7(2), 179–188. https://doi.org/10.1111/j.1469-1809.1936.tb02137.x

Disponible en el UCI Machine Learning Repository:  
Dua, D. and Graff, C. (2019). *UCI Machine Learning Repository*. University of California, Irvine, School of Information and Computer Science. https://archive.ics.uci.edu/dataset/53/iris

### Mascotas (`mascotas/`) — Oxford-IIIT Pet Dataset

Parkhi, O.M., Vedaldi, A., Zisserman, A., & Jawahar, C.V. (2012). Cats and Dogs. *IEEE Conference on Computer Vision and Pattern Recognition (CVPR)*. https://www.robots.ox.ac.uk/~vgg/data/pets/
