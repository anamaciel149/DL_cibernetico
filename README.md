# Projeto — Deep Learning em Segurança Cibernética

Arquivo principal: `DL_Ciberseguranca_UNSW_NB15.ipynb`

## Tema
Detecção de intrusões em tráfego de rede usando uma Deep Neural Network.

## Base
UNSW-NB15, obtida do Kaggle pelo pacote `kagglehub`:
`mrwellsdavid/unsw-nb15`

## Como usar no Google Colab
1. Faça upload do `.ipynb` no Google Colab.
2. Execute as células na ordem.
3. O notebook instala `kagglehub` e baixa automaticamente a base.
4. Aguarde o treinamento da rede.
5. Use as métricas e gráficos produzidos para preencher a apresentação.

## Saídas principais
- distribuição das classes;
- arquitetura da rede;
- curvas de treinamento;
- limiar otimizado na validação;
- accuracy;
- precision;
- recall;
- F1-score;
- ROC-AUC;
- matriz de confusão;
- curva ROC;
- curva Precision-Recall.

## Observação
O código remove `attack_cat` das variáveis de entrada no problema binário para evitar vazamento de informação.
