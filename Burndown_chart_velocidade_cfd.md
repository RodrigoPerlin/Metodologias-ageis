# 📘 Aula: Métricas Essenciais em Metodologias Ágeis  
### **Burndown Chart • Velocidade • CFD (Cumulative Flow Diagram)**

---

## 🎯 Objetivo da Aula
Ao final desta aula, você será capaz de:
- Compreender a finalidade e a interpretação de um **Burndown Chart**.
- Calcular e analisar a **Velocidade** de um time ágil.
- Entender e interpretar um **CFD – Cumulative Flow Diagram**, identificando gargalos.

---

# 🟦 1. Burndown Chart

## 📌 O que é?
Um **Burndown Chart** é um gráfico usado principalmente em Scrum para acompanhar o **progresso do trabalho ao longo do Sprint**.

Ele mostra:
- **Quantidade de trabalho restante** (eixo Y)
- **Dias do Sprint** (eixo X)

## 📈 Para que serve?
- Acompanhar a evolução do time durante o Sprint.
- Antecipar atrasos.
- Avaliar se o time vai entregar o planejado.

## 📊 Como funciona?
Exemplo: Sprint planejado com **40 pontos de história**.

| Dia | Pontos Restantes |
|-----|------------------|
| 1   | 40 |
| 2   | 35 |
| 3   | 33 |
| 4   | 25 |
| 5   | 18 |
| ... | ... |
| 10  | 0 |

## 🧠 Como interpretar
- **Linha real acima da linha ideal** → time mais lento (risco).
- **Linha real abaixo da linha ideal** → time mais rápido.
- **Linha horizontal** → nenhum trabalho concluído (alto risco).

---

# 🟩 2. Velocidade (Velocity)

## 📌 O que é?
A **Velocidade** é a quantidade de **story points concluídos** pelo time ao final de um Sprint.

## 💡 Para que serve?
- Previsões mais precisas sobre entregas futuras.
- Planejamento do Sprint com base na capacidade real.
- Histórico de desempenho.

## 📏 Como calcular?
> **Velocidade = Soma dos pontos concluídos no Sprint**

Exemplo:

| Sprint | Pontos Concluídos |
|--------|-------------------|
| 1 | 25 |
| 2 | 28 |
| 3 | 26 |

**Velocidade média = (25 + 28 + 26) / 3 = 26,3 pontos**

## 🧠 Interpretação correta
- Velocidade **não é meta**.
- Não serve para **comparar times**.
- O importante é a **consistência ao longo do tempo**.

---

# 🟧 3. CFD – Cumulative Flow Diagram

## 📌 O que é?
Um **Cumulative Flow Diagram (CFD)** é um gráfico utilizado em Kanban e Scrum para mostrar o **fluxo de trabalho ao longo do tempo**, com quantidade cumulativa de itens por estado.

Estados típicos:
- To Do  
- In Progress  
- Done  

## 📈 Como se lê?
O CFD é formado por camadas coloridas:

- Azul → To Do  
- Amarelo → In Progress  
- Verde → Done  

Cada camada **cresce de forma cumulativa**.

## 🧠 Por que é importante?
O CFD permite visualizar:
- Quantidade de trabalho em andamento (**WIP**)
- Tempo total das tarefas (**lead time**)
- Gargalos no processo
- Estabilidade e previsibilidade do fluxo

### Exemplos de interpretação:
- **In Progress aumentando demais** → gargalo, excesso de trabalho.
- **Camadas se afastando** → aumento do lead time.
- **Linhas paralelas** → fluxo estável e previsível.

---

# 🟪 4. Comparação Resumida

| Métrica | Foco | Usado em | O que mostra |
|--------|------|----------|--------------|
| **Burndown Chart** | Progresso no Sprint | Scrum | Se o Sprint será entregue |
| **Velocidade** | Capacidade do time | Scrum | Planejamento e previsibilidade |
| **CFD** | Fluxo contínuo | Kanban / Scrum | Gargalos e estabilidade do fluxo |

---

# 🟦 5. Exercícios Práticos

## ✔ Exercício 1 – Burndown
Sprint com 50 pontos.  
Pontos concluídos por dia:  
**5, 8, 6, 0, 10, 7, 8**  
→ Desenhe o Burndown.

---

## ✔ Exercício 2 – Velocidade
Sprints concluídos: **22, 25, 17**  
→ Calcule a velocidade média.

---

## ✔ Exercício 3 – CFD
Kanban com:
- 4 tarefas em To Do  
- 6 em In Progress  
- 2 em Done  

→ Onde está o gargalo?  
(Resposta: **In Progress está alto**, indicando excesso de WIP)

---

# 🟩 6. Conclusão
- O **Burndown** ajuda a prever o andamento e conclusão do Sprint.
- A **Velocidade** permite melhor planejamento e previsibilidade.
- O **CFD** é a métrica mais completa para analisar o fluxo e identificar gargalos.

