O **Kanban** é um método visual de **gestão de fluxo de trabalho** que ajuda equipes a visualizar tarefas, identificar gargalos e otimizar processos.  

### 📜 Origem
- Criado na **Toyota** (década de 1940) para controle de produção.  
- Popularizado no **desenvolvimento de software** por **David J. Anderson**.  

### 💡 Princípios Fundamentais do Kanban
1. **Comece com o que você faz hoje**  
   → Adapta-se ao processo atual sem exigir grandes mudanças imediatas.  
2. **Acorde buscar melhorias incrementais**  
   → Melhorias contínuas e evolutivas.  
3. **Respeite papéis, responsabilidades e processos atuais**  
   → Evita resistência à mudança.  
4. **Incentive a liderança em todos os níveis**  
   → Todos são responsáveis pela melhoria.  

---

## 📋 2. Quadros Kanban e Visualização do Trabalho

A principal ferramenta do método Kanban é o **quadro Kanban**, que permite **visualizar o fluxo de trabalho**.

### 🧩 Estrutura típica de um quadro Kanban

| Etapa | Descrição |
|-------|------------|
| **Backlog** | Lista de tarefas pendentes, aguardando priorização. |
| **To Do (A Fazer)** | Itens prontos para serem iniciados. |
| **Doing (Em Progresso)** | Tarefas em execução pela equipe. |
| **Testing (Em Teste)** | Itens em validação ou revisão. |
| **Done (Concluído)** | Trabalho finalizado e entregue. |

### 📌 Exemplo visual:

| **Backlog** | **To Do** | **Doing** | **Testing** | **Done** |
|--------------|-----------|-----------|--------------|-----------|
| Task 1       | Task 3    | Task 4    | Task 6       | Task 7    |
| Task 2       |           | Task 5    |              |           |


### ⚙️ Benefícios da visualização
- Transparência total do processo  
- Comunicação mais eficiente  
- Identificação rápida de gargalos  

### 💻 Exemplo prático de uso
Uma equipe de desenvolvimento web usa o Trello com colunas “Backlog”, “Em Progresso” e “Concluído”.  
Durante a daily, o time analisa visualmente o quadro para identificar tarefas travadas e redistribuir esforços.

---

## ⚖️ 3. Limites de Trabalho em Progresso (WIP)

**WIP (Work In Progress)** define o **número máximo de tarefas** que podem estar em uma coluna ao mesmo tempo.

### 🎯 Objetivo do WIP
- Evitar sobrecarga;  
- Focar em **finalizar antes de começar algo novo**;  
- Melhorar a previsibilidade de entregas.  

### 📏 Exemplo:

| Etapa | Limite WIP | Status |
|-------|-------------|--------|
| Doing | 3 | ✅ Três tarefas em andamento — limite atingido |
| Testing | 2 | ⚠️ Duas tarefas — deve liberar uma antes de adicionar nova |

### 💻 Exemplo prático
Uma equipe de QA define **WIP = 2** para a coluna de testes.  
Isso evita que o time de desenvolvimento envie muitas tarefas simultâneas para QA, mantendo o fluxo equilibrado.

---

## 🔄 4. Fluxo e Melhoria Contínua

O **fluxo** representa o caminho que uma tarefa percorre até ser concluída.

### 🧭 Objetivo do fluxo
- Entregar valor continuamente;  
- Identificar gargalos e bloqueios.  

### 🔍 Métricas importantes

| Métrica | Descrição |
|----------|------------|
| **Lead Time** | Tempo total desde a criação até a entrega. |
| **Cycle Time** | Tempo de execução ativa (do “Doing” ao “Done”). |
| **Throughput** | Número de tarefas entregues em um período. |

### 🔁 Kaizen (改善)
Princípio japonês de **melhoria contínua** — pequenas mudanças frequentes levam à excelência.  

### 💻 Exemplo prático
Após medir o *cycle time*, o time percebe que o teste automatizado demora 3 dias.  
Eles decidem otimizar os scripts, reduzindo o tempo para 1 dia.

---

Fundamentos do Lean Thinking

O **Lean Thinking** (pensamento enxuto) visa **eliminar desperdícios** e **maximizar o valor entregue** ao cliente.

### 🏭 Origem
Baseado no **Toyota Production System (TPS)**, criado por **Taiichi Ohno**.

### 🧩 Princípios do Lean Thinking

1. **Definir valor** do ponto de vista do cliente.  
2. **Mapear o fluxo de valor**, separando atividades que agregam ou não valor.  
3. **Criar fluxo contínuo** de trabalho.  
4. **Estabelecer um sistema puxado** (trabalho começa conforme a demanda).  
5. **Buscar a perfeição** por meio da melhoria contínua.  

