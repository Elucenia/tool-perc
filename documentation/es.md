<!-- ELUCENIA technical documentation · perc · es · no clinical/professional/rights approval -->

# Criterios PERC

[condiciones, fuentes y permisos](https://elucenia.org/es/herramientas/perc)

## Cómo usar

Utilice la herramienta en el portal o abra index.html mediante un servidor HTTP local. Seleccione el idioma, complete los campos y calcule.

## Entradas y unidades

### Edad ≥ 50 años

`idade`

### Frecuencia cardíaca ≥ 100 bpm

`fc`

### Saturación de O₂ \< 95% en aire ambiente

`sat`

### Edema unilateral de miembro inferior

`edema`

### Hemoptisis

`hemoptise`

### Cirugía o traumatismo con hospitalización en las últimas 4 semanas

`cirurgia`

### TVP o EP previa

`tev`

### Uso de estrógenos (anticoncepción o terapia hormonal sustitutiva)

`hormonio`

## Edición del método

PERC/Kline 2004: 8 criterios negativos con sospecha previa baja; sin decisión automática

## Fórmula documentada

Ocho preguntas sí/no. PERC es negativo solo si todas son “no”. Aplicar solo si el médico ya considera baja probabilidad clínica (gestalt \< 15%).

## Límites y población

La PERC 2004 se derivó en pacientes de urgencias evaluados por embolia pulmonar y se probó en grupos de riesgo bajo y muy bajo. Los ocho criterios deben ser negativos simultáneamente, incluidos edad \< 50 años, pulso \< 100/min y saturación \> 94% en el estudio original. La regla no establece un riesgo nulo y su aplicabilidad depende de la selección previa de la población; las definiciones temporales y los criterios de inclusión deben comprobarse en la versión utilizada.

## Referencias

- [Kline JA et al. Clinical criteria to prevent unnecessary diagnostic testing in emergency department patients with suspected pulmonary embolism. J Thromb Haemost, 2004.](https://doi.org/10.1111/j.1538-7836.2004.00790.x)

- [Freund Y et al. Effect of the Pulmonary Embolism Rule-Out Criteria on subsequent thromboembolic events among low-risk emergency department patients: the PROPER randomized clinical trial. JAMA, 2018.](https://doi.org/10.1001/jama.2017.21904)

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
