# Backend del Proyecto – FastAPI

## Instalación
pip install -r requirements.txt

## Ejecución
python -m uvicorn main:app --reload

## Endpoints disponibles
- GET /students
- GET /students/{id}

## Testing 
python -m pytest

## Docker
docker build -t daw-backend .
docker run -p 8000:8000 daw-backend

## CI/CD – GitHub Actions
Workflows ubicados en backend/.github/workflows/
- backend-test.yml
- backend-docker.yml

Requiere secrets:
- DOCKERHUB_USERNAME
- DOCKERHUB_TOKEN








## Informacion impresa
--
origin  https://github.com/Patatuela1/proyecto_examen-.git (fetch)
origin  https://github.com/Patatuela1/proyecto_examen-.git (push)
--
## Informacion Grafica
```
* 313ed10 (HEAD -> rama1_DiegoLopez) Informacion Grafica añadida
* a64bc9f (origin/main, rama2_DiegoLopez, main) Primer commit en GitLab
* ddf5b26 Primer commit
```
