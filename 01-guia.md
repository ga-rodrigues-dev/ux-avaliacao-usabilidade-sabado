# Guia de execução — Avaliação de Usabilidade (sábado)

> **Objetivo de hoje:** avaliar a usabilidade do protótipo com **dois métodos**. De manhã, **planejar** um Teste de Usabilidade (TU) para **duas tarefas** — sem executar o teste com usuários. Em seguida, **aplicar** a Avaliação Heurística (AH): cada pessoa inspeciona sozinha e o grupo consolida. Às **13h**, apresentar **15 minutos** destacando só os problemas mais relevantes.

> Confirme no **AVA/Moodle** os **dois conjuntos de slides** e o **roteiro oficial**. Se divergir deste guia, **prevalece o AVA**.

> **Fechado às 8h de hoje:** as **17 perguntas** dos slides 13–14 (métodos empíricos) vão **todas** para o slide; na fala, só 3–4. **Um conjunto** de respostas para as duas tarefas — não 17+17. A AH pode usar as **mesmas ou outras** duas tarefas. Cada pessoa: **no mínimo 5 problemas**, organizados **por problema** (não por heurística). Consolidação ≠ concatenar (isso é item de avaliação). Relógio sugerido: ~1h TU · ~1h AH individual · ~2h discussão + slides.

Página de trabalho: [02-modelos.md](./02-modelos.md)

## Dinâmica do dia

- **8h:** abertura (já ocorreu) → salas do grupo. Plantão da professora pelo grupo do chat. Conferir o documento de salas (nome, sobrenome, ano, e-mail).
- **~1h — Tarefa 1 (grupo):** planejar o TU. Responder as **17 perguntas dos slides 13 e 14** da aula de métodos empíricos. Começar definindo as duas tarefas.
- **AH em 3 momentos:** (1) grupo alinha tarefas (início/fim), personas e heurísticas; (2) **~1h individual** — no mínimo **5 problemas** por pessoa; (3) **~2h** de discussão + slides. Consolidação **não cabe em 20 min** e não cabe 2h no individual.
- **13h:** apresentações avaliativas, **15 minutos** por grupo. Gravadas; slides sobem no AVA. Sem prova tradicional — esta é parcela de nota.
- Só **duas tarefas** em cada método: profundidade, não largura. As da AH **podem ser as mesmas ou outras** das do TU.

## O que precisa ser entregue

- **As 17 respostas do planejamento** no slide (2–3 perguntas por slide). Na fala, **3 ou 4** escolhidas — medidas e parâmetros são as que ela citou como boas de mostrar.
- **Uma tabela de problemas por integrante** (AH), **no mínimo 5 linhas**, organizadas **por problema**. Depois da discussão, **não reescrever** a individual.
- **Uma tabela consolidada** do grupo (mesmas 4 colunas; deve ter **mais de 5** linhas). Concatenar as individuais **é item de avaliação negativo**.
- **Slides** com as 17 respostas + tabelas individuais + consolidada.
- **Upload no AVA** do deck.

Critérios recorrentes: **correção, completude e capricho**. Usar a terminologia da aula: *Teste de Usabilidade* (TU), *Avaliação Heurística* (AH), *heurística violada*, *severidade*, *tarefa na perspectiva do usuário*.

## Ponto de partida: o protótipo do grupo

A atividade **não parte do zero**. Inspecionar a **versão atual** da solução (protótipo da 2ª semana + ajustes de acessibilidade da 3ª).

**Sistema:** web/app de alimentação saudável e controle de peso para usuários leigos — registro de refeições (scanner/foto + busca por texto) e módulo de aprendizado tipo “Duolingo de nutrição”, com tom não-punitivo.

**Personas** (se colocar no lugar do usuário):

- **Marta**, 48 — rotina corrida; registro rápido; linguagem simples; sem culpa.
- **José**, 67 — diabetes; fonte grande, alto contraste, poucas opções; medo de apertar errado.
- **Larissa**, 23 — deficiência visual; TalkBack/NVDA; busca por texto; rótulos completos.

