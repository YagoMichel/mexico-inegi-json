# 🌎 Catálogo México INEGI – JSON Abreviado

¡Hola! 👋 Soy Yago, y este proyecto nace de la necesidad de tener un **JSON práctico y accesible** con todos los estados, municipios y localidades de México, basado en los datos del INEGI.

La idea es que cualquier desarrollador, estudiante o curioso pueda **consultar, usar y desplegar esta información fácilmente** en sus proyectos web, apps o sistemas de datos, sin complicaciones.

## ¿Qué hay en este repositorio?

- **`mexico_inegi.json`**: El JSON completo con todos los estados, municipios y localidades.
- **`LICENSE`**: Licencia MIT para que cualquiera pueda usar y adaptar el proyecto.
- **`README.md`**: Sí, este archivo que estás leyendo 😄

El JSON tiene esta estructura:

```json
{
  "clave_estado": "01",
  "nombre_estado": "Aguascalientes",
  "municipios": [
    {
      "clave_municipio": "001",
      "nombre_municipio": "Aguascalientes",
      "localidades": [
        {
          "clave_localidad": "0001",
          "nombre_localidad": "Aguascalientes"
        },
        {
          "clave_localidad": "0094",
          "nombre_localidad": "Granja Adelita"
        }
      ]
    }
  ]
}
