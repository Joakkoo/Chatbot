**Clonar el repositorio y crear un entorno virtual**
```bash
git clone https://github.com/python-engineer/chatbot-deployment.git
cd chatbot-deployment
python -m venv venv
venv/Scripts/activate
```

**Instalar dependencias**
```bash
(venv) pip install Flask torch torchvision nltk
```

**Instalar el paquete nltk**
```bash
(venv) python
>>> import nltk
>>> nltk.download('punkt')
```
**Ejecutar el frontend**
1. La ejecucion se puede hacer con la extension de python en visual studio
o
2. Ejecutando el comando py app.py y entrando al link que proporciona la respuesta de la terminal
