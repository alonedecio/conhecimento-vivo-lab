# CONHECIMENTO/VIVO — CREATIVE LAB 001
## Pesquisa de direção de arte, motion e narrativa imersiva
Data: 2026-10-17 · Estado: briefing de exploração · Escopo: APENAS repositório conhecimento-vivo-lab

> Objetivo: desenvolver uma landing cinematográfica e interativa que demonstre como expertise humana se converte em inteligência proprietária, estruturada, verificável e em evolução — sem tocar a versão oficial.

## 0. Premissas e proteção
- A versão oficial aprovada permanece intocada. Este documento e futuros protótipos devem existir exclusivamente no repositório LAB.
- O LAB atual contém index.html, index-en.html, diagnostico.html, diagnostico-en.html, styles.css, script.js, mobile-v16.css e docs/.
- O index.html atual já contém linguagem visual dark, esverdeada, grafos de agentes, halos, animações de conexões, canvas/reveal e diagnóstico. Isso é um ponto de partida, não um limite criativo.
- A comparação considera provisoriamente **ZexIA (https://zexia.ai/)**, empresa brasileira de soluções de IA personalizadas. O pedido chamou a referência de “ZexAI”; confirmar o endereço, se for outro site.
- A leitura da ZexIA baseia-se na página publicamente indexada. Não houve captura frame a frame, inspeção do JavaScript compilado nem medição de duração/easing. Não atribuir efeitos ou bibliotecas específicas ao concorrente sem auditoria visual/técnica posterior.

## 1. ZexIA: anatomia narrativa verificável
1. **Abertura:** fotografia de uma área comercial escura, com um único escritório iluminado. Manchete: “O expediente acabou. As vendas, não.” A luz encena um problema comercial.
2. **Gancho temporal:** 22h46 → 22h47 → 22h48 → amanhã, 9h. O relógio organiza a história e transforma argumento de automação em acontecimento.
3. **Demonstração simultânea:** conversa do cliente, intervenção do agente, qualificação, reunião marcada e registro estruturado no CRM. Importante: causa e efeito visualmente rastreáveis.
4. **Participação:** demonstração de agente por texto e voz com ficha do CRM ao lado. O visitante deixa de apenas assistir e começa a testar.
5. **Capítulos:** cinco resultados em horários de um dia operacional (22:47, 02:14, 07:30, 09:50, 18:40).
6. **Credibilidade:** casos setoriais, processo comercial, o que a empresa não faz, FAQ e CTA.

Fonte: https://zexia.ai/

### Inventário de motion a auditar no navegador
A tabela separa **elementos observáveis no conteúdo** de **tratamentos audiovisuais que propomos investigar**, evitando inventar a implementação do concorrente.

| Camada | Elemento observável da página | Tratamento de motion/luz a testar no LAB |
|---|---|---|
| Hero | Exterior noturno, escritório aceso | Cinemagraph com janelas estáticas e uma luz interna que ganha intensidade; câmera com push-in de 1–2% |
| Sequência | Horários/etapas 22:46–22:48 | Scroll-scrub e iluminação sincronizados; roteiro de 5 beats; legenda sempre visível |
| Conversa | Mensagens, typing, reunião | Cascata de mensagens com atraso controlado; transição da mensagem para artefato estruturado |
| CRM | Lead, temperatura, etapa e evidência | Painel iluminado progressivamente à medida que chegam dados; evitar fake numbers |
| Capítulos | Cinco resultados do dia | Pinned chapter e mudanças de plano por scroll, com saída descomplicada em mobile |
| Contato | Demonstração por texto e voz | Microinterações imediatas, mensagens de erro claras e estado de carregamento |
| Conversão | Casos, método, CTA | Descanso visual, prova legível e CTA sempre acessível |

**O que aprender:** dramaturgia em vez de lista de features; implicações reais em vez de efeitos de IA genéricos.
**O que NÃO importar:** storytelling centrado em automação WhatsApp/CRM, relógio 22h47, promessas de operação 24h se não forem a essência de Conhecimento/Vivo.

## 2. A tese criativa própria
Conhecimento/Vivo não é só um agente que responde; é um ambiente em que o conhecimento especializado é extraído, organizado, operacionalizado, testado com especialistas e continuamente aprimorado.

Proposta de arco dramático:
**Invisível → Extraído → Organizado → Testado → Vivo**

Metáfora contínua: uma matéria luminosa, inicialmente difusa e fragmentada, torna-se uma estrutura inteligível. Essa estrutura reage às perguntas do usuário; quando ocorre incerteza, mostra fonte, limite e necessidade de revisão. A interface não finge infalibilidade.

### Lema de direção
**A informação entra como ruído. A expertise aparece como estrutura. A confiança nasce da verificação.**

## 3. Três territórios visuais para testar (não escolher ainda)

### A — O Arquivo de Luz
- Linguagem: museu futurista, lentes macro, vidro fosco, tipografia editorial e poucos objetos icônicos.
- Paleta: obsidiana, verde espectral, branco quente; highlights extremamente controlados.
- Motion: câmera lenta e intencional, foco respirando, relighting, shader de refração, transições por passagem de um feixe de luz.
- Força: premium, credível, cinema e clareza.
- Risco: parecer marca genérica de hardware de luxo.

### B — A Biblioteca que Respira
- Linguagem: inteligência como ecossistema vivo, filamentos, ramificações, tecidos de conhecimento; nada de cérebro de neon clichê.
- Motion: crescimento orientado a nós, forças suaves, bloom localizado, rastros de decisões, hover que revela critério.
- Força: relação direta com o nome Conhecimento/Vivo.
- Risco: abstração excessiva, GPU alta, pouca explicação da proposta.

### C — Atlas da Expertise
- Linguagem: enciclopédia interativa + laboratório científico + cinema editorial.
- Motion: decomposição de documentos em sinais, convergência para mapas de critérios, split type, panorâmicas entre diagramas.
- Interação: clicar numa decisão e abrir fonte, exceções, avaliação e responsável humano.
- Força: une sofisticação com a especificidade do negócio.
- Risco: excesso de informação se cada seção virar dashboard.

**Experimento inicial recomendado:** misturar C (clareza e estrutura) com A (luz e cinematografia). B como camada orgânica contextual, não como estética dominante.

## 4. Storyboard de uma landing-experiência
| Ato | O que o visitante vê | O que compreende | Mecanismo proposto |
|---|---|---|---|
| 00 — Cold open | Escuridão, partículas de fragmentos e uma voz/texto curta sobre conhecimento perdido | O ativo já existe, mas está disperso | Entrada progressiva, som opcional e hero estático de fallback |
| 01 — O invisível | Pequenas decisões humanas, arquivos e conversas desconectadas | Expertise não equivale a um conjunto de PDFs | Parallax de camadas, texto em profundidade |
| 02 — Captura | Fragmentos convergem em um núcleo com critérios nomeados | Especialistas ajudam a explicitar contexto e exceções | Scroll-scrub, morph/dissolve e luz focal |
| 03 — Arquitetura | Núcleo abre um mapa de conhecimento navegável | Não se trata só de colocar documentos num chatbot | Grafo interativo; hover revela origem e relação |
| 04 — A prova | Pergunta real atravessa critérios; uma decisão precisa de revisão | Evals e especialistas dão limites e confiabilidade | Interface interativa auditável, estados explícitos |
| 05 — O vivo | Estrutura aprende por correções validadas e fica mais clara | O conhecimento evolui sem perder governança | Crescimento discreto e propagação de luz |
| 06 — Convite | Volta à tipografia limpa e diagnóstico / conversa | Existe um próximo passo concreto | Motion reduzido; CTA e diagnóstico existentes |

Ao longo dos atos: CTA visível em pontos de transição; navegador por capítulos opcional; mobile não pode exigir 3D nem longos scrolls.

## 5. Linguagem do motion
- **Motion de câmera:** dolly-in, orbit limitada e rack focus digital. Pouco movimento deve carregar muita intenção.
- **Motion de matéria:** particle flow → aggregation → topology; a transformação mostra maturação, não explosão decorativa.
- **Motion tipográfico:** máscara por linha, deslocamentos contidos, tracking e grandes mudanças de escala nos títulos de ato.
- **Motion de interface:** 160–300ms para microinterações; 500–1100ms para revelações; scroll narrativo com controle do usuário. Durações são hipóteses, testar.
- **Luz:** key light em objeto central; bloom seletivo e localizado; caustics/refração apenas como sotaque; haze muito suave para profundidade.
- **Transições:** corte editorial entre grandes ideias; match cut entre formas relacionadas; light-wipe somente quando ilumina a próxima ideia.
- **Som:** opcional e desligado por padrão; ativação consciente; texturas reativas discretas, nunca áudio surpresa.

## 6. Artistas e estúdios por disciplina
### Web imersiva / creative development
- **Active Theory** — https://activetheory.net/ — direção imersiva, mundos WebGL, sensação de presença; estudar câmera e progressão espacial.
- **Unseen Studio** — https://2025.unseen.co/ — editorial em movimento, scroll chapters, experiências tipográficas; estudar ritmo e controle de atenção.
- **Resn** — https://resn.co.nz/ — web experimental com personalidade; estudar interações memoráveis sem copiar gimmicks.
- **makemepulse** — https://www.makemepulse.com/what-we-do/ — experiências narrativas em WebGL, instalações e 3D; estudar linguagem multisensorial.
- **Bruno Simon** — https://bruno-simon.com/ — navegação como exploração, objeto interativo e regras de jogo.
- **Yuri Artiukh** — https://threejs-workshops.com/ — shaders e técnicas WebGL; referência de execução e prototipagem.

### Arte generativa / dados vivos
- **Refik Anadol** — https://refikanadol.com/works/machine-hallucination/ — dados como escultura imersiva; intensidade e ideia de memória.
- **Ryoji Ikeda** — https://www.ryojiikeda.com/project/datamatics/ — dados em ritmo, escala, silêncio, contraste; pensar tempo e precisão.
- **teamLab** — https://www.teamlab.art/ — ambientes relacionais; interação que muda o sistema e não apenas anima um botão.

### Iluminação / composição / cinematic CGI
- **James Turrell** — https://www.pacegallery.com/artists/james-turrell/ — luz como matéria e arquitetura de percepção.
- **GMUNK** — https://gmunk.com/BOX — projeção mapeada, robótica, luz e efeitos ópticos.
- **FutureDeluxe** — https://futuredeluxe.com/ — materiais, direção futurista, filmes de alta textura.
- **ManvsMachine** — https://mvsm.com/ — motion, composição 3D, identidades cinéticas.
- **Peter Tarka** — https://petertarka.com/ — escultura abstrata, materialidade e direção de arte 3D.

### Branding, tipografia e didática do motion
- **BUCK** — https://buck.co/work/zapier-motion-library — arte e motion traduzindo funcionalidades em narrativas.
- **Ordinary Folk / Jorge R. Canedo** — https://www.ordinaryfolk.co/project/equilibrium — transições de forma, ritmo e materialidade; também observar https://www.ordinaryfolk.co/process
- **Bureau Borsche** — https://bureauborsche.com/ — vocabulário editorial e tipografia como identidade, não mero conteúdo.
- **Max Cooper** — https://maxcooper.net/ — relação entre memória, geometria, audiovisual e emoção.

## 7. Implementação de referência para protótipos
**V0 (provar direção criativa, sem depender de GPU):** HTML/CSS/SVG + GSAP ScrollTrigger, fotos e vídeo leve de fallback. Protótipo de 2 seções somente: hero + transformação. Incorporar textos reais da proposta de valor.

**V1 (prova de luz/volume):** Three.js para UM objeto central com render sob demanda, light rig, pós-processamento bloom moderado e câmera controlada por ScrollTrigger. Usar texturas de resolução adequada.

**V2 (participação):** painel que transforma exemplos de expertise em critérios + mostra a avaliação humana; deve explicar, não mascarar, o funcionamento.

Libs/docs:
- GSAP ScrollTrigger: https://gsap.com/docs/v3/Plugins/ScrollTrigger/
- Three.js: https://threejs.org/
- Bloom: https://threejs.org/docs/pages/UnrealBloomPass.html
- Lenis, somente se fizer sentido e após teste de acessibilidade: https://github.com/darkroomengineering/lenis
- Reduced motion: https://developer.mozilla.org/en-US/docs/Web/CSS/Reference/At-rules/%40media/prefers-reduced-motion

### Critérios não negociáveis
- Primeiro conteúdo legível sem aguardar intro e sem forçar loading cinematográfico.
- Sem autoplay com som, sem flashes agressivos; preferência de movimento reduzido respeitada.
- Mobile recebe direção de arte própria, preferindo vídeo/frame/render simplificado em lugar de 3D pesado.
- Texto essencial e CTA continuam DOM real, selecionável, acessível e indexável.
- Evitar visual “rede neural genérica”, jargão falso, números inventados ou demos que pareçam dados de clientes reais.
- Verificar LCP, CLS, INP, FPS e consumo de memória em smartphone intermediário antes de promover qualquer experimento.
- No experimento, registrar: hipótese, resultado visual, clareza percebida, impacto de performance e decisão (adotar/rejeitar).

## 8. Próximas decisões
1. Confirmar se a referência era zexia.ai ou outra ZexAI e, se necessário, refazer auditoria.
2. Montar 3 styleframes independentes com as direções A/B/C (sem escrever landing ainda).
3. Selecionar 1 direção visual para um vertical slice hero → primeira transição → primeiro diagrama com motion real.
4. Testar se visitantes compreendem “conhecimento proprietário estruturado e avaliado” sem explicação do fundador.
5. Se funcionar, evoluir para capítulos; caso contrário, revisar primeiro a metáfora narrativa, não aumentar os efeitos.

### Regra do laboratório
Nada é promovido à landing oficial por fascínio visual. Só sobe depois de demonstrar clareza comercial, experiência de uso e desempenho.
