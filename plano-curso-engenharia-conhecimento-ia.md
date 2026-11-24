# Plano de Curso â€” Engenharia de Conhecimento da IA (v2)

> Formato **ARCKHÉ AI** Â· 6 trilhas (1 por camada da PirÃ¢mide da InteligÃªncia Aplicada) Â· **muito conteÃºdo, muita prÃ¡tica, muitos exemplos** Â· eixo dedicado a **quem estÃ¡ entrando tarde** Â· motor de **marketing viral** embutido Â· **Prova da PirÃ¢mide** no final, com correÃ§Ã£o instantÃ¢nea e badge compartilhÃ¡vel.

---

## 0. Posicionamento e nomes

**Nome do framework (autoridade):** Engenharia de Conhecimento da IA â€” PirÃ¢mide da InteligÃªncia Aplicada.

**Nome de venda (o que para o scroll):**

> **A PirÃ¢mide da IA â€” vocÃª nÃ£o precisa de 100 prompts. Precisa de 6 camadas.**

Sub-promessas alternativas para testes A/B:
- "Entrou tarde na IA? A pirÃ¢mide que transforma atraso em vantagem."
- "Pare de colecionar prompts. Comece a construir inteligÃªncia."
- "Do zero ao sistema que aprende com vocÃª â€” em 6 camadas."

**Posicionamento contra o mercado:** todo curso de IA em PT-BR vende lista de prompts. Este vende **estrutura** â€” e ataca de frente a barreira emocional ("jÃ¡ estou atrasado") que nenhum concorrente toca.

| # | Camada | Trilha | Cor | Frase-Ã¢ncora | Caso-Ã¢ncora exclusivo |
|---|--------|--------|-----|--------------|----------------------|
| 1 | **Prompt** | T1 | Emerald ðŸŸ¢ | "Prompt Ã© a pergunta." | O e-mail difÃ­cil: mesmo pedido, 4 versÃµes, 4 resultados |
| 2 | **IntenÃ§Ã£o** | T2 | Blue ðŸ”µ | "IntenÃ§Ã£o Ã© o destino." | O post que vendeu zero: prompt perfeito, alvo errado |
| 3 | **Contexto** | T3 | Purple ðŸŸ£ | "Contexto Ã© o mapa." | A campanha genÃ©rica: a IA nÃ£o era fraca, estava cega |
| 4 | **Aproveitamento** | T4 | Amber ðŸŸ¡ | "Aproveitamento Ã© o mÃ©todo." | O acerto que se perdeu: ninguÃ©m anotou por que funcionou |
| 5 | **Arquitetura** | T5 | Teal ðŸŸ¦ | "Arquitetura Ã© o sistema." | O gargalo invisÃ­vel: 10 prompts bons, processo quebrado |
| 6 | **EvoluÃ§Ã£o** | T6 | Rose ðŸŒ¹ | "EvoluÃ§Ã£o Ã© o aprendizado acumulado." | O vÃ­deo que bombou (e o canal que nÃ£o aprendeu nada com ele) |

> **Regra anti-repetiÃ§Ã£o:** cada trilha abre com seu caso-Ã¢ncora â€” uma situaÃ§Ã£o onde **sÃ³ aquela camada** resolve. O aluno nunca sente "isso Ã© igual Ã  trilha anterior". O caso abre o index da trilha e Ã© retomado nos mÃ³dulos.

---

## 1. O eixo "Quem entra tarde" (diferencial do curso)

Atravessa TODAS as trilhas. Quatro mecanismos:

1. **DiagnÃ³stico de nÃ­vel** (landing + inÃ­cio de cada trilha): 6 perguntas â†’ "seu ponto real na pirÃ¢mide Ã© a camada X". Combate o erro do relatÃ³rio Â§10 (entrar no meio sem fundamento). **Ã‰ tambÃ©m o motor viral** â€” ver Â§11.
2. **Box "Atalho do retardatÃ¡rio"** em cada mÃ³dulo: versÃ£o mÃ­nima viÃ¡vel da camada, 1 template pronto + 1 exercÃ­cio de 10 min.
3. **MÃ³dulo 1.0 Base Zero** pra quem nunca usou IA â€” inclui **verificaÃ§Ã£o** (usar sem se queimar).
4. **Box "Na sua profissÃ£o"** em cada trilha: o caso traduzido pra 5 perfis â€” **professor, advogado, vendedor, gestor, autÃ´nomo/criador**. RequalificaÃ§Ã£o = mercado de trabalho; o aluno se vÃª no exemplo.

