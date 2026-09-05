# AH individual — Gabriel

**Tarefas:** as mesmas do TU (registrar refeição + estudar nutrição).  
**Persona na inspeção:** José (T1) e Marta (T2) — ou só José nas duas, se preferir.  
**Escala (aula analítica, slide 19):** 1 cosmético · 2 pequeno · 3 grande · 4 catástrofe.  
**Numeração das heurísticas:** a do PDF da aula analítica (não a ordem “clássica” da web).

| H | Nome na aula |
|---|---|
| 1 | Visibilidade do estado do sistema |
| 2 | Correspondência entre o sistema e o mundo real |
| 3 | Controle e liberdade do usuário |
| 4 | Consistência e padronização |
| 5 | Prevenção de erros |
| 6 | Ajuda para reconhecer, diagnosticar e recuperar de erros |
| 7 | Reconhecimento ao invés de memorização |
| 8 | Flexibilidade e eficiência de uso |
| 9 | Design estético e minimalista |
| 10 | Ajuda e documentação |

**Como usei isto:** percorri as duas tarefas no protótipo (código + telas). Confirme clicando uma vez em cada fluxo abaixo. Se algum item não bater com o que você viu, apague a linha — não invente.

**Percurso rápido (10 min)**

1. Home → Registrar refeição → Escanear → Permitir câmera → use **Simular leitura OK** só para avançar (é o stub do protótipo; **não** anote isso como problema) → em Confirmar, mude a **porção** (ex. 1 pote → ½ pote) e olhe as kcal → Confirmar registro.  
2. Home → Registrar refeição → Buscar por texto → digite `xyz` → veja “0 resultado(s)”.  
3. Home → Estudar nutrição → olhe a trilha (“feito” / “agora”) → Começar lição → erre uma → acerte → no meio, toque **Voltar**.

---

## Tabela (colar no slide “AH — Gabriel”)

| # | Problema | Local | Heurística violada | Severidade |
|---|---|---|---|---|
| 1 | Trocar a **porção** não muda kcal nem macros; só a **quantidade** altera os números. O texto diz que os valores valem “para a quantidade e porção escolhidas”, mas a porção é ignorada. O usuário pode confirmar um registro errado. | Confirmar refeição | H1 (estado mente); também H5 | 3 grande |
| 2 | **Quantidade** e **porção** aparecem juntas, sem unidade nem frase que ligue as duas (ex. “2 × ½ pote”). O usuário tem de adivinhar se a quantidade é “quantos desta porção”. | Confirmar refeição | H2; também H7 | 2 pequeno |
| 3 | Depois de **Refeição registrada** não há desfazer, editar ou apagar o registro. Um toque errado em Confirmar fica gravado. | Pronto! (sucesso da refeição) | H3 | 3 grande |
| 4 | Busca que não acha nada mostra só “0 resultado(s)”. Não descreve o que falhou nem oferece saída (outro termo, scanner, digitar código). | Buscar por texto | H6 | 2 pequeno |
| 5 | Na trilha, o primeiro marco já aparece **feito** e o segundo **agora**, sem o usuário ter feito a lição. O estado da missão é falso. | Estudar nutrição (trilha) | H1 | 2 pequeno |
| 6 | **Voltar** no meio da lição sai para a trilha e **zera** as respostas, sem pedir confirmação. | Lição (botão Voltar) | H3; também H5 | 3 grande |
| 7 | As alternativas da lição prometem comparação visual, mas não há imagem: o texto de *alt* vira uma segunda linha (“Banana e maçã sobre a mesa”). Ruído e expectativa quebrada. | Lição (alternativas) | H2; também H9 | 2 pequeno |

Mínimo da professora: 5. Estas 7 cobrem as **duas** tarefas. Não reescreva depois da discussão do grupo.

**Pinça para a fala (1 problema):** o #1 (porção não atualiza as kcal) — é fácil de mostrar ao vivo e liga H1 com dado nutricional, que é o coração da Tarefa 1.

---

## O que NÃO colocar (para não se enrolar)

- Botão de **conta** desabilitado — o grupo assumiu que o app teria login.  
- Botões **Simular leitura OK / falha**, lanterna falsa, permissão de câmera “de mentira”: **stub do protótipo**, não heurística. Avaliar o fluxo *como se* a leitura tivesse funcionado.  
- Solução redesenhada (“eu faria um modal…”). Só o problema.  
- Uma linha por heurística. Uma linha = um problema.
