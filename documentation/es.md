<!-- ELUCENIA technical documentation · peso-ideal-e-ajustado · es · no clinical/professional/rights approval -->

# Peso ideal y peso ajustado

[condiciones, fuentes y permisos](https://elucenia.org/es/herramientas/peso-ideal-e-ajustado)

## Cómo usar

Utilice la herramienta en el portal o abra index.html mediante un servidor HTTP local. Seleccione el idioma, complete los campos y calcule.

## Entradas y unidades

### Sexo

`sexo`

- `F` — Femenino
- `M` — Masculino

### Estatura

`altura`

cm · intervalo: 120–230

### Peso real (para el peso ajustado)

`peso`

kg · opcional · intervalo: 25–350

## Edición del método

Devine 1974/Robinson 1983/Miller 1983; revisión Pai–Paloucek 2000; factor local de peso ajustado 0,4

## Fórmula documentada

Peso ideal (Devine): hombres 50 kg + 2,3 kg por pulgada por encima de 5 pies; mujeres 45,5 kg + 2,3 kg por pulgada por encima de 5 pies. En centímetros: 50 (45,5) + 2,3 × (altura − 152,4) ÷ 2,54.

Peso ajustado = Peso ideal + 0,4 × (peso real − Peso ideal).

## Límites y población

El peso ideal es una estimación de tablas altura/peso, no una medición de masa magra. La relación farmacocinética varía según el medicamento; este resumen no confirma un factor ajustado universal de 0,4. La elección del peso para la dosis debe seguir la fuente del fármaco y la población correspondiente.

## Referencias

- [Pai MP, Paloucek FP. The origin of the "ideal" body weight equations. Ann Pharmacother, 2000.](https://doi.org/10.1345/aph.19381)

## Reproducir las pruebas técnicas

Ejecute node test.cjs en el directorio raíz de este repositorio para repetir los casos sintéticos registrados. Se conservan las entradas, los resultados esperados y las tolerancias originales. Las pruebas técnicas no constituyen validación clínica.

```sh
node test.cjs
```

tool.json contiene las fuentes, la edición y el alcance de la revisión. examples.json conserva las entradas y los resultados esperados de los casos sintéticos; results.json registra los resultados obtenidos.

[Ficha y referencias](../tool.json) · [Código JavaScript](../calculator.js) · [Casos de referencia](../examples.json) · [results.json](../results.json)

## Revisión y condiciones de uso

No se ha realizado una revisión clínica independiente.

Esta interfaz es una traducción de elaboración propia, no una edición oficial o certificada. No se han realizado la revisión clínica independiente, la revisión lingüística profesional ni la autorización de derechos de los instrumentos.

Resultado de la fórmula o clasificación. La interpretación, la conducta y la aplicabilidad dependen de la evaluación profesional y de la fuente seleccionada.

## Licencia y atribución

Apache-2.0 se aplica únicamente al código de ELUCENIA. Los derechos de los instrumentos, publicaciones, traducciones y datos permanecen en manos de sus respectivos titulares. Conserve LICENSE y NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Resultados documentados

La información siguiente conserva las salidas del método para ejemplos sintéticos. No constituye una validación clínica independiente.

### 1

Peso ideal según la fórmula de Devine


### 2

Peso real > 120% del ideal: para fármacos hidrofílicos y aminoglucósidos, use el peso ajustado

| Detalles del resultado | |
| --- | --- |
| Peso real en relación con el ideal | 160% |
| Peso ajustado (IBW + 0,4 × exceso) | 93,0 kg |


### 3

Peso ideal según la fórmula de Devine


### 4

Peso ideal según la fórmula de Devine

