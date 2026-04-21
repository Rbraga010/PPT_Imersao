# CONTEXTO · Imersão H.AI — Slides + VSL

> **Data:** 21/04/2026
> **Founder:** Rodrigo Braga (PulsarH.ai)
> **Status:** Aula 1 estruturada (com imagens ERRADAS embedadas). Precisa trocar pelas 4 imagens CORRETAS do Maurício.
> **Próximo:** Trocar imagens → aprovar Aula 1 → construir Aulas 2-23 iterativamente.

---

## 🚨 AVISO CRÍTICO PRA PRÓXIMA SESSÃO

**EU USEI AS IMAGENS ERRADAS.** Peguei arquivos aleatórios do `C:\Users\rbrag\Downloads\Imagens\` ao invés das 4 imagens que o Rodrigo gerou com os prompts do Maurício.

**As 4 imagens CORRETAS do Rodrigo (anexadas na última mensagem dele):**

| # | Descrição | Destino | Observação |
|---|-----------|---------|------------|
| **1** | **Industrial Revolution engraving** — "The Second Industrial Revolution: A Technological Immersion" — ilustração vintage com fábricas, trens a vapor, navios, torres elétricas, máquinas | Slide 3 (Timeline das eras) OU contexto histórico | Metáfora histórica: assim como a 2ª revolução industrial transformou tudo, a IA faz o mesmo hoje |
| **2** | **Empresário na encruzilhada 2015 vs 2026** — silhueta de homem de terno entre estrada enevoada com placa "2015" (esquerda, cinza/mortiço) e cidade futurística dourada/tech com placa "2026" (direita, brilhante) | **Slide 5 (Diagnóstico)** | PERFEITO — substitui exatamente a imagem errada que usei (businessman no rooftop genérico) |
| **3** | **Tsunami digital subaquático** — ondas/dados dourados e cyan descendo do topo com raios de sol + códigos binários | **Slide 4 (Tsunami)** | PERFEITO — é LITERALMENTE um tsunami de dados/IA. Muito melhor que a onda ECG genérica |
| **4** | **Ondas douradas em circuito escuro** — padrão senoidal de luzes douradas com nodes brilhantes sobre background de circuito azul-escuro | **Slide 1 (Capa)** OU Slide 3 | Elegante, premium PulsarH |

**Essas 4 imagens estão na conversa original como attachments — Rodrigo enviou no final.** Próxima sessão precisa:
1. Pedir pro Rodrigo re-anexar OU olhar em `C:\Users\rbrag\Downloads\` (os arquivos mais recentes, provavelmente com timestamp de 21/04/2026)
2. Salvar em `C:\Sistemas\LandingPage\Landingpage_segundarevolucao\assets\aula1\` substituindo os arquivos errados:
   - `slide1-capa.png` ← Imagem 4 (ondas douradas circuito)
   - `slide3-timeline.png` ← Imagem 1 (industrial revolution)
   - `slide4-tsunami.png` ← Imagem 3 (tsunami subaquático digital) ⚠️ ESSA É A KILLER
   - `slide5-diagnostico.png` ← Imagem 2 (empresário 2015 vs 2026) ⚠️ ESSA TAMBÉM É KILLER

**NÃO precisa mudar o HTML** — basta sobrescrever os arquivos `.png` e recarregar. Os paths CSS já apontam pra esses nomes.

---

## 📂 ARQUIVOS CRIADOS / EDITADOS NESTA SESSÃO

### Arquivo principal (deck + VSL)
```
C:\Sistemas\LandingPage\Landingpage_segundarevolucao\imersao-hai-slides.html
```
- ~970 linhas
- HTML/CSS/JS puro (sem framework)
- Slideshow com modo Apresentar (fullscreen), navegação por setas do teclado
- Notes drawer colapsado por padrão (roteiro + dicas produção escondidos)
- Sidebar com 23 aulas listadas
- Seção VSL com 7 storyboards
- Módulo 1 header + Aula 1 completa (7 slides com roteiro + dicas produção)
- Aulas 2-4 com placeholder "em breve"
- Módulos 2-5 com placeholder

### Assets (imagens ERRADAS — substituir)
```
C:\Sistemas\LandingPage\Landingpage_segundarevolucao\assets\aula1\
├── slide1-capa.png           (atual: Gemini_Generated_Image_jelpicjelpicjelp.png - ondas douradas genéricas)
├── slide3-timeline.png       (atual: Gemini_Generated_Image_sftp30sftp30sftp.png - circuito genérico)
├── slide4-tsunami.png        (atual: Gemini_Generated_Image_pys0pzpys0pzpys0.png - ECG + cubo)
└── slide5-diagnostico.png    (atual: Gemini_Generated_Image_mbdi90mbdi90mbdi.png - rooftop city)
```

### Outros
```
C:\Sistemas\.claude\launch.json   (adicionei config "Slides HAI" na porta 7788)
C:\Sistemas\LandingPage\Landingpage_segundarevolucao\criativos-imersao-hai\SUBIR-MANUAL-9-ADS.md   (briefing Meta Ads — referência histórica, NÃO RELACIONADO às slides)
```

---

## 🎨 ESTRUTURA DA AULA 1 (7 slides)

### Slide 1 · CAPA
- **Título:** "A Tsunami da IA"
- **Subtítulo:** "IA não é tendência. É deslocamento de eras."
- **Classes CSS:** `sv-cover bg-grid-slide`
- **Imagem:** `slide1-capa.png` com `mix-blend-mode:screen; opacity:0.7`
- **Roteiro:** "Bem-vindo. Essa é a Aula 1 da Imersão H.AI — e eu escolhi o nome 'A Tsunami da IA' com cuidado..."

### Slide 2 · HOOK (pergunta)
- **Texto principal:** "Você sabe quem é seu concorrente amanhã?"
- **Classes CSS:** `sv-hook bg-grid-slide`
- **Sem imagem** — fica clean
- **Roteiro:** "Me responde isso — não pra mim, responde pra você mesmo..."

### Slide 3 · LINHA DO TEMPO (4 eras digitais)
- **Grid:** 2010 (site) / 2017 (Instagram) / **2025 (IA.gente) AGORA** / 2027 (IA.gente obrigação)
- **Classes CSS:** `sv-data`
- **Imagem:** `slide3-timeline.png` com `mix-blend-mode:screen; opacity:0.55`
- **Roteiro:** "Deixa eu te mostrar um padrão que sempre se repete..."

### Slide 4 · TSUNAMI (conceito)
- **Layout:** 2 colunas — "Onda você surfa" / "Tsunami muda o fundo do oceano" + box explicando
- **Classes CSS:** `sv-ruptura`
- **Imagem:** `slide4-tsunami.png` com `mix-blend-mode:screen; opacity:0.45`
- **Roteiro:** "Eu escolhi a palavra 'tsunami' com cuidado. Você surfa uma onda..."

### Slide 5 · DIAGNÓSTICO
- **Citação:** "O problema não é falta de inteligência. É inércia do sucesso."
- **2 cards:** "Operando com lógica de 2015" | "Num mundo já em 2026"
- **Classes CSS:** `sv-insight`
- **Imagem:** `slide5-diagnostico.png` com `opacity:0.22` (SEM blend mode — foto de cena precisa ficar legível)
- **Roteiro:** "Agora preciso te dizer uma coisa com cuidado — porque é fácil ouvir e se sentir atacado..."

### Slide 6 · REFRAME (pergunta certa)
- **Pergunta ERRADA:** "Vou usar IA ou não?"
- **Pergunta CERTA:** "Como vou usar — e quando começo?"
- **Classes CSS:** `sv-question`
- **Sem imagem** — contraste visual precisa ser limpo
- **Roteiro:** "Então eu quero te pedir pra fazer uma coisa agora: tire uma pergunta da sua cabeça. Para sempre..."

### Slide 7 · ENCERRAMENTO
- **4 bullets** do que aprendeu
- **Card "Próxima Aula":** Aula 2 · A Nova Geração
- **Classes CSS:** `sv-cta bg-grid-slide`
- **Sem imagem** — foco no resumo
- **Roteiro:** "Nessa aula você entendeu por que IA é tsunami..."

---

## 🎬 ESTRUTURA VSL (7 momentos, 7-9 min)

| # | Momento | Tempo | Visual | Copy curta |
|---|---------|-------|--------|------------|
| 1 | HOOK | 0:00–0:30 | Pergunta que para o scroll | "Você sabe quem vai quebrar primeiro nos próximos 18 meses?" |
| 2 | DOR | 0:30–1:30 | Credencial Rodrigo | "21 anos · 4.500 pessoas · eu sei como é" |
| 3 | SOLUÇÃO | 1:30–3:00 | Método PULSAR+H + stats (2 humanos + 20 IA.gentes + 3x + 0 demissão) | "Por isso criei a Imersão H.AI..." |
| 4 | PROVA | 3:00–5:00 | 4 bullets do que aprende (IA.gentes, S.E.R, plano 90d, sessão 1:1) | "Você vai aprender a construir..." |
| 5 | PREÇO | 5:00–6:30 | De R$1.497 por R$697 (ou 12× R$67) | "Uma hora com consultor C-Level custa R$800..." |
| 6 | URGÊNCIA | 6:30–7:30 | "A Sessão 1:1 é feita por mim. Não por assistente." | "As vagas são limitadas..." |
| 7 | CTA | 7:30–FIM | "Clica no botão. Me manda um oi. Vamos marcar." + botão CTA dourado | "Te espero do outro lado..." |

**VSL não tem imagens reais embedadas** — só CSS gradient nos mockups. Se quiser, próxima sessão pode fazer imagens específicas também.

---

## 🏗️ CSS ARCHITECTURE (referência pra próxima sessão)

### Variáveis
```css
--gold:#C5A572; --gold-light:#E8D5B0;
--violet:#6B2D8B; --violet-mid:#8B5CB8;
--navy:#0D1847; --bg:#070514; --surface:#0f0c24;
```

### Fontes
- Headings: **Outfit** (500-900)
- Body: **Inter** (300-900)

### Classes de slide visual (gradientes)
- `.sv-cover` — radial navy → dark purple (para capa)
- `.sv-hook` — linear navy-to-dark (para perguntas)
- `.sv-data` — linear navy-blue-to-dark (para dados/timeline)
- `.sv-ruptura` — radial orange hint → dark (para disrupção)
- `.sv-insight` — linear dark purple (para insights)
- `.sv-question` — radial center glow → dark (para reframes)
- `.sv-cta` — radial gold hint → dark (para encerramentos/CTAs)
- `.bg-grid-slide` — linhas sutis de grid 48px

### Padrão de imagem embedada
Inserir como PRIMEIRO filho do div `.sv-XXXX`:
```html
<div style="position:absolute;inset:0;
  background-image:url('assets/aula1/slideX-nome.png');
  background-size:cover;
  background-position:center;
  mix-blend-mode:screen;        /* ou remover pra foto de cena */
  opacity:0.X;                  /* 0.22–0.7 dependendo da imagem */
  pointer-events:none;
  z-index:0">
