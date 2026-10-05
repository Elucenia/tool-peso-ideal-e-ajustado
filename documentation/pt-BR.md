<!-- ELUCENIA technical documentation · peso-ideal-e-ajustado · pt-BR · no clinical/professional/rights approval -->

# Peso ideal e peso ajustado

[condições, fontes e permissões](https://elucenia.org/pt-br/ferramentas/peso-ideal-e-ajustado)

## Como usar

Use a ferramenta no portal ou abra index.html em um servidor HTTP local. Selecione o idioma, preencha os campos e calcule.

## Entradas e unidades

### Sexo

`sexo`

- `F` — Feminino
- `M` — Masculino

### Altura

`altura`

cm · intervalo: 120–230

### Peso real (para o peso ajustado)

`peso`

kg · opcional · intervalo: 25–350

## Edição do método

Devine 1974/Robinson 1983/Miller 1983; revisão Pai Paloucek 2000; pesoajustado fatorlocal 0,4

## Fórmula documentada

Peso ideal (Devine): homens 50 kg + 2,3 kg por polegada acima de 5 pés; mulheres 45,5 kg + 2,3 kg por polegada acima de 5 pés. Em centímetros: 50 (ou 45,5) + 2,3 × (altura − 152,4) ÷ 2,54.

Peso ajustado = peso ideal + 0,4 × (peso real − peso ideal).

## Limites e população

Peso ideal é uma estimativa de tabelas altura/peso e não é medida de massa magra. A relação farmacocinética varia por medicamento; não existe confirmação neste resumo de fator ajustado universal 0,4. A escolha do peso para dose deve seguir a fonte do fármaco e a população correspondente.

## Referências

- [Pai MP, Paloucek FP. The origin of the "ideal" body weight equations. Ann Pharmacother, 2000.](https://doi.org/10.1345/aph.19381)

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
