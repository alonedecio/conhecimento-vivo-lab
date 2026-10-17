# Conhecimento/Vivo — UI LAB 003
**Status:** experimento visual, NÃO aprovado para produção. **Escopo:** LAB somente. **Data:** 2026-10-17.

## Propósito
Traduzir o universo **Cosmos → System → Awakening** em componentes comerciais de landing page, ao invés de fundir visuais de galáxia, chips, néon e matéria viva em uma única cena. Os elementos devem funcionar para empreendedores: clareza de valor antes de exuberância visual.

## Protótipo entregue
Um arquivo HTML independente chamado `conhecimento-vivo-componentes-v003.html` foi produzido e disponibilizado na conversa. É uma vitrine local, com hero, alternância de três linguagens, cards, método, tipografia, cores e CTA.

**Importante:** esta documentação foi salva no GitHub; o protótipo HTML está entregue como arquivo na conversa e **não foi publicado no repositório** nesta etapa. A landing do LAB e a landing oficial continuam intocadas.

## Ideia de direção
**Silêncio espacial. Precisão digital. Presença humana.**
- Cosmos: pouco ruído; constelação como conhecimento disperso.
- System: chip/circuitos, sinais técnicos e grids discretos; cyberpunk **editorial**, não arcade neon.
- Awakening: pulso, luz mais quente, pequenos traços orgânicos; metáfora de uma IA que dá expressão à expertise humana, sem atribuir consciência real.

## Inventário de componentes
| Componente | Conteúdo / papel | Linguagem | Movimento proposto | Critério comercial |
|---|---|---|---|---|
| Header | Logo, 2-3 links, CTA | Minimal tech | Linha inferior acende em 180ms no hover | CTA reconhecível |
| Hero | Headline de proposta de valor, subhead, CTA | Cosmos | Conexões se desenham, estrela central brilha suavemente; texto imóvel | Mensagem compreensível em 5-10s |
| Alternância Cosmos / System / Awakening | Três universos, visualizados separadamente | Curadoria | Transição curta, sem morph pesado e sem retirar foco da copy | Demonstra distinção, evita colagem |
| Card Cosmos | Conhecimento humano disperso | Astronômico | Caminho das conexões desenha e revela rótulo contextual | Evitar gráfico aleatório |
| Card System | Expertise se transforma em critérios, fontes, exceções | Cyberpunk editorial | *Trace* que corre por um circuito em 450–700ms; destaque de um elemento | Tornar estrutura inteligível |
| Card Awakening | Revisão humana e melhoria | Orgânico / sutil | Pulso discreto de 3.5–5s, nunca flash | Vida = evolução verificada |
| Timeline de método | Captura → estrutura → avaliação → evolução | Sistema / informativo | Foco por linha ao scroll ou hover; sem travar navegação | Mostra como entregamos |
| Microindicadores | Fonte, avaliação, revisão, limite | HUD técnico | Status e pequenas mudanças de luz/linha em 140–220ms | Transparência operacional |
| CTA final | Diagnóstico / conversa | Minimal editorial | Sem espetáculo: retorno ao contraste, respiro e ação | Conversão |

## Motion direction: cinco princípios
1. **Motion de conteúdo > motion decorativo:** toda animação mostra descoberta, organização, teste ou refinamento.
2. **Ritmo:** títulos e CTAs aparecem prontos para ler; o movimento vive no visual de apoio.
3. **Atmosfera sem poluição:** animações de partículas nunca preenchem tela inteira, brilho focal e texturas de fundo discretas.
4. **Interface cyberpunk minimal:** filamentos e trilhas finas, referências de instrumentação científica, quase nenhuma ornamentação gratuita.
5. **Acessibilidade e desempenho:** reduced motion, efeitos sem som, mobile com renderização simplificada; nenhuma interação depende de hover.

### Efeitos que devem ser prototipados depois
- **Match cut estrela → nó do chip:** um único ponto do Cosmos se reposiciona e revela o System no momento da mudança de capítulo.
- **Light-guided reveal:** foco luminoso percorre uma aresta e revela o texto relacionado; nunca esconde texto essencial.
- **Scroll chapter:** progressão narrativa opcional por scroll, mas o usuário sempre pode pular sem bloqueio.
- **Alive feedback:** o núcleo pulsa quando há decisão/avaliação demonstrada, não simplesmente em loop incessante.
- **Typographic cut:** uma transição limpa por máscara que marca início/fim de capítulos sem explosão de partículas.

## Tipografia sugerida
- **Space Grotesk**, títulos e headings: geométrica, futurista porém madura — https://floriankarsten.github.io/space-grotesk/
- **Sora**, corpo da página e interface comercial — https://fonts.google.com/specimen/Sora
- **IBM Plex Mono**, status e microtipografia — https://fonts.google.com/specimen/IBM+Plex+Mono
- **Alternativa:** Syne para peças conceituais/editoriais, preservando ligação com o LAB v002 — https://fonts.google.com/specimen/Syne

## Tokens de UI (propostas; não importados na landing)
```css
--bg:#080D11;
--surface:#0D151A;
--line:#263A3B;
--fg:#EAF2EE;
--muted:#98ACA7;
--mint:#A8FFD7;
--gold:#F0C98D; /* só em momentos de vida e revelação */
--violet:#9786CB; /* rara */
--display:'Space Grotesk',sans-serif;
--body:'Sora',sans-serif;
--mono:'IBM Plex Mono',monospace;
```

## Referências para estudar em MOVIMENTO, não apenas stills
- **Active Theory** https://activetheory.net/ — câmera e progressão espacial entre capítulos.
- **Unseen Studio** https://2025.unseen.co/ — transições editoriais entre conteúdo e arte.
- **GMUNK TRON: Legacy** https://gmunk.com/TRON-Legacy — feixes, geometria generativa, brilho intencional.
- **Territory Studio / Blade Runner 2049** https://territorystudio.com/project/blade-runner-2049/ — microinterações, HUD cinematográfico, informação diegética.
- **Ordinary Folk** https://www.ordinaryfolk.co/process — timing, easing e transformações legíveis.
- **Ryoji Ikeda / datamatics** https://www.ryojiikeda.com/project/datamatics/ — silêncio / densidade / ritmo de dados.

Atribuição é inspiração conceitual, não reprodução de layouts, obras ou animações de terceiros.

## Observações e limites do protótipo entregue
**Feito no arquivo:** hero; SVG das 3 cenas acionáveis; pequenas animações de linha/pulso; hover de cards; timeline estática; tipografia proposta; responsividade; `prefers-reduced-motion`. Tudo funciona sem build e sem servidor de dados.

**Não feito ainda:** câmera WebGL; transição cinematic match cut entre cenas; renderização 3D real; avaliação de desempenho em dispositivos reais; estudos com empreendedores; uma landing final; integração com diagnóstico ou agendamento. O CTA do exemplo apenas navega internamente no protótipo.

## Próximo experimento isolado
Um **hero de 1 tela com 2 transições** e três estados discretos:
(1) COSMOS revela fontes -> (2) SYSTEM conecta critérios -> (3) AWAKENING mostra a revisão humana.
Testar a compreensão da promessa em 10s, estabilidade de layout, performance no Android e se o cyberpunk parece premium e não videogame.

**Regra:** não modificar landing oficial nem substituir arquivos existentes do LAB sem aprovação.
