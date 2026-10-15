# Plano da P1 · Geologia de Engenharia I (SGS0405)

Prova **teórica e dissertativa**, à mão, sem consulta. Estudo em um dia: **10h–12h e 13h–17h** (6h).

**Como usar:** em qualquer sessão, cite este arquivo e diga onde está, por exemplo:

> `@INDICE.md` vamos começar
> `@INDICE.md` voltei do almoço

O agente acha o próximo passo, conduz e atualiza este arquivo.

---

## Para o agente (leia antes de qualquer coisa)

1. Leia este índice inteiro e o [`meus-erros.md`](meus-erros.md).
2. O passo atual é a **primeira linha com `[ ]`** da tabela de Passos, salvo se ela disser outro. Veja no **Registro** (fim do arquivo) se ela parou no meio de um passo e em qual bloco.
3. Abra a sessão com 2 linhas: qual passo, quanto tempo está previsto, o que vai acontecer.
4. **Relógio.** Rode `date +%H:%M` e anote no Registro: quando ela **começa a ler**, quando **termina a leitura**, e quando **termina o passo** (depois das questões). Não pergunte a hora para ela; leia do sistema. Ao fechar cada passo, compare com o previsto (coluna "Previsto" e horário-alvo) e diga em 1 linha se está adiantada, no ritmo ou atrasada, e quantos minutos.
5. **Regra geral: aponte, não reescreva.** Se o conteúdo já está num arquivo (explicação de bloco, resposta do gabarito), mande o caminho com o número da linha (ex.: `03-igneas.md:23`) e o nome da seção. Confira a linha com `grep -n` antes. Escreva na conversa só o que não existe em arquivo: a correção da resposta dela, uma explicação nova com outro exemplo quando ela errar, as perguntas de checagem e as questões das provas antigas.
6. **Como conduzir um passo** (siga também o "Roteiro do agente" do arquivo do passo):
   1. Aponte o intervalo dos blocos (do primeiro bloco até "Questões das provas antigas", com as linhas). Ela lê **todos** os blocos de uma vez, sem responder às checagens, e avisa quando terminar. Anote a hora.
   2. Faça as **checagens em ordem, uma por vez**: escreva a pergunta completa na conversa, espere a resposta, corrija pelo `.gabarito.md`. Só então passe para a próxima.
   3. Depois, as **questões das provas antigas** do passo: escreva o enunciado completo na conversa (com o peso). Ela responde por escrito, como faria na prova. **Não mostre a resposta antes de ela tentar.** Corrija pelos critérios do gabarito: diga o que daria nota cheia, o que tiraria ponto e mostre a resposta-modelo.
   4. Se ela errar ou não entender, explique com suas palavras e com **outro** exemplo, sem repetir o texto do arquivo. Não avance com dúvida aberta.
7. **Erros:** todo erro de conceito, atenção ou escrita vai para `meus-erros.md` (uma linha por erro). O passo 10 refaz esses erros.
8. **Ao terminar um passo:** marque `[x]` na tabela e acrescente uma linha no Registro (horários, real × previsto). **Se parar no meio:** anote no Registro o passo e até onde foi (último bloco lido ou última questão corrigida).
9. **Atraso.** Se no fim de um passo ela estiver **mais de 15 min atrasada** em relação ao horário-alvo, avise e proponha o próximo item da lista "Se atrasar, corte nesta ordem". Aplique só com o OK dela e anote aqui o que foi cortado. Se estiver adiantada, sugira gastar a folga no passo 10.
10. **A prova é dissertativa.** Treine resposta escrita: o professor cobra **explicar** (processo + porquê) e **ligar à Engenharia Civil** (uso, problema, obra). Resposta só com nomes, sem o porquê, perde ponto. Corrija nesse critério.
11. As respostas escritas no PDF da prova de 2014 (`material/Prova 2014_.pdf`) são **de um aluno, não um gabarito oficial**, e têm erros (ex.: diz que foliação "está relacionada à forma como as ligações químicas ocorrem"). Use o `.gabarito.md` dos passos.
12. Pesquise na internet só se uma dúvida não estiver coberta pelos passos nem pelos slides.

---

## O que mais cai (tirado das provas de 2025 e 2014)

As duas provas são **dissertativas**, 6 a 8 questões, pesos 1,0 a 2,0. A de 2025 é a mais parecida com a sua (mesmo código SGS0405 e mesmos slides). Ela mudou o estilo: menos "explique tal tema" e mais **aplicação**: um perfil geológico para interpretar, duas contas (RQD e gradiente geotérmico) e escolha de local para obra.

