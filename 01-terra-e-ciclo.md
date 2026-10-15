# 01 · Estrutura da Terra, tectônica e ciclo das rochas

★★★ · **40 min** (leitura ≈ 12 min). Slides: `material/1_SGS0405 A1-2026 06go.pdf`.
Questões das provas antigas: **2025 Q1, Q7 · 2014 Q4**. Respostas: [`01-terra-e-ciclo.gabarito.md`](01-terra-e-ciclo.gabarito.md).

## Roteiro do agente

- Leitura dos blocos 1 a 5, depois as checagens 1 a 4, uma por vez.
- Questões, nessa ordem: **2025 Q7** (conta, ganha confiança), **2025 Q1**, **2014 Q4**.
- Na Q7, exija memorial de cálculo: grau geotérmico de cada poço, temperatura a 300 m, conclusão. Se ela usar "gradiente" e "grau" trocados, corrija (bloco 3).
- Na Q1, a parte que mais perde ponto é o "com base em qual fenômeno": a resposta é **ondas sísmicas**, e ela precisa dizer **o que** as ondas mostram (onda S não atravessa o núcleo externo → líquido).

---

## Bloco 1 · As camadas da Terra (duas divisões)

Raio ≈ 6.371 km. Há duas formas de dividir, e a prova pode pedir as duas.

**Pela composição (geoquímica):**

| Camada | Profundidade | Composição |
|---|---|---|
| Crosta oceânica | 5–12 km | basáltica (Si, Mg, Fe) |
| Crosta continental | 35–50 km | granítica (O, Si, Al, K, Na) |
| Manto (superior até 670 km, inferior até 2.900 km) | até 2.900 km | O, Mg, Si, Fe (rochas tipo peridotito) |
| Núcleo externo | 2.900–5.155 km | Fe, Ni · **líquido** |
| Núcleo interno | 5.155–6.371 km | Fe, Ni · **sólido** (pressão altíssima) |

**Pelo comportamento mecânico (geodinâmica):**

| Camada | Profundidade | Estado |
|---|---|---|
| **Litosfera** | 0–100 km | rígida: crosta + topo do manto. É ela que se quebra em **placas** |
| **Astenosfera** | 100–≈ 350 km (o slide estende até 670 km) | **plástica** (sólida, mas flui devagar). As placas deslizam sobre ela |
| Mesosfera | 670–2.900 km | sólida, rígida |
| Núcleo | 2.900–6.371 km | externo líquido, interno sólido |

As fronteiras têm nome: **Moho** (crosta/manto), **Gutenberg** (manto/núcleo, 2.900 km), **Lehmann** (núcleo externo/interno).

## Bloco 2 · Como sabemos disso: ondas sísmicas

Ninguém perfurou além de ≈ 12 km. O modelo vem da **propagação das ondas sísmicas** dos terremotos, registradas em sismógrafos pelo mundo.

- **Onda P** (primária, compressão): atravessa sólidos e líquidos.
- **Onda S** (secundária, cisalhamento): **só atravessa sólidos**.
- A velocidade das ondas muda (e elas refratam e refletem) quando o material muda. Cada mudança brusca é uma **descontinuidade** (Moho, Gutenberg, Lehmann).
- A onda S **some** a partir de 2.900 km → o **núcleo externo é líquido** (zona de sombra das ondas S).
- Apoio: dados geotérmicos, **xenólitos** (pedaços do manto trazidos pelo magma), meteoritos e ensaios de laboratório.

## Bloco 3 · Calor interno: gradiente e grau geotérmico

A temperatura **aumenta com a profundidade**. Dois jeitos de dizer a mesma coisa:

- **Gradiente geotérmico** = °C por metro (ou por km). Média ≈ **30 °C/km** (1 °C a cada ≈ 30–33 m).
- **Grau geotérmico** = **metros** de profundidade para a temperatura subir **1 °C**. Média ≈ 30 m/°C. É o que o slide define.

**Conta típica de prova:**

```
grau = profundidade medida ÷ acréscimo de temperatura     (m/°C)
T(z) = T superfície + z ÷ grau
```

Exemplo: poço de 60 m que esquentou 2 °C → grau = 30 m/°C. A 600 m: T = Tsup + 600 ÷ 30 = Tsup + 20 °C.

Uso na engenharia: águas termais, túneis profundos (calor no túnel), geotermia, metamorfismo (bloco 5).

## Bloco 4 · Tectônica de placas

A litosfera é dividida em **placas** que se movem (cm/ano) sobre a astenosfera, empurradas por **correntes de convecção** do manto. O que acontece nos limites:

