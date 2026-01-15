# Projeto ETL – Santander Dev Week 2023

## 📌 Descrição do Projeto
Este projeto foi desenvolvido como parte do desafio da Santander Dev Week 2023 e tem como objetivo demonstrar, na prática, o fluxo de ETL (Extract, Transform, Load) utilizando Python.

O foco do projeto é mostrar como os dados podem ser extraídos de uma fonte, transformados conforme regras de negócio e carregados em um novo destino para uso posterior.

---

## 🛠 Tecnologias Utilizadas
- Python
- Pandas
- Google Colab

---

## 🔄 Fluxo ETL

### Extract (Extração)
Os dados dos clientes são extraídos a partir de um arquivo CSV contendo informações básicas, como nome, conta e cartão.

### Transform (Transformação)
Durante a etapa de transformação, é gerada uma mensagem personalizada para cada cliente, destacando a importância dos investimentos como estratégia de planejamento financeiro.

### Load (Carregamento)
Após a transformação, os dados são salvos em um novo arquivo CSV, contendo tanto as informações originais quanto a mensagem personalizada.

---

## 📂 Estrutura do Projeto

- `clientes.csv`  
  Arquivo CSV com os dados de entrada dos clientes.

- `clientes_com_mensagem.csv`  
  Arquivo CSV gerado após a etapa de transformação, contendo as mensagens personalizadas.

- `etl_santander_dev_week.ipynb`  
  Notebook com a implementação do pipeline ETL.

---

## ▶️ Como Executar o Projeto
1. Abra o notebook `etl_santander_dev_week.ipynb` no Google Colab.
2. Faça o upload do arquivo `clientes.csv`.
3. Execute as células sequencialmente para realizar o processo de ETL.
4. O arquivo `clientes_com_mensagem.csv` será gerado ao final da execução.
