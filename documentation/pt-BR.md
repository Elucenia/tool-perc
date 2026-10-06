<!-- ELUCENIA technical documentation · perc · pt-BR · no clinical/professional/rights approval -->

# Critérios PERC

[condições, fontes e permissões](https://elucenia.org/pt-br/ferramentas/perc)

## Como usar

Use a ferramenta no portal ou abra index.html em um servidor HTTP local. Selecione o idioma, preencha os campos e calcule.

## Entradas e unidades

### Idade ≥ 50 anos

`idade`

### FC ≥ 100 bpm

`fc`

### SatO₂ \< 95% em ar ambiente

`sat`

### Edema unilateral de membro inferior

`edema`

### Hemoptise

`hemoptise`

### Cirurgia ou trauma com internação nas últimas 4 semanas

`cirurgia`

### TVP ou TEP prévio

`tev`

### Uso de estrogênio (anticoncepcional ou reposição hormonal)

`hormonio`

## Edição do método

PERC/Kline 2004:8 critérios negativos em suspeita prévia baixa; sem decisão automática

## Fórmula documentada

Oito perguntas de sim/não. O PERC é negativo apenas quando todas são "não". Aplica-se só a quem o médico já considera de baixa probabilidade clínica (gestalt \< 15%).

## Limites e população

A PERC 2004 foi derivada em pacientes de emergência avaliados para embolia pulmonar e testada em grupos de risco baixo e muito baixo. Os oito critérios devem ser simultaneamente negativos, incluindo idade \< 50 anos, pulso \< 100/min e saturação \> 94% no estudo original. A regra não determina risco zero e sua aplicabilidade depende da seleção prévia da população; definições temporais e critérios de inclusão devem ser conferidos na versão usada.

## Referências

- [Kline JA et al. Clinical criteria to prevent unnecessary diagnostic testing in emergency department patients with suspected pulmonary embolism. J Thromb Haemost, 2004.](https://doi.org/10.1111/j.1538-7836.2004.00790.x)

- [Freund Y et al. Effect of the Pulmonary Embolism Rule-Out Criteria on subsequent thromboembolic events among low-risk emergency department patients: the PROPER randomized clinical trial. JAMA, 2018.](https://doi.org/10.1001/jama.2017.21904)

## Reproduzir os testes técnicos

Execute node test.cjs na pasta raiz deste repositório para repetir os casos sintéticos registrados. As entradas, expectativas e tolerâncias originais são preservadas. Testes técnicos não constituem validação clínica.

```sh
node test.cjs
```

tool.json contém fontes, edição e escopo de revisão. examples.json conserva as entradas e expectativas sintéticas; results.json registra os resultados obtidos.

[Ficha e referências](../tool.json) · [Código JavaScript](../calculator.js) · [Casos de referência](../examples.json) · [results.json](../results.json)

## Revisão e condições de uso

Revisão clínica independente não realizada.

Esta interface é uma tradução autoral, não uma edição oficial ou certificada. Revisão clínica independente, revisão linguística profissional e autorização de direitos de instrumentos não foram realizadas.

Resultado da fórmula ou classificação. Interpretação, conduta e aplicabilidade dependem da avaliação profissional e da fonte selecionada.

## Licença e atribuição

Apache-2.0 aplica-se somente ao código da ELUCENIA. Os instrumentos, publicações, traduções e dados mantêm os direitos dos respectivos titulares. Preserve LICENSE e NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Resultados documentados

As informações abaixo preservam as saídas do método para exemplos sintéticos. Não constituem validação clínica independente.

### 1

PERC negativo: TEP excluído sem D-dímero, se a probabilidade pré-teste for baixa (< 15%)

Nenhuma investigação adicional para TEP é necessária nesse contexto.


### 2

PERC positivo: não exclui TEP

Prossiga com D-dímero (ou com o algoritmo de Wells/Genebra).


### 3

PERC positivo: não exclui TEP

Prossiga com D-dímero (ou com o algoritmo de Wells/Genebra).

