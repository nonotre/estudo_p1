# 08 · Ensaios de laboratório

★ · **20 min** (leitura ≈ 7 min). Slides: `material/7_ensaios 1-2.pdf` e `material/9_ensaios 3-4.pdf`.
Não caiu nas provas antigas, mas está no material de 2026. Respostas: [`08-ensaios.gabarito.md`](08-ensaios.gabarito.md).

## Roteiro do agente

- Leitura dos blocos 1 a 3, depois as checagens 1 a 3.
- Se ela estiver atrasada (corte 1 do INDICE), faça só o bloco 3 e a checagem 3.

---

## Bloco 1 · Índices físicos (quanto vazio a rocha tem)

Fragmentos de rocha (≈ 5 cm) pesados em três estados:

| Massa | Como se obtém |
|---|---|
| **A** = seca | estufa 24 h a 110 °C, pesa no ar |
| **B** = saturada | 48 h na água (vazios cheios), pesa no ar |
| **C** = saturada submersa | pesa dentro da água (o empuxo reduz o peso) |

Com água a 1 g/cm³, o volume total é **Vt = B - C**:

```
massa específica seca   ρd = A ÷ (B - C)            (g/cm³)
absorção d'água         S  = (B - A) ÷ A × 100        (%)
porosidade aparente     p  = (B - A) ÷ (B - C) × 100  (%)
```

**Por que importa num agregado:** mais vazios → **absorve mais água** (piora a trabalhabilidade do concreto), **consome mais cimento**, **menor resistência**, mais **ataque químico** (mais superfície). Basalto vesicular e rochas alteradas têm absorção alta.

## Bloco 2 · Forma dos agregados

Mede-se em 50 fragmentos o comprimento **a**, a largura **b** e a espessura **c**, e calculam-se **b/a** e **c/b** (método IPT M-49):

| Forma | b/a | c/b |
|---|---|---|
| **Cúbica** | > 0,5 | > 0,5 |
| Alongada | < 0,5 | > 0,5 |
| Lamelar | > 0,5 | < 0,5 |
| Alongada-lamelar | < 0,5 | < 0,5 |

- **Cúbica é a melhor**: distribui bem os esforços (mais resistência), menos vazios (economiza ligante, compacta melhor o lastro), concreto mais trabalhável, sem planos de fraqueza.
- Alongada e lamelar: o contrário, e se alinham formando planos de fraqueza.
- Depende da **estrutura da rocha**: **maciça → cúbica** (granito, basalto); **xistosa → alongada/lamelar** (xisto, filito). Frações mais finas tendem a ser mais lamelares. O britador também influi.

## Bloco 3 · Compressão puntiforme e uniaxial

**Compressão uniaxial (simples):** cilindro de rocha comprimido até romper.
- **σc = F ÷ A** (resistência à compressão, MPa);
- **E** (módulo de elasticidade) = inclinação da curva tensão × deformação;
- **ν** (coeficiente de Poisson) = deformação lateral ÷ deformação axial.
- É o ensaio "oficial", mas exige corpo de prova preparado, caro e demorado.

**Compressão puntiforme (*point load*):** comprime um pedaço **irregular** ou de testemunho entre **duas ponteiras**. Portátil, barato, rápido.
- Índice: **Is = P ÷ De²** (De = diâmetro equivalente; em pedaço irregular, De² = 4·W·D ÷ π, W = largura e D = distância entre as ponteiras), corrigido para diâmetro de 50 mm: **Is(50) = Is × (De ÷ 50)^0,45**.
- Despreza os 2 maiores e os 2 menores resultados; Is(50) = média do resto.
- **Estimativa: σc ≈ 25 × Is(50)** (o slide usa 25; a literatura dá entre 20 e 25).
- Limitações: **menos preciso** que o uniaxial e **não serve para rochas brandas**; bom para rochas duras fragmentadas.

---

## Checagens

1. Uma amostra tem A = 500 g, B = 510 g, C = 310 g. Calcule a massa específica seca, a absorção e a porosidade. Serviria como agregado?
2. Por que um xisto dá brita pior que um granito? Use a forma dos fragmentos.
3. Um ensaio puntiforme deu Is(50) = 6 MPa. Qual a resistência à compressão estimada? Por que não se usa esse ensaio num argilito?
