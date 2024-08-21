# Análise de Dados CAGED com Python e BigQuery - Comparação do Mercado de Trabalho com os Cursos Oferecidos pelo SENAC/RN

## Visão Geral

Este projeto independente de Business Intelligence (BI) visa analisar o mercado de trabalho do Rio Grande do Norte (RN) em 2023 utilizando dados do CAGED e compará-lo com os cursos oferecidos pelo SENAC/RN. O objetivo é identificar como a oferta educacional do SENAC/RN se alinha com as demandas do mercado de trabalho local, destacando oportunidades e lacunas que podem orientar decisões estratégicas.

## Objetivos do Projeto

- **Analisar os dados do CAGED** para entender as tendências do mercado de trabalho no RN em 2023.
- **Comparar os dados do mercado de trabalho** com os cursos oferecidos pelo SENAC/RN, identificando áreas de convergência e divergência.
- **Gerar insights acionáveis** que possam auxiliar no alinhamento da oferta educacional com as necessidades do mercado.

## Estrutura do Projeto

- **`Codigo.ipynb`**: Jupyter Notebook contendo todo o código para coleta, análise, e visualização dos dados. 
  - **Pacotes e Bibliotecas**: O projeto utiliza bibliotecas como `pandas`, `numpy`, `seaborn`, `matplotlib`, `plotly`, `requests`, `BeautifulSoup`, e `google.cloud` para manipulação de dados, visualização e interações com BigQuery.
  - **Coleta de Dados**: Extração de dados do site do SENAC/RN via web scraping e dos dados do CAGED.
  - **Análise e Comparação**: Processamento dos dados para comparar as tendências do mercado de trabalho com os cursos disponíveis.
  - **Visualizações**: Criação de gráficos e dashboards para apresentar os insights de forma interativa e compreensível.

- **`Dados_CAGED`**: Pasta contendo os layouts e descrições dos dados do CAGED utilizados no projeto.

## Ferramentas e Tecnologias Utilizadas

- **Python**: Para manipulação de dados, análise e visualização.
- **BigQuery**: Para execução de consultas SQL em grandes volumes de dados.
- **Pandas e Numpy**: Para manipulação e processamento dos dados.
- **Matplotlib, Seaborn e Plotly**: Para criação de gráficos e visualizações interativas.
- **BeautifulSoup e Requests**: Para web scraping e extração de dados diretamente do site do SENAC/RN.

## Como Utilizar

1. Clone este repositório:
   ```bash
   git clone https://github.com/HanrsMullerDSA/Projeto_Senac.git
2. Instale as dependências necessárias:
   ```bash
   pip install -r requirements.txt
3. Abra o Jupyter Notebook `Codigo.ipynb` para explorar o código e executar a análise.

## Resultados

Os principais insights incluem:
- Áreas onde os cursos do SENAC/RN estão alinhados com as demandas do mercado de trabalho do RN.
- Setores onde há oportunidades de desenvolvimento de novos cursos para atender lacunas do mercado.

## Conclusão

Este projeto demonstra como a análise de dados e BI podem ser utilizados para alinhar a oferta educacional com as necessidades reais do mercado de trabalho, fornecendo uma base sólida para decisões estratégicas no setor de educação profissional.

## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues e pull requests para melhorias ou novas funcionalidades.

## Licença

Este projeto está sob a licença [MIT](LICENSE). Consulte o arquivo [LICENSE](LICENSE) para mais detalhes.
