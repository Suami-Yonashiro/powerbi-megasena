# 🎯 Dashboard de Análise da Mega-Sena com Power BI

Este projeto é um painel interativo criado no Power BI para explorar os resultados da Mega-Sena.
Utilizei dados públicos da Caixa Econômica Federal, permitindo ao usuário analisar diferentes concursos, histórico de sorteios, padrões estatísticos e obter insights relevantes. 
---

## 📊 Funcionalidades do Dashboard

- 🔢 **Mapa de calor das dezenas mais sorteadas**
- 📅 **Informações de atualização e maior prêmio já sorteado**
- 🔍 **Número de sorteios sem ganhadores**
- 💻 **Maior prêmio histórico**
- 🎛️ **Filtros dinâmicos por número do concurso, ano e dezenas**
- 🎯 **Verificação personalizada de combinações**: permite ao usuário inserir 6 dezenas e verificar se essa combinação já foi sorteada — com data e número do concurso.
- 🧮 **Quantidade de combinações de 6 dezenas sorteadas e quantas vezes ela se repetiu**
- 📌 **Sorteio por estado**
---

## 🛠️ Ferramentas utilizadas

- **Power BI Desktop**
- **Power Query** para ETL
- **DAX** para medidas analíticas (como verificação de combinação do usuário)
- **Fonte de dados**: Resultados oficiais da Mega-Sena (site da Caixa)
---

## 📁 Estrutura dos arquivos

| Arquivo | Descrição |
|--------|-----------|
| `202504_PRTF_Mega_R01.pbix` | Arquivo principal do Power BI |
| `d_megase.csv` | Base de dados com todos os resultados históricos |
| `README.md` | Descrição do projeto |
---

## 🧠 Principais insights

- As dezenas mais sorteadas historicamente até o momento
- Quais pares de dezenas aparecem com mais frequência
- Frequência por anos e comportamento ao longo do tempo
- Combinações já sorteadas e data do sorteio
- Número de sorteios sem ganhadores, ilustrando a proporção inversa
- Repetição das combinações de 6 dezenas sorteadas
- Estados com maior número de ganhadores
---

## 🖼️ Imagens do Dashboard

![Dashboard](imagem/dashboard-megasena.jpg)
---

## 📌 Autor

(https://www.linkedin.com/in/suami-yonashiro)
---

## 📥 Como baixar e usar

1. Faça o download do arquivo `.pbix` e .csv
2. Abra no Power BI Desktop
3. Clique em “Atualizar” para carregar os dados mais recentes
---

## 📜 Licença

Este projeto utiliza dados públicos e está disponível para fins educacionais.