</div>
```

**Regras de opacity:**
- Screen blend + imagem dourada em fundo preto = `0.5–0.7` (bem visível, efeito glow)
- Screen blend + imagem mista = `0.4–0.5`
- SEM blend + foto realista = `0.15–0.25` (foto como ambiente, texto precisa ficar legível)

---

## ⚙️ WORKFLOW / REGRAS IMPORTANTES

### Aprovação iterativa
Rodrigo disse na sessão anterior:
> "monte a estrutura e os componentes da aula 1 - apos minha avaliacao, vc vai para a 2."

**Regra:** Cada aula precisa aprovação individual antes de partir pra próxima.

### Formato dos slides
Rodrigo corrigiu uma vez:
> "adorrei, mas eu preciso que o na tela, seja slides reais mesmo, para eu ir passando e apresentando sem mostrar mais nada... o que falar e detalhes ficam ocultos so para eu estudar"

**Regra:** Slideshow REAL (um slide por vez), notes drawer OCULTO por padrão, modo fullscreen pra apresentação.

### Estilo PulsarH
- Dark backgrounds (#070514, #0D1847)
- Dourado (#C5A572) como highlight
- Violeta (#6B2D8B) como secundário
- Fontes: Outfit (headings) + Inter (body)
- Glass cards, gradient dividers, grid overlay sutil
- SEM emojis exceto em dicas de produção (💡)

### Tom de voz (Rodrigo)
- Direto, confiante, "cara que virou o jogo"
- Usa "chefe" ao se referir ao aluno/espectador? NÃO — isso é interno da Pulse
- Linguagem: "tsunami", "empresário médio", "inércia do sucesso", "3x mais", "2 humanos + 20 IA.gentes", "zero demissão"

---

## 📚 CONTEÚDO DAS PRÓXIMAS AULAS (do imersao-hai-briefing.html)

### MÓDULO 1 · A RUPTURA (4 aulas)
- ✅ **Aula 1 · A Tsunami da IA** (feita, falta trocar imagens)
- ⏳ **Aula 2 · A Nova Geração** — quem está prosperando (CEOs novos, empresas enxutas, padrão aprendível)
- ⏳ **Aula 3 · A Síndrome do Empresário Médio** — os 5 vícios que matam (ex: achar que "tempo resolve", delegação disfuncional, medo de demissão)
- ⏳ **Aula 4 · Demitir é Cilada** — por que cortar pessoal não é a resposta; a resposta é AMPLIFICAR

### MÓDULO 2 · DNA DO LÍDER HÍBRIDO (5 aulas — uma por dimensão)
- ⏳ Aula 5 · **Conector** (pontes humanas + tech)
- ⏳ Aula 6 · **Hiperprodutivo** (alavancas, delegação radical)
- ⏳ Aula 7 · **Humilde** (ego é o inimigo, aprendizado contínuo)
- ⏳ Aula 8 · **Sistêmico** (pensar em processos, não em tarefas)
- ⏳ Aula 9 · **Humano** (cuidado genuíno, presença)

### MÓDULO 3 · IA.GENTES (4 aulas)
- ⏳ Aula 10 · A Era dos IA.gentes (o que é, por que é diferente de chatbot)
- ⏳ Aula 11 · Os 4 Tipos (Secretário / Executor / Conselheiro / Autor)
- ⏳ Aula 12 · Anatomia do Prompt (framework de criação)
- ⏳ Aula 13 · Erro Nº1 (tentar automatizar processo quebrado)

### MÓDULO 4 · TRAZER A TRIBO (S.E.R — 3 aulas)
- ⏳ Aula 14 · **Sensibilizar** (como abrir a conversa sem gerar medo)
- ⏳ Aula 15 · **Engajar** (co-criar com o time)
- ⏳ Aula 16 · **Respeitar/Educar** (formar o time, não impor)

### MÓDULO 5 · PULSAR+H (5 aulas + bônus)
- ⏳ Aula 17 · **Planejar** (mapa antes do código)
- ⏳ Aula 18 · **Usar** (executar com ferramentas certas)
- ⏳ Aula 19 · **Lapidar + Sustentar** (iterar e manter)
- ⏳ Aula 20 · **Alavancar + Replicar** (escalar padrões)
- ⏳ Aula 21 · **+H Humanização** (nunca perder o humano)
- ⏳ Aula 22 · **10 Mandamentos** (os 10 do Rodrigo)
- ⏳ Aula 23 · **Pitch Final** (como apresentar a transformação pra o time/cliente)

**Cada aula:** ~5-8 slides + roteiro por slide + dicas de produção.

---

## 🖥️ PREVIEW SERVER

Config em `C:\Sistemas\.claude\launch.json`:
```json
{
  "name": "Slides HAI",
  "runtimeExecutable": "npx",
  "runtimeArgs": ["serve", "LandingPage/Landingpage_segundarevolucao", "-p", "7788", "--no-clipboard"],
  "port": 7788
}
```

URL: `http://localhost:7788/imersao-hai-slides.html`

