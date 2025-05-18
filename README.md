# 🎯 Dashboard: Inteligência Analítica com Power BI. Mega-Sena.

Com a proposta de construir um portfólio fundamentado em dados e voltado à tomada de decisões estratégicas, este projeto foi pensado para unir **lógica, análise e visão de negócio em um único tema**.
A escolha da Mega-Sena foi pelo seu teor lúdico, que desperta curiosidade - mesmo entre quem está fora do contexto de dados - permitindo ilustrar com uma **base pública, como é possível identificar padrões, construir regras, adaptar soluções** e comunicar com clareza.

---

# 📊 Funcionalidades do Dashboard

- 🔢 **Mapa de calor das dezenas mais sorteadas**
- 📅 **Informações de atualização e maior prêmio já sorteado**
- 🔍 **Número de sorteios sem ganhadores**
- 💻 **Sorteio por estado**
- 🎛️ **Quantidade de combinações de 6 dezenas sorteadas e quantas vezes ela se repetiu**
- 🎯 **Verificação personalizada de combinações**: permite ao usuário inserir 6 dezenas e verificar se essa combinação já foi sorteada — com data e número do concurso.
---

# 🛠️ Ferramentas utilizadas

- **Power BI Desktop**
- **Power Query** para ETL
- **DAX** para medidas analíticas (como verificação de combinação do usuário)
- **Fonte de dados**: Resultados oficiais da Mega-Sena (site da Caixa)
---

# 📁 Estrutura dos arquivos

| Arquivo | Descrição |
|---------|-----------|
| `202504_PRTF_Mega_R01.pbix` | Arquivo principal do Power BI |
| `d_megase.csv` | Base de dados com todos os resultados históricos |
| `README.md` | Descrição do projeto |
---

# 🧠 Principais insights

- Dezenas mais sorteadas historicamente e sua frequência com o decorrer das atualizações. 
- Número de sorteios *sem* ganhadores, ilustrando a proporção inversa a quantidade de sorteios.
- Combinação de 6 dezenas sorteadas em relação a sua repetição, indicando um fator de aleatoriedade superficial.
- Concentração de premiação por estado.
- Escolha das dezenas de um concurso, na verificação do concurso e data do sorteio.
- Para cada aposta de 6 dezenas a chance é de 1 para 50.063.860.
---

# 🖼️ Imagens do Dashboard

![Dashboard](dashboard-megasena.jpg)
---

# 📌 Autor

(https://www.linkedin.com/in/suami-yonashiro)
---

# 📥 Como baixar e usar

1. Faça o download do arquivo `.pbix` e .csv
2. Abra no Power BI Desktop
3. Clique em “Atualizar” para carregar os dados mais recentes
---

# 📜 Licença

Este projeto utiliza dados públicos e está disponível para fins educacionais.
