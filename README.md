# 🌎 Catálogo México INEGI – JSON Abreviado

¡Hola! 👋 Soy Yago, y este proyecto nace de la necesidad de tener un **JSON práctico y accesible** con todos los estados, municipios y localidades de México, basado en los datos del INEGI.

La idea es que cualquier desarrollador, estudiante o curioso pueda **consultar, usar y desplegar esta información fácilmente** en sus proyectos web, apps o sistemas de datos, sin complicaciones.

## ¿Qué hay en este repositorio?

- **`mexico_inegi.json`**: El JSON completo con todos los estados, municipios y localidades.
- **`LICENSE`**: Licencia MIT para que cualquiera pueda usar y adaptar el proyecto.
- **`README.md`**: Sí, este archivo que estás leyendo 😄

El JSON tiene esta estructura:

```json
[
  {
    "ce": "01",              // Clave del estado
    "ne": "Aguascalientes",  // Nombre del estado
    "m": [                   // Lista de municipios
      {
        "cm": "001",         // Clave del municipio
        "nm": "Aguascalientes", // Nombre del municipio
        "l": [               // Lista de localidades dentro del municipio
          {
            "c": "0001",     // Clave de la localidad
            "n": "Aguascalientes" // Nombre de la localidad
          },
          {
            "c": "0094",
            "n": "Granja Adelita"
          },
          {
            "c": "0096",
            "n": "Agua Azul"
          },
          {
            "c": "0100",
            "n": "Rancho Alegre"
          },
          {
            "c": "0102",
            "n": "Los Arbolitos [Rancho]"
          },
          {
            "c": "0104",
            "n": "Ardillas de Abajo (Las Ardillas)"
          }
        ]
      }
    ]
  }
]