| Limite | Movimento | O que gera | Exemplo |
|---|---|---|---|
| **Divergente** | placas se afastam | magma sobe → nova crosta oceânica (basalto), dorsais, vulcões | Dorsal Mesoatlântica |
| **Convergente** | placas se chocam | subducção (uma afunda e funde → magma), cordilheiras, **metamorfismo regional**, terremotos fortes | Andes, Himalaia |
| **Transformante** | placas deslizam lado a lado | falhas e terremotos | Falha de San Andreas |

O Brasil está **no meio** da Placa Sul-Americana (longe dos limites) → poucos terremotos fortes. Mas a tectônica deixou marcas aqui: o embasamento cristalino do leste (gnaisses, granitos) nasceu em colisões de placas há mais de 500 milhões de anos; o basalto da Bacia do Paraná derramou quando a América do Sul começou a se separar da África (≈ 130 milhões de anos); e a escarpa da Serra do Mar é resultado de falhas normais ligadas a essa separação.

## Bloco 5 · Ciclo das rochas e os materiais geológicos

As três famílias de rocha se transformam umas nas outras. Quem move o ciclo: **calor interno** (tectônica: fusão, metamorfismo, soerguimento) e **energia do Sol** (clima: intemperismo, erosão).

```
          fusão                 resfriamento
ROCHA  ─────────► MAGMA ─────────────────────► ÍGNEA
  ▲                                              │
  │ metamorfismo (P e T, sem fundir)             │ intemperismo + erosão
  │                                              ▼
METAMÓRFICA ◄─── P e T ─── SEDIMENTAR ◄── litificação ◄── SEDIMENTO / SOLO
```

Qualquer rocha pode ir para qualquer caminho (uma ígnea pode virar metamórfica direto, uma sedimentar pode fundir).

**Ligação com a tectônica (a 2014 Q4 pede isso):** a tectônica é o motor do ciclo. Subducção funde rocha → magma → ígneas. Colisão de placas → pressão e temperatura → metamórficas. Soerguimento expõe rochas profundas → intemperismo → sedimentos → sedimentares.

**Materiais geológicos que a obra encontra** (de cima para baixo):

| Material | O que é |
|---|---|
| **Solo** (residual) | rocha totalmente alterada, no lugar onde se formou |
| **Sedimento** | partículas **transportadas** (rio, vento, mar) e depositadas, ainda soltas |
| **Saprolito** | rocha muito alterada que ainda guarda a estrutura da rocha-mãe |
| **Rocha alterada** | rocha parcialmente alterada |
| **Rocha sã** | sem alteração |

Solo + sedimento + saprolito + rocha alterada = **regolito** (o "manto" inconsolidado sobre a rocha). A maioria das obras civis fica nos primeiros 0–100 m, ou seja, **dentro do regolito**.

**Índices físicos** (partículas + vazios): porosidade = Vv/Vt × 100; umidade = Ma/Ms × 100; grau de saturação = Va/Vv × 100. Seco (vazios com ar), não saturado (água e ar), saturado (só água).

---

## Checagens

1. Explique a diferença entre **litosfera** e **crosta**, e entre **astenosfera** e **manto**. Por que a divisão geodinâmica importa para a tectônica?
2. Se um terremoto acontece no Japão, por que um sismógrafo do lado oposto da Terra registra a onda P, mas não a onda S? O que isso prova?
3. Um poço de 90 m mostrou acréscimo de 3 °C. Qual o grau geotérmico? Qual a temperatura a 450 m, se na superfície é 22 °C?
4. Descreva o caminho de um granito até virar um gnaisse, e de um granito até virar um arenito. Em cada caminho, qual agente atua (calor interno ou energia solar)?

## Questões das provas antigas

**2025 Q7 (1,0)** · Em investigação preliminar, 02 poços tubulares foram perfurados em 02 locais distintos (A e B) que estão sendo avaliados quanto à exploração como estações de águas termais utilizando o gradiente ou grau geotérmico destas áreas. O poço definitivo deverá explorar a água subterrânea a uma profundidade de 300 m. Qual é o local mais adequado, sabendo-se que para o empreendimento ser viável economicamente, a temperatura média da água tem que estar acima de 40 °C? Justifique com o memorial de cálculo. Outros dados: Poço A: 45 m de profundidade, acréscimo de 3 °C; Poço B: 72 m de profundidade, acréscimo de 4 °C. Temperatura média anual de superfície em A e B é igual a 20 °C.

**2025 Q1 (1,5)** · Quais as principais subdivisões da estrutura interna do planeta? Com base na observação de qual fenômeno ou processo natural foi, e ainda é utilizado, para fundamentar este modelo de estrutura interna?

**2014 Q4 (1,5)** · Explicar como a estrutura interna da Terra e a Tectônica de Placas se relacionam com o ciclo das rochas. Como o conhecimento da estrutura interna da Terra e da Tectônica de Placas pode auxiliar na implantação de obras civis?
