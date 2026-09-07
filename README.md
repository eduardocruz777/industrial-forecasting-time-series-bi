# 📈 Analytics Avançado: Previsão de Produção Industrial e Análise de Séries Temporais no Power BI

## 📌 Visão Geral do Projeto
Este projeto consiste no desenvolvimento de uma solução de **Advanced Analytics voltada para a camada de Planejamento e Controle de Produção (PCP)** [image_GDcA-k.png]. O objetivo principal foi estruturar uma análise profunda de séries temporais sobre o histórico produtivo de uma planta industrial, implementando cálculos de médias móveis para mapeamento de tendências, detecção automatizada de anomalias e projeções preditivas baseadas em Inteligência Artificial nativa com horizonte de 5 anos [0.1.101, image_GDcA-k.png].

Desafio avançado correspondente ao **Laboratório Prático 9** da formação de Business Intelligence da **Data Science Academy**.

---

## 💼 Fundamentos de Negócio e Engenharia Preditiva
O painel foi projetado para responder a demandas complexas de capacidade operacional e governança fabril, desdobrando-se em 3 frentes científicas [0.1.101, image_GDcA-k.png]:

1. **Monitoramento do Histórico de Produção (Média Móvel):** Engenharia de métricas lógicas para isolar a tendência real de longo prazo. O modelo capturou o pico de produtividade em 2020 (**Média de 0,47 Mi unidades**), mapeando a desaceleração estrutural subsequente até o fechamento de **0,21 Mi** em 2023 [image_GDcA-k.png].
2. **Diferenciação e Sazonalidade Multidimensional:** Distribuição volumétrica da capacidade operacional cruzando o fluxo temporal com o `Turno` de trabalho (Manhã/Tarde) e a segmentação sociodemográfica de `Faixa Etária` dos funcionários (de 16 anos a acima de 65 anos) através de gráficos de área empilhada [0.1.101, image_GDcA-k.png].
3. **Forecasting Automatizado via IA (Horizonte 2024 - 2028):** Implementação de algoritmos de suavização exponencial para prever o comportamento produtivo futuro da planta pelos próximos 5 anos. O visível gráfico projeta a estabilização da linha média central acompanhada da zona cinza de intervalo de confiança (margem de erro estatística) [image_GDcA-k.png].

---

## 🛠️ Tecnologias e Recursos Técnicos Utilizados
* **Microsoft Power BI:** Arquitetura dimensional, ferramentas de Analytics nativas e previsão de séries temporais [image_GDcA-k.png].
* **Power Query (ETL):** Carga e tratamento da base transacional industrial (`.csv`), normalização de strings de categorias e tipagem de colunas cronológicas.
* **Linguagem DAX Avançada:** Desenvolvimento de medidas explícitas para cálculo de médias móveis acumuladas, totalizações proporcionais e tratamento de contextos temporais dinâmicos.

---

## 📂 Organização dos Arquivos no Repositório
* `dados_producao_industrial.csv`: Base de dados transacional bruta contendo as datas de competência, turnos, idades e volumes de peças.
* `Lab9_Previsao_Series_Temporais.pbix`: Arquivo nativo do Power BI com o modelo relacional e os recursos de IA ativos [source: 12, image_GDcA-k.png].
* `README.md`: Documentação técnica, executiva e de negócios do projeto.

---

## 👤 Autor
* **Eduardo Cruz**
* LinkedIn: [eduardo-cruz777](https://linkedin.com)
* Email: edufracruz@gmail.com
<img width="899" height="503" alt="Lab4" src="https://github.com/user-attachments/assets/92e9f916-a4ff-40e9-a466-ccfa0d138ca8" />
<img width="878" height="478" alt="Lab3" src="https://github.com/user-attachments/assets/9a4fafb9-1dd9-43b4-a7e8-91a72912811b" />
<img width="757" height="442" alt="Lab2" src="https://github.com/user-attachments/assets/228eab71-42f7-4a73-b28f-8b8df4ec5b62" />
<img width="668" height="442" alt="Lab1" src="https://github.com/user-attachments/assets/ed845365-e88d-490f-b7c7-2d0cb57a5841" />
