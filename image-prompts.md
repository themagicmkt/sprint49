# Prompts de imagem — Página Sprint 49

Documento com **todos os assets visuais** da página, organizados por seção, com:
- Especificações técnicas (dimensão, formato, peso ideal)
- Prompt pronto pra gerador de imagem (Midjourney v6 / Flux / Ideogram / DALL·E 3)
- Variações alternativas quando útil
- Notas sobre assets que **NÃO devem ser gerados por IA** (logos reais, fotos do Leandro etc.)

**Diretrizes globais de marca** (aplique em todo prompt):
- Cor primária: laranja `#FF6B1A`
- Cor secundária: preto profundo `#0A0A0A`, off-white `#F5F5F0`, dourado `#FFB800`
- Estilo geral: moderno, premium, founder-tech, Stanford-meets-Vale-do-Silício
- Evitar: clip-art, stock genérico anos 2010, gradientes pastéis, ícones flat coloridos infantis

---

## 1. HERO — Mockup notebook + celular
- **Onde aparece:** seção Hero, abaixo do CTA principal
- **Dimensão:** 1600×900 (16:9)
- **Formato:** WebP (peso alvo: <200kb)
- **Arquivo sugerido:** `img/hero-mockup.webp`

**Prompt (Midjourney/Flux):**
```
photorealistic product mockup of a modern MacBook Pro 16" and iPhone 15 Pro side
by side on a dark matte black surface, screens both turned on displaying a sleek
startup education dashboard, vibrant orange (#FF6B1A) UI accents on deep black
interface, "Sprint 49" wordmark visible on the laptop screen, video lesson player
with progress bar showing "Day 3 of 7" and a sidebar of modules, the phone screen
shows a community chat with bright orange highlights, soft cinematic studio
lighting from upper-left, subtle orange rim light from the right, shallow depth
of field, slight reflection on the surface, professional commercial product
photography, ultra detailed, 8k, 16:9 --ar 16:9 --style raw --v 6
```

**Variação (top-down):**
```
top-down flat-lay of a MacBook open on a matte black desk, screen showing a dark
mode startup course dashboard with orange #FF6B1A accents, an iPhone next to it
showing a Discord community, a notebook with bold "49" branding on the corner, a
black ceramic coffee cup, soft directional light, premium founder workspace
aesthetic, 16:9
```

---

## 2. INFOGRÁFICO — Jornada Dia 1 → Dia 7
- **Onde aparece:** seção "Apresentando Sprint 49"
- **Dimensão:** 1600×700 (16:7)
- **Formato:** SVG (preferencial) ou PNG transparente
- **Arquivo sugerido:** `img/jornada-7-dias.svg`

**Prompt (Ideogram v2 — melhor pra texto/infográfico):**
```
minimalist horizontal timeline infographic titled "Sprint 49 — 7 dias", deep
black background, 7 large circular milestone nodes from left to right labeled
D1, D2, D3, D4, D5, D6, D7 in bold Iceland font, each node filled with vibrant
orange #FF6B1A, connected by a thin glowing orange line, each node has a single
minimal line icon above it (lightbulb for D1, target for D2, magnifying glass
for D3, speech bubble for D4, microphone for D5, rocket for D6, checkmark for
D7), short uppercase label under each (DECOMPOR, ICP, ACHAR, SCRIPT, ENTREVISTAR,
LANDING, DECIDIR), generous negative space, premium tech infographic style,
flat design, no decorative noise, 16:7 aspect ratio
```

**Alternativa:** Construir manualmente em Figma — fica mais previsível pro texto.

---

## 3. MOCKUP DOS MATERIAIS — Stack de entrega
- **Onde aparece:** seção "O que você recebe"
- **Dimensão:** 1200×1500 (4:5 vertical)
- **Formato:** WebP
- **Arquivo sugerido:** `img/stack-entrega.webp`

**Prompt (Midjourney/Flux):**
```
overhead top-down flat-lay product photography of a complete startup education
toolkit on a deep matte black surface, composition includes: an open MacBook Pro
showing a dark-mode video lesson player with orange #FF6B1A play button visible,
an iPad displaying a colorful framework template/worksheet (ICP canvas style),
a printed spiral-bound workbook with bold orange "49" letters on the cover,
a smartphone showing a Discord community chat with founders, a leather notebook,
a fine-tip pen, a black ceramic coffee mug, soft directional orange rim lighting
from upper right creating gentle shadows, premium commercial photography,
intentional negative space, founder workspace mood, ultra detailed, 4:5
--ar 4:5 --style raw --v 6
```

