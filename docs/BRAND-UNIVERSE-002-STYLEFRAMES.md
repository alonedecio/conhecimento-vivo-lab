# CONHECIMENTO/VIVO LAB — VISUAL UNIVERSE 002
**Status:** EXPLORAÇÃO / NÃO APROVADO · **Data:** 2026-10-17 · **Escopo:** somente `alonedecio/conhecimento-vivo-lab`

## 0. North Star criativa
**Do universo de possibilidades à inteligência que ganha vida.**

Arco visual único:
1. **COSMOS** — constelações = decisões, fontes, histórias e saberes humanos ainda dispersos.
2. **NÚCLEO** — mergulho da escala astronômica para o microchip; conexões tornam-se estrutura, critérios e processos.
3. **DESPERTAR** — circuitos emitem filamentos orgânicos e luz mais quente; a expertise humana ganha expressão operacional.

"Alma/vida" é metáfora de marca para propósito, comportamento útil, cuidado, conhecimento validado e revisão humana; **não** significa consciência, emoção real ou autonomia irrestrita.

## 1. Styleframes gerados
Foram concebidos três stills cinematográficos 1536×1024, entregues no chat em um pacote ZIP auto-contido com `brandboard.html`, `brand-tokens.css` e as seguintes imagens:
- `assets/01-cosmos.png`: constelações, cristais e órbitas; preto azulado, verde gelado e pontos dourados.
- `assets/02-nucleo.png`: megaprocessador e linhas de energia; escala, precisão e matéria de silício.
- `assets/03-despertar.png`: filamentos suaves emergem de um chip e sugerem uma presença humana abstrata, sem cair num robô clichê.

**Nota operacional:** as imagens estão anexadas ao pacote entregue na conversa, mas não foram incorporadas a este repositório por esta alteração. Para o protótipo visual do LAB, importar a pasta `assets/` do ZIP para um caminho próprio e manter a landing oficial intocada. Os stills são direcionais, não assets finais de produção.

## 2. Proposta cromática
| Nome | Hex | Uso |
|---|---|---|
| Void | `#060B10` | 70% da base escura, respiro cinematográfico |
| Abyss | `#0F1A24` | seções e superfícies |
| Graphite | `#1B3135` | painéis e molduras |
| Paper | `#EAF1EC` | texto claro de leitura |
| Muted | `#A7BBB5` | texto secundário |
| Living Mint | `#A8FFD7` | cor de marca, CTA, pontos-chave |
| Aurora Teal | `#56DCB8` | arestas, trilhas, partículas |
| Soul Gold | `#F0C98D` | calor e revelação, usar raramente |
| Nebula Violet | `#9786CB` | profundidade, foco e micro detalhes, usar raramente |

**Regra:** cor de destaque não deve representar volume indiscriminado de brilho. Fundo escuro + foco luminoso + leitura clara. O ouro marca o momento da transformação, nunca o menu inteiro.

## 3. Tipografia — hipótese inicial
- **Syne** (font-display) 600/700/800: títulos heróicos, peças editoriais, branding e contraste de escalas. Já existe na versão atual do LAB, preservando parte do DNA.
- **Sora** (font-body) 400/500/600: parágrafos, benefícios, conteúdo de interface; substituição experimental da Inter do HTML atual.
- **IBM Plex Mono** (font-system) 400/500: timestamps, capítulos, labels técnicos, fontes, avaliações e métricas.
- **Teste alternativo:** Space Grotesk para display com expressão menos excêntrica; Oxanium APENAS em poucas legendas HUD, jamais todo o site.

Fontes principais open-source/OFL:
- https://fonts.google.com/specimen/Syne
- https://github.com/google/fonts/blob/main/ofl/syne/DESCRIPTION.en_us.html
- https://github.com/sora-xor/sora-font
- https://www.ibm.com/design/language/typography/typeface/
- https://floriankarsten.github.io/space-grotesk/
- https://github.com/google/fonts/blob/main/ofl/oxanium/upstream_info.md

Hierarquia orientadora desktop, NÃO valores finais:
- Display 72–140px, line-height ~.92–1.04, letter-spacing -0.04em a -0.08em, conforme fonte selecionada e teste real de acentos.
- Títulos de seção 44–88px.
- Lead 18–22px; parágrafos 16–18px, line-height 1.55–1.75.
- System labels 10–12px com tracking positivo para small caps; não usar mono em blocos longos.
- Mínimo de três níveis de texto (display, corpo, sistema) e máximo de três famílias em cada view.

