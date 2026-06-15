# Servicio Hola Mundo con Flask

Este proyecto despliega un servicio Flask utilizando Docker Compose.

## Estructura

```text
holaflask/
├── app.py
├── Dockerfile
├── docker-compose.yml
├── README.md
└── .github/
    └── workflows/
        └── flask.yml
```

## Construir la imagen

```bash
docker compose build
```

## Ejecutar

```bash
docker compose up -d
```

## Verificar

Abrir en el navegador:

http://localhost:5000