> **Tarefa ≠ funcionalidade.** *Logar* não é tarefa. Tarefa é o que a pessoa quer na vida; funcionalidade é do sistema. Tem que ser **navegável no protótipo que já existe**. Candidatas: **registrar uma refeição** e **consultar o cardápio / estudar nutrição**. O grupo decide. Na AH, as duas tarefas **podem ser as mesmas do TU ou outras**.

## Dois métodos, papéis diferentes

| Método | Tipo | O que o grupo faz hoje | Resultado esperado |
|---|---|---|---|
| **Teste de Usabilidade (TU)** | Empírico — observação de usuários | **Só o planejamento.** Não há tempo (nem usuários) para executar. | Plano executável: tarefas, medidas, parâmetros, roteiro, ética |
| **Avaliação Heurística (AH)** | Analítico — inspeção por especialistas | **Aplicar por inteiro:** individual → discussão → consolidação | Lista de problemas que **violaram heurísticas**, com severidade |

Usabilidade (ISO 9241-11) = **eficácia** + **eficiência** + **satisfação**. A responsabilidade é do design, não da pessoa. Os dois métodos **não exigem proposta de redesign** — o resultado é a **lista de problemas**. Se surgir uma ideia de correção na discussão, pode mostrar como bônus; não é o entregável.

---

## Planejar o Teste de Usabilidade

### O que é (e o que não é)

**TU** é nome de método formal — não é o termo genérico “testes com usuário”. Exige **medidas quantificáveis** e **parâmetros definidos antes** da coleta. Hoje o grupo **não observa usuários**; só responde as perguntas de planejamento.

Medidas citadas em aula: tempo da tarefa, número de erros, razão sucesso/erro, pedidos de ajuda, comentários favoráveis/desfavoráveis, tempo sem interação.

### Perguntas que o planejamento precisa responder

Fonte oficial: **slides 13 e 14**, **17 perguntas**, **um conjunto** para as duas tarefas. Medidas/parâmetros podem ter valores diferentes por tarefa.

1. **Objetivo** — avaliar a usabilidade da solução X para as tarefas Y, no perfil da persona Z.
2. **Duas tarefas** na perspectiva do usuário + personas/cenários associados.
3. **Quando e onde** o teste ocorreria (mesmo sendo hipotético).
4. **Duração** prevista por participante.
5. **Suporte computacional** — dispositivo, protótipo em papel/Figma/código, captura de tela, *eye-tracking*, fala, mapa de calor (só o que faria sentido).
6. **Estado inicial do sistema** — todo mundo começa do **mesmo ponto**. Se a tarefa é registrar refeição e o login não será testado, o roteiro diz: “considere que você já entrou; seu nome já aparece aqui”. Limpar cache/histórico para o 2º participante não herdar atalhos do 1º.
7. **Quem observa / quem modera** e **como recrutar** participantes (perfil: Marta? José? Larissa? usuários novos vs. experientes).
8. **Critério de início e de fim** — marco idêntico para todos. Ex.: “registrar refeição” **termina** quando a mensagem de confirmação aparece **e** a pessoa diz “terminei” — não basta clicar em salvar.
9. **O que o moderador pode (e não pode) fazer** — se estiver visível, a pessoa vai perguntar “é aqui que eu clico?”. Responder com pergunta: *“O que você acha que vai acontecer se clicar aí?”* Protocolo **Thinking Aloud** (pensar em voz alta).
10. **Dados a coletar e como analisar.**
11. **Parâmetros de sucesso** — definidos **antes** da coleta, a partir de um teste prévio curto da própria equipe. Ex.: tempo abaixo de X segundos, no máximo Y erros, nenhum comentário desfavorável. **Apresentar esses números.**
12. **Questionário de perfil?** **Entrevista depois?** Decidir com consciência de tempo (profundidade vs. largura).
13. **Roteiro de abertura** — texto **igual para todos**.
14. **Ética** — ver bloco abaixo.