## 4. Materiais e composição
- **Cosmos:** névoa cósmica sutil, pontos luminosos, cristais, estrelas como dados, linhas orbitais extremamente finas.
- **Núcleo:** metal escovado escuro, chip cerâmico, vidro preto, gravações a laser, microtraços eletroluminescentes.
- **Despertar:** fibras e capilares de luz, refração moderada, leve mudança de temperatura da luz mint → gold; visualiza manifestação da expertise, não "humano digital" enganoso.
- Pouco brilho por área, grande profundidade de campo quando houver informação, extremos macro quando o objeto for apenas artístico.
- **Tipografia sempre em HTML real**, nunca incorporada como imagem na landing final.

## 5. Motion e transições
1. **ORBIT:** leve dolly-in / câmera orbital; constelações reagem de forma contextual ao deslocamento. Não induzir vertigem.
2. **TRACE:** match cut de estrela→nó→pad do microchip; linhas iluminam-se somente quando passam a representar fontes/critérios conhecidos.
3. **PULSE:** emissões orgânicas moderadas. Um pulso serve para indicar resposta ou correção validada, não afirma "consciência".
4. **EDITORIAL CUT:** grandes títulos permanecem nítidos, texto aparece por máscara em 600–900ms; evitar sequências de carregamento forçadas.
5. **HUMAN VALIDATION:** última transição mostra evidência, limite e a validação por especialista antes do CTA.

Tecnologia recomendada na fase de protótipo: CSS/SVG e GSAP ScrollTrigger; adicionar Three.js apenas para o elemento central se necessário. Sem som automático, sem impedir scroll, respeitar `prefers-reduced-motion` e dispositivos de menor potência. Não copiar efeitos sem medir LCP, CLS e INP.

## 6. Referências artísticas — bibliografia orientada a decisões
- **GMUNK / TRON: Legacy:** https://gmunk.com/TRON-Legacy — rede de linhas, DNA digital inspirado em estruturas naturais; equilíbrio de regra gráfica e organicidade.
- **GMUNK / TRON: Ares computer vision:** https://gmunk.com/TRON-Ares-Computer-Vision — elementos como um único organismo de percepção, não um amontoado de widgets. Referência conceitual particularmente forte.
- **Territory Studio / Blade Runner 2049:** https://territorystudio.com/project/blade-runner-2049/ — interfaces como parte do storytelling; texturas físicas, lentes, variações de luz.
- **Territory Studio / Ghost in the Shell:** https://territorystudio.com/project/ghost-in-the-shell/ — interfaces não planas e representações tridimensionais de informação.
- **Paul Chadeisson:** https://pao.artstation.com/projects — senso de escala cósmica e arquitetura tecnológica monumental.
- **Tendril:** https://tendril.studio/work/ — filmes para marcas tecnológicas complexas, materiais e craft cinematográfico.
- **Universal Everything / Future You:** https://www.universaleverything.com/art/future-you — a experiência só ganha expressão quando o visitante participa; usar interação significativa, não só movimento decorativo.
- **Ryoji Ikeda / datamatics:** https://www.ryojiikeda.com/project/datamatics/ — dados como ritmo, precisão e escala.
- **Refik Anadol:** https://refikanadol.com/works/machine-hallucination/ — dados/memória como matéria abstrata em movimento.

**Apropriação:** estudar os princípios de direção de arte, não copiar projetos, imagens, composições ou elementos protegidos. Os três frames entregues são criações conceptuais novas.

## 7. Clareza de negócio
Conhecimento/Vivo NÃO se reduz a "robô inteligente e bonito": o visitante deve entender **captura colaborativa de expertise → estrutura de critérios e exceções → aplicação → avaliações → revisão contínua**. O motivo de compra precisa permanecer reconhecível.
Exemplos de headlines exploratórias:
- "Há universos de conhecimento dentro da sua empresa."
- "A experiência ganha estrutura."
- "Inteligência que carrega o que seus especialistas sabem."

Proibido sugerir que o sistema já substitui julgamento especializado, compreende como um humano, tem alma literal ou aprende automaticamente sem governança.

## 8. Plano de validação
1. Styleframes (concluído) → revisão da metáfora e temperatura emocional.
2. Typography shootout: Syne vs Space Grotesk em HERO real, português e inglês.
3. Protótipo isolado (não `index.html`): **Cosmos → NÚCLEO** com 1 match cut, 1 headline e 1 CTA.
4. Segundo slice: **NÚCLEO → DESPERTAR** com demonstração de um critério e uma avaliação humana.
5. Testes com público B2B: o que compreenderam em 10s, onde clicaram, desempenho em mobile, reduced motion.
6. Só então decidir se alguma linguagem deve integrar a landing oficial, em outro processo de aprovação.

## 9. Preservação
**Nenhum arquivo da landing do LAB ou repositório oficial deve ser alterado como efeito colateral desta etapa.** Diretrizes seguem no LAB enquanto não houver aprovação específica.
