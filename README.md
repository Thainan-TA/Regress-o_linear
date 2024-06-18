# Regressão Linear com o Dataset de Boston do Scikit-Learn

Este projeto demonstra como aplicar regressão linear usando o dataset de Boston disponível na biblioteca Scikit-Learn. O objetivo é prever o valor mediano das casas em diferentes bairros de Boston com base em várias características.

## Pré-requisitos

- Python 3.6 ou superior
- Bibliotecas Python:
  - scikit-learn
  - pandas
  - numpy
  - matplotlib

Você pode instalar essas bibliotecas usando o pip:

```bash
pip install scikit-learn pandas numpy matplotlib
```

## Descrição do Dataset

O dataset de Boston contém informações coletadas pelo Serviço de Censos dos EUA sobre casas em Boston. Ele possui 506 amostras e 13 variáveis preditoras. As variáveis são:

* CRIM - Taxa de criminalidade per capita
* ZN - Proporção de terrenos residenciais zonados para lotes acima de 25.000 pés quadrados
* INDUS - Proporção de hectares comerciais não varejistas por cidade
* CHAS - Variável fictícia Charles River (1 se o trecho limita o rio; 0 caso contrário)
* NOX - Concentração de óxidos nítricos (partes por 10 milhões)
* RM - Número médio de quartos por residência
* AGE - Proporção de unidades ocupadas pelos proprietários construídas antes de 1940
* DIS - Distâncias ponderadas até cinco centros de emprego de Boston
* RAD - Índice de acessibilidade às rodovias radiais
* TAX - Taxa de imposto sobre a propriedade de valor total por $10.000
* PTRATIO - Proporção aluno-professor por cidade
* B - 1000(Bk - 0.63)^2 onde Bk é a proporção de negros por cidade
* LSTAT - Porcentagem de status baixo da população

  
**A variável alvo (target) é MEDV (Valor Mediano das Casas em $1000)**

## Conclusão
Este projeto demonstra como utilizar a regressão linear para prever o valor mediano das casas em Boston com base em várias características. Através do uso de Scikit-Learn, foi possível treinar, avaliar e visualizar o modelo de forma eficiente.

## Referências
[Scikit-Learn Documentation](https://scikit-learn.org/stable/index.html)

[Dataset de Boston](https://mirahari.github.io/boston/)
