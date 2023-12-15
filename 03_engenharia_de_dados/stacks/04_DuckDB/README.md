><img src="https://duckdb.org/images/DuckDB-Footer.svg" alt="DuckDB" width="200"/>

# <h1 align='center'>[DuckDB](https://duckdb.org/)</h1>

-   > Obs: O __DuckDB__ é um sistema de gerenciamento de banco de dados __SQL OLAP__ (_Processamento Analítico Online_) em processo

## Por que DuckDB?

* Simples e portátil
    * Em processo, sem servidor sem dependências, compilação de arquivo único
    * APIs para Python, R, Java, Julia, Swift 
    * Funciona em Windows, Linux, macOS, OpenBSD
* Rico em recursos
    * Transações, persistência
    * Amplo suporte SQL 
    * __Consultas diretas em Parquet, CSV e JSON__
    * Junções, agregações, funções de janela

* Rápido
    * Otimizado para análises
    * Motor vetorizado e paralelo
    * Maior que o processamento de memória
    * Carregadores paralelos Parquet, CSV e NDJSON

* Gratuito e extensível
    * Gratuito e de código aberto
    * Licença Permissiva do MIT
    * Mecanismo de extensão flexível

* > Todos os benefícios de um banco de dados, sem complicações.

## Quando usar DuckDB 

- [x] ✔ Processamento e armazenamento de conjuntos de dados tabulares, por exemplo, de arquivos CSV ou Parquet
- [x] ✔Análise de dados interativa, por exemplo, juntar e agregar várias tabelas grandes
- [x] ✔Grandes alterações simultâneas em múltiplas tabelas grandes, por exemplo, acréscimo de linhas, adição/remoção/atualização de colunas
- [x] ✔Grande transferência de conjunto de resultados para o cliente

## Quando não usar DuckDB

- [ ] ❌ Casos de uso transacionais de alto volume (por exemplo, rastreamento de pedidos em uma loja virtual)
- [ ] ❌ Grandes instalações cliente/servidor para armazenamento centralizado de dados corporativos
- [ ] ❌ Gravando em um único banco de dados a partir de vários processos simultâneos
- [ ] ❌ Vários processos simultâneos lendo de um único banco de dados gravável

## Instalação

- > Vamos instalar o DuckDB e realizar este tutorial em um notebook`.ipynb` usando um ambiente interativo `Python` 

_Célula de instalação:_
```python
# Usamos o sinal de "!" (exclamação) antes do comando para indicar ao ambiente que é um comando bath
!pip install duckdb==0.9.2
```

* > As demais operações vamos realizar direto no ambiente do notebook aqui [notebook_duckdb.ipynb](./notebook_duckdb.ipynb)

* > Para este projeto vamos usar dados de futebol brasileiro do [kaggle](https://www.kaggle.com) 
    - [Campeonato Brasileiro de futebol](https://www.kaggle.com/datasets/adaoduque/campeonato-brasileiro-de-futebol/) arquivos já baixados e salvos no caminho [./Campeonato Brasileiro de futebol/](./Campeonato%20Brasileiro%20de%20futebol/)

## Contribuição

Se você tiver alguma sugestão ou quiser contribuir com materiais adicionais, sinta-se à vontade para abrir uma issue ou enviar um pull request neste repositório.

Divirta-se aprendendo!

## Autor

(Gustavo Lopes: [GitHub](https://github.com/Gustavo-H-Martins) | [LinkedIn](https://www.linkedin.com/in/gustavo-henrique-lopes-martins-361789192/))

![Gustavo Lopes](https://media.licdn.com/dms/image/D4D03AQHV5drm3wpahA/profile-displayphoto-shrink_100_100/0/1690910388427?e=1705536000&v=beta&t=aJWHFAWbByEHIyIBM1o6m3zfBB8arlyMEQIpP7ruRJk)

- Engenheiro de Dados com foco
  -
  - Big Data
  - Processamento Distribuído
  - Arquitetura e computação em nuvem
  - Performance e redução de custo
  - Repasse de conhecimento e democratização de acesso