Mantra: **"VocÃª nÃ£o estÃ¡ atrasado. VocÃª estÃ¡ comeÃ§ando pela base â€” que Ã© exatamente onde se deve comeÃ§ar."**

---

## 2. Estrutura geral

```
engenharia-conhecimento-ia/
â”œâ”€â”€ index.html                      # Landing: pirÃ¢mide interativa + diagnÃ³stico viral + 6 trilhas
â””â”€â”€ curso/
    â”œâ”€â”€ trilha1/  (Prompt â€” Emerald)        modulo-1-0, 1-1, 1-2
    â”œâ”€â”€ trilha2/  (IntenÃ§Ã£o â€” Blue)          modulo-2-1, 2-2
    â”œâ”€â”€ trilha3/  (Contexto â€” Purple)        modulo-3-1, 3-2
    â”œâ”€â”€ trilha4/  (Aproveitamento â€” Amber)   modulo-4-1, 4-2
    â”œâ”€â”€ trilha5/  (Arquitetura â€” Teal)       modulo-5-1, 5-2
    â”œâ”€â”€ trilha6/  (EvoluÃ§Ã£o â€” Rose)          modulo-6-1, 6-2
    â””â”€â”€ prova/
        â””â”€â”€ index.html              # Prova da PirÃ¢mide: 12 questÃµes + gabarito comentado + badge
```

PadrÃ£o por mÃ³dulo: **6â€“8 tÃ³picos**, 500â€“800 linhas, â‰¥1 SVG futurista, variedade de componentes (grids âœ“/âœ—, timeline, tip boxes, prompt boxes), **â‰¥3 exemplos prÃ¡ticos copy-paste por mÃ³dulo**, **entregÃ¡vel** ao final.

Total: **13 mÃ³dulos + prova final**. Carga: ~12â€“15h.

---

## 3. Trilha 1 â€” Engenharia de Prompt (Emerald) ðŸŸ¢

**Caso-Ã¢ncora:** *O e-mail difÃ­cil.* VocÃª precisa responder um cliente insatisfeito. Mesmo pedido em 4 versÃµes â€” do "responde esse cliente" ao prompt completo com papel, tom, formato e exemplo. As 4 respostas lado a lado. O aluno VÃŠ a diferenÃ§a antes de aprender a teoria.
**Pergunta-guia:** *Como pedir melhor?*

### MÃ³dulo 1.0 â€” Base Zero (pra quem entra agora)
1. O que Ã© IA generativa, em 1 frase honesta (sem hype)
2. Modelo, prompt, resposta, janela de contexto â€” vocabulÃ¡rio mÃ­nimo
3. Como abrir e conversar (ChatGPT / Claude / Gemini â€” onde clicar)
4. Os 3 mitos do retardatÃ¡rio ("Ã© tarde", "Ã© sÃ³ pra programador", "vai me substituir")
5. Primeira conversa guiada (copie, cole, veja acontecer)
6. **VerificaÃ§Ã£o: use sem se queimar** â€” o que Ã© alucinaÃ§Ã£o, os 3 cheques antes de usar qualquer resposta (fonte? data? faz sentido?), quando a IA inventa com confianÃ§a
7. O que a IA NÃƒO faz bem (e por que saber isso te protege)

**PrÃ¡tica:** primeira conversa funcional + caÃ§ar 1 alucinaÃ§Ã£o de propÃ³sito ("me dÃª 5 fatos sobre [tema que vocÃª domina]" e conferir).
**EntregÃ¡vel:** print do antes/depois + checklist de verificaÃ§Ã£o preenchido.

### MÃ³dulo 1.1 â€” Anatomia de um bom prompt
1. As 5 partes: Papel Â· Tarefa Â· Contexto Â· Formato Â· Exemplo
2. Pedido fraco Ã— forte (grid âœ“/âœ— â€” exemplos do relatÃ³rio Â§3 + caso do e-mail)
3. Definir formato de saÃ­da (lista, tabela, passo a passo)
4. Pedir o nÃ­vel certo de explicaÃ§Ã£o (crianÃ§a / leigo / especialista)
5. Pedir exemplos e comparaÃ§Ãµes de propÃ³sito
6. Erros que matam o prompt: genÃ©rico, ambÃ­guo, sem formato
7. IteraÃ§Ã£o: melhorar a resposta sem recomeÃ§ar do zero

**PrÃ¡tica:** o mesmo prompt em 3 nÃ­veis de explicaÃ§Ã£o; consertar 5 prompts quebrados (exercÃ­cio com gabarito).
**EntregÃ¡vel:** 3 prompts ruins seus transformados em fortes (ficha).