(As demais das 17 estão nos slides 13–14 do AVA — responder **todas** no slide, mesmo as que não forem faladas.)

### Ética (entrar no plano, mesmo sem executar)

- Anonimizar: Usuário 1, Usuário 2 — nunca o nome.
- Consentimento por escrito; a pessoa pode **parar a qualquer momento**.
- Cuidado com dados sensíveis (senha real, dados de saúde).
- Deixar explícito: **avalia-se a solução, não a pessoa.**
- Pesquisa científica (Plataforma Brasil/CONEP): **não se paga** participante; só ressarcimento de despesa; protocolo aprovado **antes** da coleta.
- Produto de mercado: a empresa *pode* oferecer recompensa. Não misturar as duas lógicas no plano.

### Depois da execução (só para o plano saber o destino dos dados)

Na etapa real, a equipe confronta os dados com os **limites pré-estabelecidos** e gera lista de problemas com severidade: **cosmético** (atrasa, não impede) → **sério** (atrapalha de verdade) → **catastrófico** (não consegue terminar). Isso alimenta um ciclo de redesign — não precisa ser feito hoje.

---

## Aplicar a Avaliação Heurística

### O que é

**AH** (A e H maiúsculos) é inspeção da interface guiada pelas **10 heurísticas de Nielsen** (com Rolf Molich, década de 1990). Recomenda-se **3 a 5 avaliadores**; grupo de ~6 serve. O grupo usa o **protótipo executável** que já tem.

Um **problema** existe quando **uma ou mais** heurísticas são violadas. Citar **todas** as violadas naquela linha. **Não há hierarquia** entre as 10.

### Etapas de hoje

1. **Pré-avaliação (grupo):** uniformizar termos; decidir as **duas tarefas**; retomar personas, cenários e protótipo.
2. **Inspeção individual (~1h):** percorrer a **tarefa**, não a lista H1–H10. Em cada ação, passar o conjunto de perguntas. **No mínimo 5 problemas.** Uma linha = um problema. Modelos da internet que organizam “por heurística” estão **errados**.
3. **Discussão e consolidação (~2h com os slides):** agregar, reescrever, mudar severidade, acrescentar local ou **descartar**. Concatenar as individuais **é item de avaliação**.
4. **As individuais ficam como estavam** e **entram no slide**. Se um item “deixou de ser problema”, permanece na individual e some da consolidada. A consolidada deve ter **mais de 5** linhas.

### Formato da tabela (4 colunas)

| Descrição do problema | Local na interface | Heurística(s) violada(s) | Severidade |
|---|---|---|---|
| O que acontece e por que fere eficácia, eficiência ou satisfação | Tela, passo, componente (ex.: “2ª e 4ª tela do registro”) | Número (H1–H10); pode ser mais de uma | Escala combinada pelo grupo (**mínimo 3 níveis**), **igual para todos** |

**Escala sugerida por Nielsen:** cosmético/superficial → importante/grande → catastrófico (impede a tarefa). Ou a de 4 pontos: superficial · pequeno · grande · catastrófico. Três pontos já basta.

### As 10 heurísticas — perguntas-guia

Pergunta “não” ⇒ problema.

