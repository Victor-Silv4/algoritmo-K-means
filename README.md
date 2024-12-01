# Projeto: Implementação e Análise do Algoritmo de K-Means com o Dataset Human Activity Recognition

## Objetivo do Projeto
Este projeto tem como objetivo aplicar o algoritmo de agrupamento K-Means para analisar dados de atividades humanas coletados por sensores. A análise busca identificar padrões intrínsecos nas atividades realizadas, com aplicações potenciais em monitoramento físico e sistemas de saúde inteligentes.

## Instruções para Executar o Código

1. **Configuração do Ambiente**:
   - Certifique-se de ter o Python instalado (recomendado: versão 3.8 ou superior).
   - Instale as dependências necessárias executando o comando `pip install -r requirements.txt`.

2. **Estrutura dos Dados**:
   - Os dados devem estar no formato `.txt` e seguir a estrutura do *UCI HAR Dataset*, incluindo os arquivos `X_train.txt`, `y_train.txt` e `subjects_train.txt`.

3. **Passos para Execução**:
   - Clone o repositório, acesse o diretório do projeto e execute o script principal com o comando `python main.py`.

4. **Saída**:
   - O script irá:
     1. Carregar e normalizar os dados.
     2. Aplicar o algoritmo K-Means.
     3. Gerar visualizações e análises dos clusters formados.

## Principais Conclusões e Considerações

- **Eficácia do K-Means**:
  - O K-Means demonstrou ser uma ferramenta eficaz para agrupar atividades humanas com base em dados de sensores. A normalização dos dados foi essencial para garantir a formação de clusters coesos.

- **Número de Clusters**:
  - O método do cotovelo indicou que 6 clusters representam adequadamente as atividades distintas presentes nos dados.

- **Limitações**:
  - O desempenho do K-Means depende de uma boa escolha de inicialização e normalização. Futuros trabalhos podem explorar alternativas, como o uso de algoritmos hierárquicos ou DBSCAN para validar os resultados.

- **Aplicações Potenciais**:
  - Este projeto pode ser expandido para aplicações reais, como dispositivos vestíveis para monitoramento de saúde ou análise de comportamento em tempo real.

## Referências
- ANGUITA, Davide; GHIO, et al. *A Public Domain Dataset for Human Activity Recognition Using Smartphones*. 2013. University of Genova; Universitat Politècnica de Catalunya- CETpD.