### MÃ³dulo 1.2 â€” Prompts reutilizÃ¡veis
1. Por que reescrever sempre Ã© desperdÃ­cio
2. Anatomia de template com variÃ¡veis `[ ]`
3. **10 templates prontos**: resumo, e-mail, explicaÃ§Ã£o, brainstorm, revisÃ£o, comparaÃ§Ã£o, plano de aula, proposta comercial, post, anÃ¡lise de documento
4. Onde guardar (doc, notas, biblioteca pessoal)
5. Nomear e versionar
6. **Atalho do retardatÃ¡rio:** os 3 templates que resolvem 80% do dia
7. **Na sua profissÃ£o:** o template-chave de cada perfil (professor: plano de aula Â· advogado: anÃ¡lise de clÃ¡usula Â· vendedor: follow-up Â· gestor: resumo de reuniÃ£o Â· criador: roteiro)

**EntregÃ¡vel:** **biblioteca pessoal de 5+ prompts** nomeados, salva.

> **Kit T1** â€” Template universal:
> ```
> VocÃª Ã© [PAPEL]. Sua tarefa Ã© [TAREFA].
> Contexto: [O QUE A IA PRECISA SABER].
> Formato: [LISTA/TABELA/PASSOS]. RestriÃ§Ãµes: [O QUE EVITAR].
> Exemplo do que quero: [1 EXEMPLO].
> Antes de responder, diga o que assumiu.
> ```

---

## 4. Trilha 2 â€” Engenharia de IntenÃ§Ã£o (Blue) ðŸ”µ

**Caso-Ã¢ncora:** *O post que vendeu zero.* Prompt tecnicamente perfeito, texto bonito â€” e nenhuma venda. O prompt pedia "um texto sobre o produto"; a intenÃ§Ã£o real era "fazer o leitor agendar uma conversa". A IA acertou a tarefa e errou o destino. SÃ³ intenÃ§Ã£o resolve isso â€” prompt melhor nÃ£o resolveria.
**Pergunta-guia:** *Para que estou pedindo isso?*

### MÃ³dulo 2.1 â€” Tarefa Ã— IntenÃ§Ã£o
1. A diferenÃ§a entre o que peÃ§o e o que quero alcanÃ§ar
2. As 6 perguntas da intenÃ§Ã£o: objetivo, transformaÃ§Ã£o, decisÃ£o, pÃºblico, efeito, motivo
3. Dissecando o caso: o mesmo post com 3 intenÃ§Ãµes diferentes (informar / vender / autoridade) â€” 3 textos completamente distintos
4. O custo de responder bem pro alvo errado
5. Como declarar intenÃ§Ã£o dentro do prompt
6. Quando a intenÃ§Ã£o muda a resposta inteira (3 estudos rÃ¡pidos)
7. Checklist de intenÃ§Ã£o antes de apertar enter

**PrÃ¡tica:** pegar 1 texto que vocÃª jÃ¡ pediu pra IA e regerar com 2 intenÃ§Ãµes opostas; comparar.
**EntregÃ¡vel:** pedido real reescrito declarando pÃºblico + objetivo + efeito.

### MÃ³dulo 2.2 â€” IntenÃ§Ã£o aplicada a resultado
1. IntenÃ§Ã£o em conteÃºdo (o que o vÃ­deo/post deve CAUSAR)
2. IntenÃ§Ã£o em vendas (a decisÃ£o que o leitor precisa tomar)
3. IntenÃ§Ã£o em decisÃ£o/gestÃ£o (que escolha isso destrava)
4. IntenÃ§Ã£o em atendimento (resolver, nÃ£o sÃ³ responder)
5. Alinhar tom e linguagem Ã  intenÃ§Ã£o
6. **Atalho do retardatÃ¡rio:** a frase de 1 linha "meu objetivo real aqui Ã© ___"
7. **Na sua profissÃ£o:** professor (a aula deve fazer o aluno conseguir o quÃª?) Â· advogado (o parecer sustenta qual decisÃ£o?) Â· vendedor (qual o prÃ³ximo passo do lead?) Â· gestor (qual decisÃ£o a anÃ¡lise habilita?) Â· criador (o que o pÃºblico faz apÃ³s assistir?)

**EntregÃ¡vel:** **carta de intenÃ§Ã£o** reutilizÃ¡vel do seu trabalho.

> **Kit T2** â€” Bloco de intenÃ§Ã£o (cola antes do prompt):
> ```
> Objetivo final: [...]. PÃºblico: [...]. Efeito/decisÃ£o que quero gerar: [...].
> Se precisar escolher, priorize: [clareza | persuasÃ£o | precisÃ£o | velocidade].
> ```