Preview MCP tools:
- `mcp__Claude_Preview__preview_start` (name: "Slides HAI")
- `mcp__Claude_Preview__preview_screenshot`
- `mcp__Claude_Preview__preview_eval` (rodar JS no browser)
- `mcp__Claude_Preview__preview_resize` (ex: width 1440, height 900)

### JavaScript interno do slideshow (pra debugging)
- `goTo('show-1', idx)` — navegar pra slide X (0-indexed)
- `slideNav('show-1', dir)` — +1 / -1
- `enterFS('show-1')` — entrar fullscreen
- `exitFS()` — sair fullscreen
- `fsNav(dir)` — navegar em fullscreen
- `toggleNotes('notes-1', 'toggle-1')` — abrir/fechar drawer
- `jumpRot(1, idx)` — pular pra roteiro do slide X

---

## 🎯 PRÓXIMOS PASSOS (ordem)

### 1. Trocar as 4 imagens (PRIORIDADE MÁXIMA)
Rodrigo vai re-enviar as 4 imagens corretas do Maurício. Salvar em:
- `assets/aula1/slide1-capa.png` ← ondas douradas circuito
- `assets/aula1/slide3-timeline.png` ← industrial revolution
- `assets/aula1/slide4-tsunami.png` ← tsunami subaquático digital
- `assets/aula1/slide5-diagnostico.png` ← empresário 2015 vs 2026

