# ghost-regresion-resemble

## Pre-requisitos para usar

- NodeJS

## Instalación

Clone este repositorio en la misma ruta donde tiene el repositorio de cypress

```bash
 npm install
```

## Ejecución

ejecute el comando para hacer la comparacion de las imagenes entre las dos versiones de ghost bajo pruebas

```bash
 npm start
```

## Al finalizar usted obtendra

- Directorio con las diferencias halladas por ResembleJS para cada Scenario y paso.
  - Este podrá encontrarlo con el nombre `compared-images`
- Reporte generado para mostar las diferencias de cada Scenario.
  - El archivo se llama `report.html` y se recomienda usar un servidor tipo [http-server](https://www.npmjs.com/package/http-server) para su visualización 

Se dejan imagenes y reporte precargados para una preinspeccion.