---

## 5. Trilha 3 â€” Engenharia de Contexto (Purple) ðŸŸ£

**Caso-Ã¢ncora:** *A campanha genÃ©rica.* "Crie uma campanha pro meu projeto" â†’ resultado que serviria pra qualquer empresa do planeta. A IA nÃ£o era fraca: estava **cega**. Mesmo prompt + pasta de contexto (pÃºblico, exemplos que funcionaram, tom da marca, limites) â†’ campanha que parece feita por quem trabalha lÃ¡ hÃ¡ anos. Nem prompt nem intenÃ§Ã£o resolvem cegueira â€” sÃ³ contexto.
**Pergunta-guia:** *O que a IA precisa saber pra entender melhor?*

### MÃ³dulo 3.1 â€” O que Ã© contexto (alÃ©m do prompt)
1. Contexto = mapa: respostas ruins quase sempre sÃ£o contexto pobre
2. Os tipos: arquivos, imagens, docs, histÃ³rico, exemplos bons/ruins, regras, marca, pÃºblico, restriÃ§Ãµes
3. Anexar arquivos e referÃªncias (como cada ferramenta lida)
4. Exemplos positivos e negativos como contexto ("assim sim, assim nÃ£o")
5. Identidade de marca/voz como contexto reutilizÃ¡vel
6. Quando contexto demais atrapalha (ruÃ­do Ã— sinal)
7. **Privacidade e dados: o que NUNCA colar na IA** â€” dados de clientes, senhas, contratos confidenciais, dados de saÃºde; como anonimizar antes de usar ([NOME], [EMPRESA]); o que cada ferramenta faz com seus dados; a regra de ouro: "colaria isso num grupo pÃºblico?"

**PrÃ¡tica:** anonimizar um documento real e usÃ¡-lo como contexto; comparar resposta com e sem a pasta de contexto.
**EntregÃ¡vel:** **pasta de contexto** do seu projeto + checklist de privacidade.

### MÃ³dulo 3.2 â€” Engenharia de contexto na prÃ¡tica
1. O "briefing permanente": doc que vocÃª cola/reanexa sempre
2. Estrutura de pastas que a IA entende
3. Transformar histÃ³rico de conversas em contexto reaproveitÃ¡vel
4. DossiÃª de pÃºblico-alvo (1 pÃ¡gina que melhora tudo)
5. RestriÃ§Ãµes e regras internas como guarda-corpo
6. **Atalho do retardatÃ¡rio:** o mini-briefing de 5 linhas
7. **Na sua profissÃ£o:** professor (perfil da turma + currÃ­culo) Â· advogado (modelos da banca + jurisprudÃªncia usual) Â· vendedor (ICP + objeÃ§Ãµes frequentes) Â· gestor (metas + restriÃ§Ãµes do trimestre) Â· criador (nicho + 3 posts que performaram)

**EntregÃ¡vel:** **briefing-base do projeto** pronto pra reanexar.

> **Kit T3** â€” Briefing-base:
> ```
> # Projeto: [nome]
> Quem somos / voz: [...] Â· PÃºblico: [...]
> Exemplos bons: [...] Â· Exemplos a evitar: [...]
> Regras/limites: [...] Â· Resultado esperado: [...]
> âš  Dados sensÃ­veis: anonimizados (checklist ok)
> ```

---

## 6. Trilha 4 â€” Engenharia de Aproveitamento (Amber) ðŸŸ¡

**Caso-Ã¢ncora:** *O acerto que se perdeu.* Um post performou 10Ã— a mÃ©dia. TrÃªs meses depois, ninguÃ©m lembra qual era a estrutura, o prompt, o gancho. O conhecimento existiu â€” e evaporou. Prompt, intenÃ§Ã£o e contexto estavam certos; faltou **registrar e transformar em mÃ©todo**.
**Pergunta-guia:** *O que deu certo e pode virar mÃ©todo?*

### MÃ³dulo 4.1 â€” Da tentativa ao padrÃ£o
1. Por que conhecimento nÃ£o registrado se perde (o caso, dissecado)
2. O que registrar: prompts que funcionaram, respostas boas, erros recorrentes
3. Achar a estrutura por trÃ¡s do acerto (Dorâ†’ExplicaÃ§Ã£oâ†’Exemploâ†’BenefÃ­cioâ†’CTA, relatÃ³rio Â§6)
4. Acerto â†’ template Â· erro â†’ ajuste Â· repetiÃ§Ã£o â†’ processo
5. Seu primeiro **playbook** (1 pÃ¡gina por processo)
6. MÃ©tricas simples: o que conta como "deu certo"
7. Rotina de captura: 5 min no fim do dia