---

## 💻 1. Lean aplicado ao Desenvolvimento de Software

O **Lean Software Development (LSD)** adapta os princípios Lean para software.

### 🔑 Princípios do Lean Software Development (Poppendieck & Poppendieck)

| Princípio | Explicação |
|------------|------------|
| **Eliminar desperdícios** | Evitar retrabalho, código não usado e reuniões inúteis. |
| **Aprender rapidamente** | Obter feedback rápido com clientes e testes automatizados. |
| **Decidir o mais tarde possível** | Tomar decisões com base em informações concretas. |
| **Entregar o mais rápido possível** | Entregas incrementais e contínuas. |
| **Empoderar a equipe** | Dar autonomia e responsabilidade aos desenvolvedores. |
| **Construir qualidade** | Garantir qualidade desde o início (ex: TDD, CI). |
| **Otimizar o todo** | Focar na entrega de valor global do sistema. |

### 💻 Exemplo prático de Lean em software
Uma equipe utiliza **Integração Contínua (CI)** e **Entrega Contínua (CD)** para eliminar desperdícios e reduzir retrabalho.  
A cada commit, o código é testado e implantado automaticamente em ambiente de staging.

---

## 🧠 2. Discussão e Atividade Prática


Monte um **quadro Kanban digital** (Trello, Jira ou Miro):

Backlog | To Do | Doing (WIP=3) | Testing | Done

markdown
Copiar código

**Etapas:**
1. Adicione 8 tarefas relacionadas a um projeto (ex: site institucional).  
2. Simule o fluxo respeitando o WIP.  
3. Calcule o *lead time* e *cycle time* das tarefas.  
4. Reflita: houve gargalos? Onde o fluxo parou?  

---

## 🧩 8. Questões de Fixação e Respostas

### 📝 Parte 1 — Kanban

1. **Quais são os quatro princípios fundamentais do Kanban?**  
   **Resposta:**  
   - Comece com o que você faz hoje;  
   - Busque melhorias incrementais;  
   - Respeite papéis e responsabilidades atuais;  
   - Incentive a liderança em todos os níveis.  

2. **O que significa “visualizar o fluxo de trabalho”?**  
   **Resposta:** Representar visualmente as etapas do processo em um quadro Kanban, tornando visível o status das tarefas e gargalos.  

3. **Por que é importante definir limites de WIP?**  
   **Resposta:** Para evitar sobrecarga, manter o foco na conclusão de tarefas e equilibrar o fluxo de trabalho.  

4. **Qual a diferença entre lead time e cycle time?**  
   **Resposta:**  
   - *Lead time:* tempo total desde a criação até a entrega.  
   - *Cycle time:* tempo em que a tarefa está efetivamente em execução.  

5. **O que representa o conceito de Kaizen?**  
   **Resposta:** Princípio de melhoria contínua por meio de pequenas mudanças constantes.  

---

### 📝 Parte 2 — Lean Thinking

6. **Quais são os cinco princípios do pensamento Lean?**  
   **Resposta:**  
   1. Definir valor;  
   2. Mapear o fluxo de valor;  
   3. Criar fluxo contínuo;  
   4. Estabelecer sistema puxado;  
   5. Buscar a perfeição.  

7. **Cite três tipos de desperdícios comuns no desenvolvimento de software.**  
   **Resposta:**  
   - Reuniões desnecessárias;  
   - Código não utilizado;  
   - Retrabalho devido à falta de testes.  

8. **O que significa “decidir o mais tarde possível” no Lean Software Development?**  
   **Resposta:**  
   Significa adiar decisões até que haja informações suficientes para escolher a melhor alternativa, evitando retrabalho.  

9. **Como o Lean ajuda na melhoria contínua dos processos de software?**  
   **Resposta:**  
   Através da identificação e eliminação de desperdícios e da promoção de ciclos de feedback rápidos.  

10. **Dê um exemplo prático de aplicação de Lean em equipes ágeis.**  
    **Resposta:**  
    Usar *deploy contínuo* e *automação de testes* para reduzir desperdícios e acelerar entregas de valor ao cliente.  

---

## 🎓 Conclusão

Tanto **Kanban** quanto **Lean** compartilham o mesmo propósito:  
> **entregar valor de forma eficiente e contínua, reduzindo desperdícios e promovendo melhoria constante**.

Enquanto o Kanban oferece **métodos visuais e métricas**, o Lean fornece a **filosofia** e os **princípios** para tomada de decisão e cultura organizacional.

---
