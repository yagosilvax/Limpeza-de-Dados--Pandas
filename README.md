# Analise e Limpeza de Dados


Este projeto consiste no desenvolvimento de um pipeline de dados (ETL) utilizando **Python** e **Pandas** para extrair, tratar e analisar o histórico de vendas de uma cafeteria. O objetivo principal foi transformar dados brutos em uma base limpa e pronta para geração de inteligência de negócio.

## Escopo do Projeto:

O projeto foi estruturado para resolver problemas clássicos de engenharia e análise de dados:

1. **Extração:** Leitura dos dados brutos de vendas.
2. **Tratamento (Data Cleaning):** Limpeza de dados nulos, formatação de tipos, correção de strings e estruturação de caminhos dinâmicos.
3. **Carga:** Salvamento automatizado da base tratada em uma estrutura de pastas organizada (`/datasets/processados/`).
4. **Análise de Negócio:** Agrupamento e métricas de faturamento e volume de vendas.

## Tecnologias e Bibliotecas Utilizadas:

- **Linguagem:** Python 3.x
- **Biblioteca Principal:** `Pandas` (Manipulação e análise de dados)
- **Estrutura de Armazenamento:** Arquivos CSV

---

## Métricas e Insights Gerados:

Após a limpeza da base, o script realiza análises automatizadas para responder a perguntas de negócio essenciais:

* **Faturamento Total por Item:** Agrupamento financeiro para identificar quais produtos trazem maior receita para a cafeteria.
* **Volume de Itens Vendidos:** Identificação dos produtos mais populares em quantidade absoluta.

---

## Estrutura de Pastas e Configuração

Para rodar o projeto, é necessário replicar a estrutura de diretórios esperada pelo script Python:

```text
📂 Analise de Dados/
├── 📂 Script-python                 # Script principal de tratamento e análise
├── 📄 README.md                     # Documentação do projeto
└── 📂 datasets/
    └── 📂 processados/              # Pasta onde o Pandas salvará o arquivo tratado
```
