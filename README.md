 # API Testing | Swagger PetStore

Proyecto de pruebas funcionales sobre APIs REST utilizando Postman y Newman.

El objetivo fue validar el correcto funcionamiento de los endpoints de Swagger PetStore mediante pruebas positivas, negativas y de rendimiento. 
Swagger https://petstore.swagger.io/#/

## Features

- API Testing
- Validación de Status Code
- Validación de Response Body
- Variables de entorno
- Automatización con datos dinámicos: Dado las limitaciones de la version gratuita de postman, solo se podrá visualizar los pasos para realizar automatizaciones con datos de entrada multiples para una mayor cobertura en los casos de prueba y el archivo con los datos a utilizar en la sección "Automatizacion" -> "Pasos-de-automatizacion" -> "Datos-de-entrada-multiples.json"
- Reportes con Newman
- Pruebas de Performance
- "InformePetStoreCollection.docx" es una evalucion y analisis de los resultados obtenidos. 

## Tecnologías

- Postman

- Newman

- Swagger

## Módulos

### User

- Alta

- Consulta

- Actualización

- Eliminación

### Login

- Casos positivos

- Casos negativos

- Performance

## Setup

Importar la Collection en Postman.

Importar el Environment.

Ejecutar la colección.

Para ejecutar mediante Newman:

```bash
newman run PetStore.postman_collection.json
```
Link de la collection para visualizar en postman:
https://go.postman.co/collection/54356312-d5fed90d-fe15-4f5a-bf9c-fbf7dfdb1a69?source=collection_link
