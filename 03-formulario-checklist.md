# Formulário / checklist — trabalho de sábado

Fonte das decisões: [slides do grupo](https://docs.google.com/presentation/d/1cbikm95pDQn9qG7Zja0pKOheoJcsYl1l/edit).  
Guia: [01-guia.md](./01-guia.md) · Modelos: [02-modelos.md](./02-modelos.md)  
**Folha do Gabriel (AH individual):** [04-gabriel-ah-individual.md](./04-gabriel-ah-individual.md)

**Como usar:** itens com ✅ já estão fechados. Campos `___` ainda faltam no grupo.

---

## 0. Acordos (atualizado 5/set, manhã)

| # | Pergunta | Decisão |
|---|---|---|
| 1 | A AH usa as mesmas duas tarefas do TU? | ✅ **Sim, as mesmas** |
| 2 | Escala de severidade da AH | ⚠️ **Ainda não combinada.** Recomendação (PDF da aula analítica, slide 19): **1 cosmético · 2 pequeno · 3 grande · 4 catástrofe.** Os slides do TU usam 3 níveis (cosmético / sério / catastrófico) — isso vale para classificar problemas **depois** de um teste com usuário, não é a escala oficial da AH. |
| 3 | Nº de participantes do TU | ✅ **7 pessoas.** Critério 80% → **pelo menos 6 de 7** concluem sem falha (não 4 de 5, nem 7 de 8). |
| 4 | Estado inicial / login | ✅ **Manter o texto do slide** (“conta já logada”). Assumir que o app **teria** tela de login. Não avaliar o botão de conta desabilitado como problema. |

Mensagem pronta para o grupo (escala):

> Pessoal, na AH individual vou usar a escala de **4 níveis da aula analítica**: 1 cosmético, 2 pequeno, 3 grande, 4 catástrofe. Se alguém já estiver usando a de 3 do TU, avisem agora.

---

## 1. Relógio (agora → 13h)

- [x] Tarefas da AH = as do TU
- [ ] **Você agora:** tabela individual ≥5 (folha do Gabriel)
- [ ] Corrigir no slide do TU: **7** participantes e sucesso **6/7**
- [ ] Grupo: 30 s para travar a escala de 4
- [ ] Consolidada (não concatenar)
- [ ] Pinça da fala + deck no AVA

Hora de parar o individual e voltar ao grupo: `___:___`

---

## 2. Já decidido — Teste de Usabilidade (não reabrir)

### Situação

| Item | Decisão |
|---|---|
| Objetivo | Avaliar se usuários fazem as tarefas principais de forma intuitiva, eficiente e com pouca ajuda; achar dificuldades e melhorias |
| Onde / quando | **Presencial**, ambiente tranquilo, sessão isolada, no período agendado |
| Duração | **20–30 min** (abertura + 2 tarefas + entrevista) |
| Dispositivo | Tablet ou smartphone com o protótipo + internet |
| Estado inicial | Tela inicial aberta; **conta já logada** (assumir login); cache limpo entre pessoas; alimentos e ≥1 lição disponíveis |
| Papéis | **Moderador** + **Observador** |
| Quem testa | Colegas / família / conhecidos; preferência: usuários novos |
| Quantos | **7** |
| Questionário de perfil | Sim, 3–5 min |
| Entrevista depois | Sim, 2–3 min, 7 perguntas |

### As duas tarefas (TU e AH)

**Tarefa 1 — Registrar refeição**  
*“Você acabou de consumir um alimento e deseja registrá-lo no aplicativo. Utilize o código de barras ou busca por texto para localizar o alimento e registre-o como parte da sua refeição.”*

**Tarefa 2 — Estudar nutrição**  
*“Você deseja aprender mais sobre alimentação saudável. Acesse a área de aprendizado e conclua uma das lições disponíveis.”*

### Fim da tarefa / falha

| | Sucesso | Falha |
|---|---|---|
| T1 | Alimento achar (código **ou** texto) + registrado + mensagem de confirmação + “terminei” | Desiste, 2 min parado, ou moderador faz no lugar |
| T2 | Lição inteira + atividade concluída + mensagem tipo “parabéns” + “terminei” | Idem |

### Medidas e parâmetros (falar na apresentação)

| Medida | Tarefa 1 | Tarefa 2 |
|---|---|---|
| Tempo-alvo | ≤ 2 min | ≤ 3 min |
| Erros máximos | 1 | 2 |
| Pedidos de ajuda máximos | 1 | 1 |
| Conclusão | **80% = 6 de 7** sem falha | idem |
| Ajuda | A maioria **não** pede | idem |
| Erro crítico | Nenhum que impeça terminar | idem |

- [ ] Corrigir no deck: 7 pessoas e 6/7
- [x] **Medidas e parâmetros** entram na fala (a professora pediu)

---

## 3. Avaliação Heurística

**Roteiro oficial:** planejamento do TU (já nos slides) + AH **completa** (individuais ≥5 + consolidada).  
**Fases da aula:** alinhar no grupo → **inspeção sozinho, duas passagens** → discussão → relatório (problema, local, heurística, severidade).

**Numeração = PDF da aula analítica** (H6 é *erro*, não *reconhecimento*):

| H | Nome | Pergunta da aula |
|---|---|---|
| 1 | Visibilidade do estado do sistema | O sistema informa o progresso a tempo? |
| 2 | Correspondência com o mundo real | Linguagem familiar, ordem natural? |
| 3 | Controle e liberdade | Dá para fazer o que quer, desfazer, sair? |
| 4 | Consistência e padronização | Mesmo elemento, mesmo efeito? |
| 5 | Prevenção de erros | Dá para errar menos *antes* de confirmar? |
| 6 | Reconhecer, diagnosticar e recuperar erros | Mensagem clara, sem código, com próximo passo? |
| 7 | Reconhecimento ao invés de memorização | Está visível ou preciso lembrar de outra tela? |
| 8 | Flexibilidade e eficiência | Há atalho / caminho eficiente? |
| 9 | Design estético e minimalista | Informação irrelevante esconde o que importa? |
| 10 | Ajuda e documentação | Ajuda fácil de achar e focada na tarefa? |

### 3.1 Antes de se separar

- [x] Tarefas = T1 + T2 do TU
- [ ] Escala = 4 níveis (confirmar no grupo)
- [ ] Persona (pode ser as duas, ou uma por tarefa)

| Pessoa | Persona T1 | Persona T2 |
|---|---|---|
| Beatriz | | |
| Daniel | | |
| **Gabriel** | José | Marta |
| Jhonatan | | |
| Levy | | |
| Renan | | |
| Yasmin | | |

### 3.2 Individuais

- [ ] Beatriz ≥5
- [ ] Daniel ≥5
- [x] **Gabriel ≥5** — ver [04-gabriel-ah-individual.md](./04-gabriel-ah-individual.md)
- [ ] Jhonatan ≥5
- [ ] Levy ≥5
- [ ] Renan ≥5
- [ ] Yasmin ≥5

### 3.3 Consolidada

Discussão obrigatória. Pode reescrever, mudar severidade, juntar, **tirar**. Concatenar = nota ruim. **Mais de 5** linhas. Individuais **não** se apagam.

---

## 4. Apresentação 13h / 15 min

| Min | Bloco | Quem |
|---|---|---|
| ~2 | Sistema + personas + as 2 tarefas (AH = iguais) | ___ |
| ~4 | TU: 3–4 perguntas, **parâmetros com número** (7 pessoas, 6/7) | ___ |
| ~7 | Cada um: 1–2 problemas da individual, ligando à consolidada | todos |
| ~2 | Fechamento da consolidada. Sem redesenhar. | ___ |

**Pinça do Gabriel:** porção não atualiza kcal (H1, sev. 3).

---

## 5. Entrega

- [ ] 17 respostas do TU no slide (corrigir 7 / 6 de 7)
- [ ] 7 tabelas individuais (≥5 linhas)
- [ ] 1 consolidada (>5 linhas, discutida)
- [ ] Pinça da fala
- [ ] Upload AVA