**PrÃ¡tica:** fazer engenharia reversa de 1 conteÃºdo seu (ou de referÃªncia) que performou â€” extrair a estrutura em 5 passos.
**EntregÃ¡vel:** **1 playbook** de um processo seu.

### MÃ³dulo 4.2 â€” Biblioteca viva
1. Organizar: prompts, briefings, playbooks num lugar sÃ³
2. NomeaÃ§Ã£o e versÃ£o (v1, v2, "campeÃ£o atual")
3. Checklists a partir de processos repetidos
4. Curadoria: aposentar o que parou de funcionar
5. Compartilhar com equipe / clientes (seu mÃ©todo vira ativo)
6. **Atalho do retardatÃ¡rio:** registre sÃ³ os 3 prompts que mais usa
7. **Na sua profissÃ£o:** professor (banco de planos por turma) Â· advogado (banco de teses e modelos) Â· vendedor (playbook de objeÃ§Ãµes) Â· gestor (decisÃµes registradas + critÃ©rios) Â· criador (estruturas campeÃ£s por formato)

**EntregÃ¡vel:** **Ã­ndice da biblioteca pessoal**.

> **Kit T4** â€” Ficha de aproveitamento:
> ```
> O que tentei: [...] Â· Funcionou? [sim/nÃ£o] Â· Por quÃª: [...]
> Vira template? [...] Â· Vira regra? [...] Â· Onde guardei: [...]
> ```

---

## 7. Trilha 5 â€” Engenharia de Arquitetura (Teal) ðŸŸ¦

**Caso-Ã¢ncora:** *O gargalo invisÃ­vel.* Dez prompts excelentes, biblioteca organizada â€” e o trabalho ainda trava, porque cada etapa depende de vocÃª lembrar de fazer. O problema nÃ£o Ã© nenhum prompt: Ã© que **nÃ£o existe processo conectando as peÃ§as**. SÃ³ arquitetura resolve.
**Pergunta-guia:** *Como organizar tudo num sistema funcional?*
**âš  Regra da trilha:** 100% no-code/conceitual. Nada de ferramenta tÃ©cnica obrigatÃ³ria â€” fluxos desenhÃ¡veis em papel e executÃ¡veis em qualquer chat de IA.

### MÃ³dulo 5.1 â€” Pensar em sistemas, nÃ£o em comandos
1. De comando isolado a fluxo (entradaâ†’interpretaÃ§Ã£oâ†’aÃ§Ã£oâ†’avaliaÃ§Ã£oâ†’ajusteâ†’nova aÃ§Ã£o, Â§7)
2. O que a IA faz num sistema: interpretar, organizar, sugerir, revisar, comparar, executar partes
3. Desenhar seu primeiro fluxo (produÃ§Ã£o de conteÃºdo, Â§7, passo a passo)
4. Pontos de decisÃ£o e ramificaÃ§Ãµes
5. Onde o humano entra (handoff humano Ã— IA)
6. A lÃ³gica do loop: Pensarâ†’Agirâ†’Avaliarâ†’Ajustarâ†’Agir (Â§9)
7. VisÃ£o geral de ferramentas (no-code, agentes) â€” o suficiente pra nÃ£o se intimidar, sem dependÃªncia

**PrÃ¡tica:** desenhar o fluxo do caso-Ã¢ncora e marcar onde ele quebrava.
**EntregÃ¡vel:** **fluxograma de 1 processo seu** (papÃ©is IA/humano marcados).

### MÃ³dulo 5.2 â€” Montando um mini-sistema
1. Do fluxo no papel ao fluxo executÃ¡vel (num simples chat)
2. Encadear prompts (saÃ­da de um vira entrada do outro) â€” exemplo completo de 4 etapas
3. Bases de conhecimento como peÃ§a do sistema
4. Loop de revisÃ£o (a IA avalia o prÃ³prio resultado com critÃ©rios seus)
5. CritÃ©rios de qualidade dentro do fluxo
6. **Atalho do retardatÃ¡rio:** o sistema mÃ­nimo de 3 caixas que jÃ¡ entrega valor
7. **Na sua profissÃ£o:** professor (fluxo de criaÃ§Ã£o de aula) Â· advogado (fluxo de anÃ¡lise de contrato) Â· vendedor (fluxo leadâ†’proposta) Â· gestor (fluxo de decisÃ£o semanal) Â· criador (fluxo ideiaâ†’post publicado)

**PrÃ¡tica:** executar o mini-sistema de 3 caixas com um caso real, do inÃ­cio ao fim.
**EntregÃ¡vel:** **1 mini-sistema documentado** (fluxo + prompts de cada etapa).