---

## 4. FOTO DO LEANDRO PIAZZA
- **Onde aparece:** seção "Quem te guia"
- **Dimensão:** 1000×1200 (5:6 vertical)
- **Formato:** WebP
- **Arquivo sugerido:** `img/leandro-piazza.webp`

> ⚠️ **NÃO GERAR POR IA.** É pessoa real e pública. Use foto oficial.
>
> **Onde pegar:**
> - LinkedIn: https://www.linkedin.com/in/leandro-piazza/
> - Press kit: solicitar via contact@49educacao.com.br
> - Imagens em entrevistas/matérias (Startupi, SC Inova, NSC Total)
>
> **Tratamento sugerido:** foto em fundo escuro, com leve gradiente laranja por
> trás (pode ser feito em CSS sem precisar editar). Crop a partir do peito,
> olhando pra câmera. Se a foto for clara, aplicar overlay preto 30%.

---

## 5–7. FOTOS DE DEPOIMENTO (3 founders)
- **Onde aparece:** seção "Quem já fez"
- **Dimensão:** 200×200 cada (avatar circular)
- **Formato:** WebP
- **Arquivos sugeridos:** `img/depoimento-1.webp`, `-2.webp`, `-3.webp`

> ⚠️ **PRIORIDADE: usar fotos REAIS dos founders citados (com consentimento).**
> Depoimento fake é ilegal (CDC art. 37) e mata credibilidade.
>
> **Caminhos:**
> 1. Trocar os depoimentos por casos reais de alunos da 49 (peça 3 cases ao time)
> 2. Coletar a foto + autorização escrita de cada um
> 3. Crop quadrado, centralizado no rosto

**Se for absolutamente necessário usar avatars genéricos (NÃO RECOMENDADO):**
trocar o nome por inicial ou "Aluno 49" e deixar claro que é ilustrativo.

---

## 8. LOGO 49 EDUCAÇÃO (versões)
- **Onde aparece:** topo da página, footer, e (idealmente) favicons
- **Variações necessárias:**
  - Logo principal colorida (PNG transparente, 600×200)
  - Logo monocromática branca (PNG transparente, 600×200)
  - Símbolo isolado "49" (SVG, 200×200) — pra favicon e ícones
- **Arquivos sugeridos:** `img/logo-49.svg`, `img/logo-49-white.svg`

> ⚠️ **NÃO GERAR POR IA.** Use o logo oficial.
>
> **Onde pegar:**
> - Site oficial: https://49educacao.com.br (extrair via inspetor)
> - Solicitar manual de marca via contact@49educacao.com.br
> - Página de branding: https://49educacao.com.br/branding/

A página hoje usa um **placeholder em CSS** (caixa laranja com "49" + texto
"educação" em Iceland). Substituir pelo logo oficial assim que disponível.

---

## 9. SELO DE GARANTIA 7 DIAS
- **Onde aparece:** seção "Garantia"
- **Dimensão:** 400×400 (1:1, transparente)
- **Formato:** PNG transparente ou SVG
- **Arquivo sugerido:** `img/selo-garantia.png`

**Prompt (Ideogram v2 — texto preciso):**
```
circular badge seal design, vibrant orange #FF6B1A solid background, white bold
sans-serif text "GARANTIA 7 DIAS INCONDICIONAL" wrapping around the perimeter,
central icon of a simple shield with a checkmark inside, modern flat vector
style with a subtle vintage stamp feel, slight inner rim border in white,
transparent PNG background, perfectly symmetrical, 1:1 square aspect ratio,
no shadows, no realistic textures, clean and confident
```

**Variação tipográfica (em vez de prompt):** construir em Figma com a tipografia
Iceland (que já está na página) pra manter consistência total.

---

## 10. LOGOS DE MÍDIA (ticker da barra de prova social)
- **Onde aparece:** logo abaixo do hero, ticker animado
- **Lista de logos:** Startupi, IstoÉ Dinheiro, SC Inova, NSC Total, Baguete,
  Economia SC, Startups.com.br
- **Dimensão:** altura 40px, largura variável
- **Formato:** SVG ou PNG transparente, em **cinza/branco** (estilo monocromático)

