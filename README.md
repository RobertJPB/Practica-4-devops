# Práctica 4: Integración Continua (DevOps ITLA)

Repositorio para la práctica de integración continua utilizando **GitHub Actions**.

## Requisitos y Objetivos
1. Crear un programa "Hola Mundo" en JavaScript (`index.js`).
2. Configurar el workflow `.github/workflows/alerta.yml` en GitHub Actions para que, al realizar un push en la rama `main`, ejecute el script y envíe una notificación push a [ntfy.sh/devops-itla](https://ntfy.sh/devops-itla).

## Estructura del Proyecto
```
├── .github/
│   └── workflows/
│       └── alerta.yml
├── index.js
└── README.md
```

## Ejecución Local
```bash
node index.js
```
