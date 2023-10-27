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