> ⚠️ **NÃO GERAR POR IA.** Use logos oficiais de cada veículo.
>
> **Onde pegar:**
> - Cada veículo tem press kit no rodapé do site, geralmente em "Imprensa" ou
>   "Sobre"
> - Brandfetch (https://brandfetch.com) tem boa parte
> - Cuidado com direitos de uso — usar só pra menção verídica
>   ("citado em") está dentro do fair use, mas mantenha o aviso

A página hoje usa **wordmark em texto** como placeholder. Trocar pelos PNGs
oficiais e ajustar `<img>` no ticker.

---

## 11. LOGOS DAS STARTUPS DO PORTFÓLIO
- **Onde aparece:** seção "Quem já fez", abaixo dos depoimentos
- **Lista:** Ottimizza, Captei, Feedz, Rocketseat, Contentools, Conpass
- **Dimensão:** altura 48px, largura variável
- **Formato:** SVG/PNG monocromático cinza-escuro

> ⚠️ **NÃO GERAR POR IA.** Use logos oficiais.
>
> **Onde pegar:**
> - Site de cada startup
> - Brandfetch.com
> - Tratamento: converter pra escala de cinza, opacidade 60%

---

## 12. (BÔNUS) OPEN GRAPH IMAGE — pra compartilhamento
- **Onde aparece:** preview no WhatsApp, LinkedIn, Twitter, etc.
- **Dimensão:** 1200×630 (1.91:1)
- **Formato:** PNG/JPG, ≤300kb
- **Arquivo sugerido:** `img/og-sprint49.png`

**Prompt (Ideogram v2):**
```
landscape social media share image, deep black background with subtle orange
radial glow on the right side, on the left side bold Iceland font headline in
white "Em 7 dias, sua ideia validada." with a vibrant orange #FF6B1A underline,
small uppercase tag "SPRINT 49 · 49 EDUCAÇÃO" above the headline in orange,
on the right side a minimalist mockup of a tilted iPhone showing a dark
dashboard with orange UI accents, premium tech brand aesthetic, ultra clean,
1200x630, no clutter
```

**Adicionar ao `<head>`:**
```html
<meta property="og:image" content="img/og-sprint49.png" />
<meta property="og:title" content="Sprint 49 — Valide sua ideia em 7 dias" />
<meta property="og:description" content="O método Stanford da 49 Educação condensado em 7 missões diárias. R$ 197, garantia 7 dias." />
```

---

## 13. (BÔNUS) FAVICON
- **Dimensão:** 512×512 → exportar 32×32, 16×16, apple-touch (180×180)
- **Formato:** PNG + ICO
- **Arquivo sugerido:** `img/favicon.png`

**Prompt:**
```
square brand icon, vibrant orange #FF6B1A rounded square background, bold white
display font number "49" centered, minimal, flat design, no shadow, no gradient,
exportable favicon
```

---

## Checklist final

| # | Asset | Tipo | Status |
|---|---|---|---|
| 1 | Hero mockup | Gerar IA | ⬜ |
| 2 | Infográfico 7 dias | Gerar IA ou Figma | ⬜ |
| 3 | Stack de entrega | Gerar IA | ⬜ |
| 4 | Foto Leandro Piazza | **Foto real** | ⬜ |
| 5 | Depoimento 1 | **Foto real + case real** | ⬜ |
| 6 | Depoimento 2 | **Foto real + case real** | ⬜ |
| 7 | Depoimento 3 | **Foto real + case real** | ⬜ |
| 8 | Logo 49 (3 variações) | **Asset oficial** | ⬜ |
| 9 | Selo garantia | Gerar IA ou Figma | ⬜ |
| 10 | Logos mídia (7) | **Assets oficiais** | ⬜ |
| 11 | Logos portfólio (6) | **Assets oficiais** | ⬜ |
| 12 | OG image | Gerar IA | ⬜ |
| 13 | Favicon | Gerar IA ou Figma | ⬜ |

---

## Dicas de ferramenta

- **Mockups fotorealistas (#1, #3):** Flux Pro 1.1 ou Midjourney v6 dão melhor
  resultado. Evite DALL·E 3 (perde nitidez em telas).
- **Infográficos e selos com texto (#2, #9, #12, #13):** Ideogram v2 é o único
  que renderiza texto sem erro consistentemente.
- **Upscale final:** passar tudo em Topaz Gigapixel ou Magnific antes de exportar.
- **Compressão:** Squoosh.app (WebP qualidade 75) — pesos finais <200kb cada.
