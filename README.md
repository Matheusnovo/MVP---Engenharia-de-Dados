# MVP---Engenharia-de-Dados
Aluno: Matheus Monteiro Novo de Assis

# Link do Notebook no Databricks: https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/1098376480540035/2451176262067821/8969848685121230/latest.html

## 🎯 Problema a ser resolvido

O objetivo deste MVP é analisar o desempenho dos times do **Campeonato Brasileiro da Série A** ao longo das temporadas de **2003 a 2022**, buscando entender fatores que influenciam os resultados das partidas e comportamentos recorrentes entre os times mais bem-sucedidos (campeões, classificados para a Libertadores) e os de pior desempenho (rebaixados).

A partir dessa análise, queremos extrair insights relevantes que ajudem a responder perguntas como:

- 📌 **O mando de campo ainda tem forte influência nos resultados?**
- 📌 **Os gols marcados tem forte influência nos resultados?**
- 📌 **Como foi o aproveitamento dos times com base no mando de campo e gols marcados/sofridos?**

---

### 📂 Dataset escolhido

Para começar, escolhi no Kaggle o dataset:

**Brazilian League Matches 2003–2022**  
🔗 [Link do dataset no Kaggle](https://www.kaggle.com/datasets/fabrciomacena/brazilian-league-matches-2003-2022)

Este dataset contém informações detalhadas de todas as partidas da Série A entre os anos de 2003 e 2022. Ele inclui:

- Nomes dos times
- Resultados dos jogos
- Datas das partidas
- Locais e estádios
## 📌 Conclusões Finais

Ao longo deste projeto, foi possível perceber como a **análise de dados no futebol** vai muito além de observar estatísticas isoladas. Os números contam histórias, revelam padrões e trazem insights, mas também mostram que o futebol é um esporte extremamente complexo, onde inúmeros fatores técnicos, táticos, emocionais e até ambientais influenciam diretamente o resultado de uma partida.

Durante a análise, ficou evidente que métricas como **gols marcados**, **gols sofridos** e **aproveitamento** não devem ser vistas de forma desassociada. Um exemplo interessante foi o caso do **Santos**, que mesmo figurando entre os cinco times que mais sofreram gols jogando em casa, também aparece entre os cinco com melhor aproveitamento como mandante. Esse aparente paradoxo mostra que, mesmo com uma defesa mais vulnerável, o clube conseguiu manter alta taxa de vitórias — possivelmente devido a um ataque eficiente ou desempenho pontual em jogos decisivos.

Esse tipo de observação só é possível graças à:

- ✅ Modelagem adequada dos dados  
- ✅ Construção de pipelines robustos de transformação e carga  
- ✅ Formulação de perguntas relevantes com base nos objetivos definidos no início do projeto

Utilizando a **plataforma Databricks**, conseguimos transformar uma base de dados bruta em uma estrutura analítica que nos permitiu explorar diferentes dimensões do jogo.

---

### 🔍 Novas Perguntas Levantadas

Mais do que responder às perguntas levantadas inicialmente, este projeto despertou novas curiosidades:

- ❓ Como se comportam os times fora de casa?  
- ❓ Há padrão de desempenho por década?  
- ❓ Times que marcam mais gols em casa também vencem fora?  
- ❓ Existe uma correlação entre tipo de estádio e desempenho?

Essas e muitas outras questões poderiam ser exploradas com o mesmo dataset ou com a inclusão de **novas fontes de dados** — como escalações, treinadores, presença de torcida, entre outros fatores.

---

### 🎓 Considerações Finais

Foi extremamente enriquecedor ver como os dados podem transformar algo tão emocional como o futebol em um campo fértil para **análise racional** e **tomada de decisões**. A combinação entre a **paixão pelo esporte** e o **poder da análise de dados** abre espaço para projetos ainda mais amplos e completos no futuro.