Juntas, essas métricas oferecem uma visão poderosa para melhorar a entrega e a eficiência do time.

# 🟦 Bonus Tabela Fibonacci em Scrum  
### Estimativas de Tarefas com Story Points

---

# 📘 1. O que é a Tabela Fibonacci?

A **Tabela Fibonacci** é uma sequência numérica usada em Scrum para estimar o **tamanho relativo** das histórias de usuário.  
Ela é utilizada durante o **Planning Poker** ou **Sprint Planning**.

A sequência tradicional é:

**0, 1, 2, 3, 5, 8, 13, 21, 34, 55, 89…**

Em Scrum, normalmente usamos apenas:

**1, 2, 3, 5, 8, 13, 21, 34**

(às vezes inclui-se **0**, **½**, **∞** ou **?** para sinalizar incertezas)

---

# 🟩 2. Por que usar Fibonacci?

A sequência Fibonacci tem **crescimento não linear**, o que ajuda os times a:

- 📌 **Evitar a falsa precisão** (ex: 6 ou 7 pontos não fazem diferença prática)  
- 📌 **Visualizar aumento exponencial de complexidade**  
- 📌 **Refletir incerteza maior conforme o tamanho cresce**  
- 📌 **Tomar decisões mais rápidas e com menos debate**  
- 📌 **Estimativas mais realistas** quando as tarefas ficam grandes demais

Quanto maior o número, maior a:
- complexidade  
- incerteza  
- quantidade de trabalho  
- risco  

Por isso a escala cresce rapidamente.

---

# 🟧 3. Como funciona dentro do Scrum?

## ✔ Usada na estimativa de **Story Points**
Durante o **Planning Poker**, cada membro do time escolhe um número da sequência Fibonacci para estimar:

> **Quanto esforço a história exige?**

O número representa:
- complexidade  
- esforço  
- risco  
- volume de trabalho  
- incerteza  

## ✔ Quando usar?
Durante:
- **Refinamento do backlog (Backlog Refinement)**  
- **Sprint Planning**  

---

# 🟪 4. Exemplo de interpretação dos pontos

| Fibonacci | Significado Relativo |
|----------|-----------------------|
| **1** | Muito simples, tarefa pequena |
| **2** | Simples, baixa complexidade |
| **3** | Moderada, requer atenção |
| **5** | Complexidade média |
| **8** | Complexa, exige várias etapas |
| **13** | Muito complexa, alto risco |
| **21+** | Enorme, precisa ser quebrada |

---

# 🟦 5. Por que não usar números lineares?

Exemplo: 1, 2, 3, 4, 5…

Isso induz o time a discutir:

- "É 4 ou 5?"
- "Talvez seja 6… mas não existe 6"
- "E se for 7?"

Isso gera:
- atraso  
- debates desnecessários  
- falsa sensação de precisão  

A escala Fibonacci força a decisão entre classes mais amplas:

**É pequeno (5) ou muito maior (8)?**

Isso agiliza o processo.

---

# 🟨 6. Sinalizadores especiais da escala

Times podem usar:

| Sinal | Significado |
|-------|-------------|
| **0** | História já concluída / sem esforço |
| **½** | Muito simples (quase nenhum esforço) |
| **?** | Não sei o suficiente para estimar |
| **∞** | Inestimável; precisa dividir |

Esses valores ajudam a manter a clareza no processo.

---

# 🟩 7. Exemplos Práticos

### Exemplo 1 — Feature Simples  
Criar botão com ação definida  
→ Estimativa: **2 pontos**

### Exemplo 2 — Tela completa com API  
Implementar tela, validações, API e testes  
→ Estimativa: **8 pontos**

### Exemplo 3 — Migração grande  
Mover módulo inteiro para nova arquitetura  
→ Estimativa: **13 ou 21 pontos** (deve ser quebrado)

---

# 🟧 8. Relação com Velocidade

A equipe estima usando Fibonacci.  
E a **velocidade média do time** define quantos pontos cabem no Sprint.

Exemplo:
- Time entrega 28 pontos por Sprint  
- No próximo sprint podem ser planejados ~28 (±20%) pontos

Por isso estimar bem é essencial.

---

# 🟫 9. Conclusão

A **Tabela Fibonacci** é usada em Scrum porque:

- Traz **simplicidade**
- Evita **discussões longas**
- Ajuda o time a pensar em **complexidade relativa**, não horas
- Cria um **ritmo natural de estimativa**
- Facilita prever capacidade e planejar Sprints

Ela é uma das ferramentas mais importantes para manter o processo ágil realmente **ágil**.

---

# 📌 10. Dica Bônus

Se você quiser, posso gerar:
- uma **versão com gráficos**,  
- **cartas de Planning Poker**,  
- ou uma **tabela pronta para equipe usar no Daily/PBIs**.