> **Kit T5** â€” Esqueleto de fluxo:
> ```
> [Entrada] â†’ [IA interpreta] â†’ [IA gera proposta] â†’ [AvaliaÃ§Ã£o: critÃ©rios X]
>   â†’ ok: [entrega] Â· nÃ£o ok: [ajusta] â†’ volta Ã  geraÃ§Ã£o
> ```

---

## 8. Trilha 6 â€” Engenharia de EvoluÃ§Ã£o (Rose) ðŸŒ¹

**Caso-Ã¢ncora:** *O vÃ­deo que bombou (e o canal que nÃ£o aprendeu nada).* Um vÃ­deo fez 50Ã— a mÃ©dia. O criador comemorou â€” e o canal seguiu igual. Seis meses depois, ninguÃ©m sabe replicar. Sistema rodando nÃ£o Ã© sistema evoluindo: faltou o ciclo que transforma resultado em aprendizado.
**Pergunta-guia:** *Como o sistema melhora com o tempo?*

### MÃ³dulo 6.1 â€” O ciclo que aprende
1. Comemorar nÃ£o basta â€” extrair o porquÃª
2. As 8 perguntas pÃ³s-resultado (tema, tÃ­tulo, imagem, promessa, estrutura, comentÃ¡rios, repetir, ajustar â€” Â§8)
3. Feedback como combustÃ­vel: cliente, dados, erro
4. Fechar o loop: aprendizado vira input do prÃ³ximo ciclo
5. Refinamento contÃ­nuo de prompts/briefings/playbooks
6. HistÃ³rico de decisÃµes como ativo
7. Sinais de que o sistema evolui de verdade (vs. sÃ³ roda)

**PrÃ¡tica:** aplicar as 8 perguntas a 1 trabalho recente seu.
**EntregÃ¡vel:** **1 retrÃ´** com 3 melhorias pro prÃ³ximo ciclo.

### MÃ³dulo 6.2 â€” InteligÃªncia operacional acumulada (capstone)
1. Juntar tudo: prompts + intenÃ§Ã£o + contexto + mÃ©todos + arquitetura + evoluÃ§Ã£o
2. Ritmo de revisÃ£o (semanal/mensal) sem burocracia
3. MÃ©tricas que importam pro SEU objetivo
4. Quando reescrever o sistema vs. ajustar
5. Vantagem composta: por que em 6 meses o "atrasado" ultrapassa quem sÃ³ coleciona prompts
6. **Capstone como portfÃ³lio:** montar o "mapa do seu sistema de conhecimento de IA" (1 pÃ¡gina) E **como apresentÃ¡-lo** â€” post de LinkedIn pronto pra adaptar, como descrever no currÃ­culo, como explicar numa entrevista ("eu nÃ£o uso IA, eu opero um sistema de IA")
7. **Atalho do retardatÃ¡rio:** a pergunta Ãºnica "o que repito que poderia ser melhor?"

**EntregÃ¡vel-mÃ£e:** **Mapa do Sistema de Conhecimento de IA** (peÃ§a de portfÃ³lio) + post de LinkedIn adaptÃ¡vel.

> **Kit T6** â€” Ritual de evoluÃ§Ã£o (pÃ³s-entrega):
> ```
> Funcionou: [...] Â· Por quÃª: [...]
> Ajustar: [...] Â· Vira regra nova? [...]
> PrÃ³ximo ciclo comeÃ§a com: [...]
> ```

---

## 9. Prova da PirÃ¢mide (curso/prova/index.html) ðŸ†

**PrincÃ­pio:** fÃ¡cil de realizar (pra pessoa E pra gente construir) e **a correÃ§Ã£o ensina** â€” quando a pessoa vÃª a resposta, ela entende na hora.

### Formato
- **12 questÃµes** de mÃºltipla escolha â€” 2 por camada, em ordem da pirÃ¢mide.
- Cada questÃ£o Ã© um **mini-caso prÃ¡tico** ("Maria pediu X e recebeu Y genÃ©rico. Qual camada falhou?"), nunca decoreba.
- **CorreÃ§Ã£o instantÃ¢nea, questÃ£o a questÃ£o**: clicou â†’ vÃª na hora se acertou + **gabarito comentado** (por que a certa Ã© certa E por que cada errada Ã© errada). Errar tambÃ©m ensina.
- 100% client-side (HTML+JS, padrÃ£o ARCKHÉ) â€” sem cadastro, sem backend, roda no GitHub Pages.

