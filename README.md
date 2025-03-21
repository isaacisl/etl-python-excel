# ETL de Dados de uma Empresa de Marketing para Dashboard

## Descrição
Este projeto implementa um processo ETL (Extract, Transform, Load) utilizando Python para processar dados de um arquivo Excel contendo informações sobre uma empresa de marketing. Os dados são extraídos, transformados conforme regras de negócio e carregados em um dashboard interativo para análise.

## Tecnologias Utilizadas
- Python 3.x
- Pandas
- OpenPyXL
- Requests (para extração de dados de APIs, se necessário)
- Streamlit (para criação do dashboard)
- Matplotlib e Plotly (para visualização de dados)


## Uso
1. Coloque o arquivo Excel com os dados da empresa de marketing no diretório `data/`.
2. Configure os parâmetros necessários em `main.py`.
3. Execute o script principal:
   ```bash
   python main.py
   ```
4. O arquivo Excel processado será salvo no diretório `data/`.
5. Para visualizar o dashboard, execute:
   ```bash
   streamlit run src/dashboard.py
   ```

## Funcionalidades
- Extração de dados de um arquivo Excel sobre uma empresa de marketing.
- Padronização e limpeza dos dados.
- Agregação e transformação conforme regras de negócio.
- Exporta os resultados processados para um novo arquivo Excel.
- Gera um dashboard interativo com Streamlit e visualizações em Matplotlib e Plotly.