Sobrescrever sem mudar HTML.

### 2. Ajustar opacity/blend-mode se preciso
Pra imagem 3 (tsunami subaquático) que é MUITO rica e colorida, pode valer:
- Remover `mix-blend-mode: screen` (mantém as cores originais)
- `opacity: 0.35-0.50` (visibilidade controlada)

Pra imagem 2 (empresário 2015 vs 2026) que é a narrativa PRINCIPAL do slide 5:
- Sem blend mode
- `opacity: 0.40-0.55` (deixar bem visível, é a âncora visual)
- Talvez até sem nenhum overlay (mostrar a imagem inteira como hero)

### 3. Aprovar Aula 1 definitivamente
Rodrigo abre no Chrome, apresenta do início ao fim no modo fullscreen, valida:
- Ritmo dos slides
- Roteiro batendo com slides
- Imagens funcionando em tela cheia

### 4. Construir Aula 2
Mesma estrutura (~5-8 slides + roteiro + dicas). Source content: `imersao-hai-briefing.html` seção Aula 2.

### 5. Iterar Aulas 3-23
Após cada aprovação.

---

## 💾 CONTEXTO DA INFRAESTRUTURA PULSAR (refresh)

- **VPS:** 72.60.6.61 (Hostinger Ubuntu)
- **Tmux sessions:** `pulsarh` + `donna` (Claude Code 24/7)
- **War Room:** `https://sala-de-guerra-pulsar-h.vercel.app`
- **DB:** PostgreSQL na VPS (pulsarh_war_room)
- **Bots Telegram:** @Pulseh_bot + @Donnah1_bot (chat: 8734094117)
- **Pessoas (subagents):** Pulseh (CEO), Donna (sec), Alfredo (VP comercial), Flavia (VP produtos), Simon (VP RH+IA.gentes), Falconi (VP Ops), Dalio (VP Financeiro)
- **Heads relevantes pra este trabalho:**
  - **Maurício** (Alfredo) — design/visual, prompts de imagem
  - **Betina** (Alfredo) — copy
  - **Clovis** (Flavia) — conteúdo didático/andragogia
  - **Ladeira** (Flavia) — naming/empacotamento comercial