### Resultado = badge compartilhÃ¡vel (motor viral nÂº 2)
- 0â€“4: **Explorador da Base** ðŸŸ¢ Â· 5â€“8: **Construtor de Contexto** ðŸŸ£ Â· 9â€“11: **Arquiteto de Sistemas** ðŸŸ¦ Â· 12: **Engenheiro de EvoluÃ§Ã£o** ðŸŒ¹
- Card visual com nÃ­vel + pirÃ¢mide colorida atÃ© a camada alcanÃ§ada + frase pronta: *"Tirei [nÃ­vel] na Prova da PirÃ¢mide da IA. Em qual camada vocÃª estÃ¡? ðŸ‘‰ [link]"*
- BotÃ£o "copiar resultado" + link pra trilha recomendada conforme os erros ("vocÃª errou as 2 de contexto â†’ comece pela T3").

### Exemplo de questÃ£o (modelo)
> **Q7.** JoÃ£o tem 30 prompts excelentes salvos, mas toda semana esquece etapas do processo de criar a newsletter. Qual camada resolve?
> a) Prompt â€” escrever prompts melhores
> b) Contexto â€” anexar mais arquivos
> c) **Arquitetura â€” conectar as etapas num fluxo** âœ…
> d) EvoluÃ§Ã£o â€” analisar resultados passados
>
> **Gabarito comentado:** os prompts jÃ¡ sÃ£o bons (nÃ£o Ã© a) e a IA jÃ¡ entende o assunto (nÃ£o Ã© b). O problema Ã© que as peÃ§as nÃ£o estÃ£o conectadas num processo â€” exatamente o papel da Arquitetura. EvoluÃ§Ã£o (d) viria depois: sÃ³ se melhora um processo que existe.

---

## 10. Fio condutor "pronto pra usar"

| Camada | Artefato que sai pronto |
|--------|-------------------------|
| Prompt | Biblioteca de prompts + checklist de verificaÃ§Ã£o |
| IntenÃ§Ã£o | Carta de intenÃ§Ã£o reutilizÃ¡vel |
| Contexto | Briefing-base + checklist de privacidade |
| Aproveitamento | Playbook + Ã­ndice da biblioteca |
| Arquitetura | Fluxo + mini-sistema documentado |
| EvoluÃ§Ã£o | **Mapa do sistema (portfÃ³lio) + post LinkedIn + ritual** |

Entrega-mÃ£e: o **Sistema de Conhecimento de IA pessoal** â€” mostrÃ¡vel em entrevista, LinkedIn e proposta de serviÃ§o.

---

## 11. Plano de marketing viral ðŸ“£

### Motor 1 â€” DiagnÃ³stico de nÃ­vel (landing)
- 6 perguntas, 1 por camada, respondÃ­veis em 60s.
- Resultado: "VocÃª estÃ¡ na camada X/6" + pirÃ¢mide colorida atÃ© o nÃ­vel + card compartilhÃ¡vel: *"Estou no nÃ­vel [X] da PirÃ¢mide da IA. E vocÃª? ðŸ‘‰ [link]"*
- Loop clÃ¡ssico de teste de personalidade: o resultado Ã© identidade â†’ a pessoa compartilha â†’ o quiz traz a prÃ³xima.

### Motor 2 â€” Prova da PirÃ¢mide (final)
- Badge de conclusÃ£o compartilhÃ¡vel (Â§9). Quem termina divulga; quem vÃª o badge quer o seu.

### Motor 3 â€” SÃ©rie de 6 reels (1 por camada)
Roteiro pronto a partir das frases-Ã¢ncora â€” produÃ§Ã£o via skills `video-explicativo`/`videoprodutor`:
1. ðŸŸ¢ "Prompt Ã© a pergunta." â€” o e-mail difÃ­cil em 4 versÃµes (30s)
2. ðŸ”µ "IntenÃ§Ã£o Ã© o destino." â€” o post perfeito que vendeu zero
3. ðŸŸ£ "Contexto Ã© o mapa." â€” a IA nÃ£o Ã© fraca, estÃ¡ cega
4. ðŸŸ¡ "Aproveitamento Ã© o mÃ©todo." â€” o acerto que sua empresa esqueceu
5. ðŸŸ¦ "Arquitetura Ã© o sistema." â€” 10 prompts bons nÃ£o fazem um processo
6. ðŸŒ¹ "EvoluÃ§Ã£o Ã© o aprendizado acumulado." â€” por que o vÃ­deo que bombou nÃ£o te ensinou nada
- Cada reel termina com: "Descubra sua camada â†’ link na bio" (aponta pro diagnÃ³stico).

