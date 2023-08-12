# fundamentosMachineLearning
Apuntes de las practicas realizadas a lo largo del curso de fundamentos de Machine Learning de Platzi.

## instalando python3
```bash
sudo apt-get install python3
```
## instalando pip
```bash
sudo apt-get install python3-pip
```
## instalando virtualenv
```bash
sudo pip3 install virtualenv
```


# Entorno virtual de python (virtualenv) para linux
## creando el entorno virtual
```bash
python3 -m venv env
```
## activando el entorno virtual
```bash
source env/bin/activate
```
## instalando las dependencias
```bash
pip install -r requirements.txt
```
## desactivando el entorno virtual
```bash
deactivate
```
## creando el archivo requirements.txt
```bash
pip freeze > requirements.txt
```

#gitingnore
## creando el archivo .gitignore
```bash