| # | Heurística | Pergunta enquanto inspeciona | Pista no projeto do grupo |
|---|---|---|---|
| **H1** | Visibilidade do status do sistema | A pessoa sabe o que está acontecendo, em que etapa está e o que falta, em tempo aceitável? | Registro em “uma tela só” sem “etapa 1 de 3” pode violar H1. Barra ao reconhecer foto; “refeição salva”. |
| **H2** | Correspondência com o mundo real | Termos, ícones e a **sequência** das ações batem com o modelo mental da persona? | Jargão nutricional vs. linguagem leiga de Marta/José. Ícones sem significado. |
| **H3** | Controle e liberdade do usuário | Só as ações **disponíveis agora** estão clicáveis? Dá para cancelar/desfazer? | Ação futura: **desabilitada e visível**, não sumida. José precisa de saída clara. |
| **H4** | Consistência e padronização | Mesma ação = mesmo termo, mesmo controle, mesma posição? | Botão primário que troca de lado; “salvar” vs. “confirmar” vs. “registrar”. |
| **H5** | Prevenção de erros | Máscaras, exemplos e confirmação **antes** de ação destrutiva? | “Deseja excluir esta refeição?” Falta de consistência (H4) costuma induzir erro (H5). |
| **H6** | Reconhecimento em vez de memorização | Dá para usar sem caderninho? A informação relevante está visível? | Metas e alimentos recentes à vista. Larissa não pode depender de memorizar o caminho. |
| **H7** | Flexibilidade e eficiência de uso | Há atalhos, dados recentes, personalização? | Foto/scanner para Marta; busca por texto para Larissa; “repetir ontem”. |
| **H8** | Design estético e minimalista | O que está na tela ajuda a tarefa? Excesso esconde o que importa? | **Esconder em acordeão não resolve.** Abas visíveis > conteúdo oculto. Minimalismo ≠ tela vazia. |
| **H9** | Reconhecer, diagnosticar e recuperar erros | A mensagem diz o que aconteceu, por quê e o que fazer? | Evitar “erro desconhecido”, “não foi possível cadastrar” sem causa. |
| **H10** | Ajuda e documentação | A ajuda existe **perto do uso**, pontual — e não substitui um design ruim? | Balãozinho eterno é sintoma de design fraco. |

**Breadcrumb vs. linha de progresso (H1):** breadcrumb = de onde veio e como voltar. *Progress line* = o que falta para terminar.

---

## Apresentação (13h, 15 minutos)

Deck sobe no AVA e fica gravado. Tudo documentado no slide; na fala, pinça:

1. **Contexto** — sistema, personas, as duas tarefas (e se a AH usou as mesmas ou outras).
2. **TU** — 3 ou 4 das 17 perguntas. **Medidas e parâmetros** são as que ela pediu para destacar.
3. **AH individual** — cada pessoa, **1 ou 2** problemas, já ligando à consolidação.
4. **Consolidada** — fechamento: o que o grupo priorizaria. Sem redesenhar a solução.
5. Individuais + consolidada + as 17 respostas **no slide**, mesmo o que não for falado.

## Checklist da manhã

### Abertura / AVA

- [ ] Abrir no AVA os dois conjuntos de slides e o roteiro oficial
- [ ] Ter o protótipo, personas e cenários abertos para o grupo inteiro

### Planejamento do TU

- [ ] Duas tarefas nomeadas na perspectiva do usuário (não “logar”)
- [ ] Objetivo, local/duração hipotéticos, material, recrutamento
- [ ] Estado inicial idêntico + critério de início/fim explícito
- [ ] Medidas + **parâmetros de sucesso com número**
- [ ] Roteiro de abertura padrão + *Thinking Aloud* + devolução de pergunta
- [ ] Ética (anonimato, consentimento, “não avaliamos você”)
- [ ] As 17 respostas no slide (um conjunto só)

### Avaliação Heurística

- [ ] Tarefas da AH definidas (mesmas do TU ou outras) — iguais para todo mundo *dentro da AH*
- [ ] Escala de severidade combinada (mín. 3 níveis)
- [ ] Cada pessoa: ≥5 problemas; tabela de 4 colunas, **por problema**
- [ ] Discussão: agrupar / descartar / reescrever — sem alterar as individuais
- [ ] Consolidada com mais de 5 linhas e distinta da cola das individuais

### Fechamento

- [ ] Slides pinçados (não a tabela inteira na fala)
- [ ] Individuais + consolidada + planejamento no AVA