### Motor 4 â€” ConteÃºdo de ancoragem
- **Carrossel-pirÃ¢mide** (7 slides: capa + 6 camadas) â€” formato que mais performa no Instagram/LinkedIn.
- **Post contrarian de lanÃ§amento:** "VocÃª estÃ¡ atrasado na IA? Ã“timo. â€” Quem entra no topo vÃª complexidade. Quem comeÃ§a na base entende evoluÃ§Ã£o."
- **Post-polÃªmica:** "Pare de salvar prompts. 100 prompts salvos â‰  saber usar IA."

### SequÃªncia de lanÃ§amento
1. Semana -1: post contrarian + carrossel-pirÃ¢mide (semear o framework)
2. LanÃ§amento: diagnÃ³stico no ar + reel 1
3. Semanas 1â€“6: 1 reel/camada/semana, cada um apontando pro diagnÃ³stico
4. ContÃ­nuo: badges da prova gerando prova social orgÃ¢nica

---

## 12. Landing page (index.html)

1. **Hero:** tÃ­tulo-promessa ("VocÃª nÃ£o precisa de 100 prompts. Precisa de 6 camadas.") + frase "Quem entra no topo vÃª complexidade. Quem comeÃ§a na base entende evoluÃ§Ã£o." + CTA **"Descobrir minha camada (60s)"**.
2. **PirÃ¢mide interativa (hero SVG):** 6 camadas clicÃ¡veis â†’ trilhas. Cor por camada.
3. **DiagnÃ³stico de nÃ­vel** (6 perguntas + card compartilhÃ¡vel).
4. **"VocÃª estÃ¡ atrasado? Ã“timo."** â€” a tese do retardatÃ¡rio.
5. **Grid das 6 trilhas** (cor + frase-Ã¢ncora + caso-Ã¢ncora em 1 linha + nÂº mÃ³dulos).
6. **"Na sua profissÃ£o"** â€” 5 perfis, 1 linha cada.
7. **O kit que vocÃª leva** (os 6 artefatos + mapa-portfÃ³lio).
8. **Prova da PirÃ¢mide** (teaser do badge).
9. **CTA final + ARCKHÉ AI** (`text-sky-400`).

---

## 13. Roadmap de produÃ§Ã£o

1. **Landing** com pirÃ¢mide + diagnÃ³stico (motor viral primeiro â€” comeÃ§a a captar antes do curso completo).
2. **Trilha 1** completa (Base Zero + verificaÃ§Ã£o) â€” destrava o retardatÃ¡rio.
3. Trilhas **2 e 3** (IntenÃ§Ã£o, Contexto + privacidade).
4. Trilha **4** (Aproveitamento).
5. Trilhas **5 e 6** (Arquitetura, EvoluÃ§Ã£o + capstone portfÃ³lio).
6. **Prova da PirÃ¢mide** + badges.
7. RevisÃ£o com `revisar-curso` + registro no **portal ARCKHÉ AI**.
8. ProduÃ§Ã£o dos 6 reels (skills de vÃ­deo) conforme sequÃªncia de lanÃ§amento.

PadrÃµes ARCKHÉ em todas as pÃ¡ginas: nav completo, theme toggle, SVG futurista por mÃ³dulo, mapa da trilha, â‰¥6 tÃ³picos/mÃ³dulo, ARCKHÉ AI.

> **Nota comercial:** se o curso for comercial, imagens raster via `qwen-edit-2511` (FLUX klein/dev Ã© non-commercial). SVGs inline sem restriÃ§Ã£o.

---

## 14. Registro das decisÃµes (v2)

- âœ… VerificaÃ§Ã£o/alucinaÃ§Ã£o â†’ **T1** (Base Zero, tÃ³pico 6). Privacidade/dados â†’ **T3** (mÃ³dulo 3.1, tÃ³pico 7).
- âœ… Caso-Ã¢ncora exclusivo por trilha (anti-repetiÃ§Ã£o T1â€“T3).
- âœ… T5 travada em no-code (proteger o pÃºblico retardatÃ¡rio).
- âœ… Box "Na sua profissÃ£o" (5 perfis) em todas as trilhas.
- âœ… Capstone T6 = peÃ§a de portfÃ³lio + post LinkedIn + script de entrevista.
- âœ… TÃ­tulo-promessa + 2 motores virais (diagnÃ³stico + prova com badge) + 6 reels + sequÃªncia de lanÃ§amento.
- âœ… Prova final: 12 questÃµes-caso, correÃ§Ã£o instantÃ¢nea com gabarito comentado (ver a resposta = aprender), client-side, badge compartilhÃ¡vel.