| Tema | 2025 | 2014 | Peso no estudo | Passo |
|---|---|---|---|---|
| Estrutura interna da Terra, sismologia, gradiente geotérmico | Q1 (1,5), Q7 (1,0) | Q4 (1,5) | ★★★ | 01 |
| Ciclo das rochas e tectônica de placas | (base de tudo) | Q4 (1,5) | ★★ | 01 |
| Ígneas: formação, basalto × granito, usos e problemas | Q5 (1,5), Q6 (1,5) | Q5 (2,0) | ★★★ | 03 |
| Sedimentares: tipos e energia do ambiente | Q3 (1,5) | Q1 (cimentação) | ★★★ | 04 |
| Metamórficas: tipos de metamorfismo, protólito → rocha | Q2 (1,0) | Q5 (2,0), Q1 (foliação) | ★★★ | 05 |
| Perfil geológico: cronologia, falhas, intrusões | Q8 (1,0), base de Q2 e Q3 | | ★★★ | 06 |
| Intemperismo, grau de alteração, R e RQD | Q4 (1,0), Q5, Q6 | Q2 (1,5), Q6 (1,5) | ★★★ | 07 |
| Minerais (estabilidade, propriedades) | apoio de Q5 | apoio de Q1 | ★★ | 02 |
| Propriedades da rocha × usos na Eng. Civil | Q6 | Q1 (2,0) | ★★ | 09 |
| Ensaios de laboratório (índices físicos, forma, Is50) | | | ★ (não caiu, mas está no material) | 08 |
| Evolução geológica do Estado de SP | | Q3 (1,5) | ★ (não está nos slides de 2026) | 09 |

**Estratégia para a prova** (o agente reforça no passo 10):

- **Contas valem ponto fácil** (RQD, R, gradiente): escreva a fórmula, os números e a unidade, e conclua com uma frase.
- **Perfil geológico:** use os princípios (superposição, intersecção, inclusão) **pelo nome**. Leia a legenda antes de tudo.
- **"Explique":** processo + causa + consequência para a obra. Sempre um exemplo de rocha e um uso ou problema.
- **Escolha de local** (barragem, fundação): compare os candidatos critério por critério (profundidade do topo rochoso = custo; zonas fraturadas ou vesiculares = resistência e percolação) e feche com o ranking.

---

## Passos

Horário-alvo = quando o passo deveria terminar. Leitura ≈ 1/3 do tempo do passo; o resto é checagem e questões.

| ✔ | # | Passo | Questões das provas antigas | Previsto | Alvo |
|---|---|---|---|---|---|
| **Manhã (10h–12h)** | | | | | |
| [ ] | 01 | [Estrutura da Terra, tectônica e ciclo das rochas](01-terra-e-ciclo.md) ★★★ | 2025 Q1, Q7 · 2014 Q4 | 40 min | 10:40 |
| [ ] | 02 | [Minerais](02-minerais.md) ★★ | (checagens; prepara a 2025 Q5) | 25 min | 11:05 |
| [ ] | 03 | [Rochas ígneas](03-igneas.md) ★★★ | 2025 Q5, Q6 · 2014 Q5 (parte ígnea) | 45 min | 11:50 |
| | | *folga* | | 10 min | 12:00 |
| **Tarde (13h–17h)** | | | | | |
| [ ] | 04 | [Rochas sedimentares](04-sedimentares.md) ★★★ | 2025 Q3 | 35 min | 13:35 |
| [ ] | 05 | [Rochas metamórficas](05-metamorficas.md) ★★★ | 2025 Q2 · 2014 Q5 (parte metamórfica) | 35 min | 14:10 |
| [ ] | 06 | [Estruturas geológicas e leitura de perfil](06-estruturas-e-perfil.md) ★★★ | 2025 Q8 | 40 min | 14:50 |
| | | *pausa* | | 10 min | 15:00 |
| [ ] | 07 | [Intemperismo e parâmetros geotécnicos](07-intemperismo-e-parametros.md) ★★★ | 2025 Q4 · 2014 Q2, Q6 | 50 min | 15:50 |
| [ ] | 08 | [Ensaios de laboratório](08-ensaios.md) ★ | (checagens) | 20 min | 16:10 |
| [ ] | 09 | [Integração: propriedades × usos e SP](09-integracao.md) ★★ | 2014 Q1, Q3 | 25 min | 16:35 |
| [ ] | 10 | Revisão final: refazer os erros de [`meus-erros.md`](meus-erros.md) e repassar a "Estratégia para a prova" | | 25 min | 17:00 |

Soma: manhã 1h50 + 10 min de folga; tarde 3h40 + 20 min de pausa/folga.

**Se atrasar, corte nesta ordem** (um item por vez, com o OK dela):

1. Passo 08 (ensaios): fica só com o bloco 3 (Is50 → σc), 5 min.
2. Passo 09: pula a 2014 Q3 (SP); fica só com a leitura do bloco 2.
3. Passo 02: lê só os blocos 1, 3 e 4 (pula identificação de minerais).
4. Passo 06: no bloco de dobras, só anticlinal × sinclinal.
5. Passo 10: só os erros tipo **C**.

Não corte os passos ★★★ nem as questões de 2025: são o retrato da prova.

---

## Registro

O agente preenche. Horários lidos com `date +%H:%M`.

| Passo | Início | Fim da leitura | Fim | Real | Previsto | Situação | Observação |
|---|---|---|---|---|---|---|---|