---

## 📝 HISTÓRICO DE DECISÕES DESTA SESSÃO

1. **Sessão anterior comprimida** — Donna ficou com 6 memórias salvas no PostgreSQL antes de reiniciar (agentId: `cmnn7pqiw00014pqkigf5t2x5`)
2. **VPS lenta** — causada por Donna tmux session de 2 dias (context window bloat). Solução: memory compaction + restart (pendente do lado do Rodrigo ou Pulse)
3. **Formato dos slides decidido** — Formato C (visual + roteiro), slideshow real com fullscreen + notes drawer oculto
4. **Aula 1 construída** com 7 slides + roteiro completo + storyboard VSL de 7 momentos
5. **Imagens erradas embedadas** — eu peguei 4 arquivos Gemini aleatórios ao invés das 4 imagens corretas do Maurício que Rodrigo gerou
6. **Rodrigo avisou** — precisa trocar pelas imagens corretas que anexou na última mensagem

---

## 🗣️ CITAÇÕES EXATAS DO RODRIGO (pra tom de voz)

- "nao quero que ela perca contexto. compacte o contexo e salve na memoria dela."
- "monte a extreutura e os componentes da aula 1 - apos minha avaliacao, vc vai para a 2."
- "perfeito - quero: 1 - C / 2 - livre, mas quero elegancia, quero padrao pulsar - chame mauricio, quero imagens..."
- "crie um capa com as caixas de cada modulo e cada aula - na caixa da aula, roteiro que devo falar que condiz com a apostila..."
- "adorrei, mas eu preciso que o na tela, seja slides reais mesmo, para eu ir passando e apresentando sem mostrar mais nada"
- "dentro do workspace do pulse tem o token... se quiser use mcp e gere as imagens no flow... ou melhor ainda, me manda o prompt do mauricio eu gero e te mando..."
- "segue imagens" [anexou 4 imagens corretas do Maurício]
- **"eu gerei as imagens do Mauricio mas vc esta usando outras..."** [correção atual — eu vacilei]
- "preciso que salve o contextos que tem dessa nossa conversa num arquivo .md completo - robusto e detalhado"

---

## ⚡ COMANDO DE RETOMADA (pra próxima sessão)

Começar a próxima sessão com:

```
Lê C:\Sistemas\LandingPage\Landingpage_segundarevolucao\CONTEXTO-IMERSAO-HAI-SLIDES.md completo.
Estamos na Imersão H.AI. Aula 1 feita mas com imagens erradas. Me peça as 4 imagens corretas do Maurício, ou verifique em Downloads os arquivos mais recentes. Substitua em assets/aula1/*.png e abra no browser (preview MCP "Slides HAI" porta 7788) pra eu validar. Depois parto pra Aula 2.
```

---

*Salvo em 21/04/2026 · Sessão lenta forçou dump de contexto · Próxima sessão retoma daqui.*
