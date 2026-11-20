# Registro de Uso de Inteligência Artificial Generativa

**Projeto Integrador — Amazonas Leilão**  
**Entregas documentadas:** Entrega 1 — HTML estrutural. Entrega 2 — CSS e responsividade.

Neste registro, documentamos como utilizamos a IA generativa no projeto.

## 1. Mapeamento do uso de IA e da nossa participação

| Etapa | Apoio da inteligência artificial | **Modificações e ajustes realizados** |
|---|---|---|
| Prototipagem e HTML inicial | Apoio à produção de textos e imagens e geração inicial das quatro páginas HTML com base no protótipo visual. | **Elaboramos o protótipo no Figma, definimos o conceito, revisamos o conteúdo e organizamos os arquivos.** |
| Entrega 1 — HTML | Refatoração semântica dos quatro arquivos HTML e adaptação da proposta e dos textos ao contexto do projeto. | **Definimos o escopo, simplificamos a estrutura, ajustamos os textos e revisamos os elementos e caminhos.** |
| Adequação de imagens | Geração/substituição das imagens e atualização de `src`, `alt` e `figcaption`. | **Identificamos animais inadequados ao contexto, solicitamos substituições e revisamos os textos e as imagens.** |
| Entrega 2 — CSS | Geração inicial de `css/style.css`, com Flexbox, Grid, variáveis CSS e media queries. | **Ajustamos manualmente cores, tamanhos de fonte, posições e alinhamentos e dividimos o CSS em arquivos por página.** |
| Organização e verificação | Apoio na geração e na refatoração do código, sem substituir a conferência humana. | **Reorganizamos as pastas e validamos os quatro arquivos HTML no W3C Markup Validation Service sem avisos.** |
| Formulário de candidatura | Inclusão do formulário e dos estilos responsivos na seção Candidaturas, com validação nativa do HTML5. | **Definimos os campos, o botão e os requisitos de layout e validação. Pedimos que o formulário não enviasse dados.** |

## 2. Histórico cronológico: prompts, resultados da IA e intervenções manuais

A sequência abaixo separa três elementos em cada etapa: o que foi pedido, o que a IA entregou e o que decedimos, corrigimos e modificamos.

### 2.1. Criação inicial do HTML com base no Figma

**Nossa orientação à IA:** pedimos que a IA desenvolvesse o HTML das quatro páginas com base no protótipo que elaboramos no Figma.

**Resultado da IA:** geração inicial da estrutura HTML do projeto, baseada no desenho das páginas elaborado no Figma.

**NOSSAS ALTERAÇÕES E DECISÕES:**
- **Criamos o protótipo no Figma**, que orientou o desenvolvimento e as escolhas visuais.
- **Revisamos e adaptamos textos e imagens** para manter o conteúdo de acordo com o contexto do trabalho.
- **Reorganizamos a estrutura e a arquitetura das pastas**, buscando facilitar a leitura e a manutenção do projeto.

### 2.2. Prompt 1 — Refatoração geral do HTML e alinhamento à IN IBAMA nº 19/2014

**Prompt original fornecido à IA:**

**Contexto e Objetivo:**

Preciso refatorar os arquivos HTML de um projeto integrador acadêmico (desenvolvido com base no edital em anexo) para ajustar o tema de forma 100% legal e alinhada à **Instrução Normativa nº 19/2014 do IBAMA**.

**Mudança Conceitual Obrigatória:**

O site **Amazonas Leilão** não é um e-commerce livre ou leilão comercial de animais silvestres. Ele deve ser retratado como uma **empresa fictícia terceirizada pelo IBAMA** para realizar leilões e destinações administrativas de animais apreendidos cuja soltura imediata na natureza seja inviável. Os lotes e arremates são restritos estritamente a **estruturas regularizadas com técnicos habilitados e infraestrutura adequada** (como zoológicos, mantenedouros e criadouros autorizados).

**Escopo da Refatoração (Mínimo e Simplificado):**

- Manter exatamente as 4 páginas padrão: `index.html`, `login.html`, `sobre.html` e `trabalhe-conosco.html` (sendo esta última a área de formulários/candidaturas).
- **Não incluir CSS** (o estilo será gerado posteriormente).
- **Não incluir scripts de back-end**, mantendo a validação estritamente nativa do HTML5 onde houver formulários.
- Seguir rigorosamente a semântica exigida pelo edital do projeto integrador (landmarks semânticos corretos, hierarquia de headings única por página, tags `lang`, `alt` em imagens e link de salto para o conteúdo).
- Atualizar os textos e descrições dos lotes na `index.html`, os avisos de restrição e habilitação prévia na `login.html`, e a proposta institucional na `sobre.html` para refletirem o modelo de destinação do IBAMA.

**Instrução de Execução:**

Antes de gerar o código final dos arquivos, por favor, **faça-me perguntas ou tire dúvidas** caso precise de algum alinhamento sobre a estrutura ou o conteúdo específico de cada página.

**Nosso complemento ao Prompt 1 (texto original):**

não gere o CSS e o Formulario por hora.

analise todos os arquivos em anexo para referencia antes de tirar as duvidas.

**Nossas respostas às perguntas de alinhamento da IA (texto original):**

1 - segunda opção, servindo de base para o layout em anexo
2- mantenha
3- login possui só email e senha, pode manter, o formulario completo que será posterior
4- pode
mantenha o html o mais simples possivel que ainda atenda aos requisitos pedidos por prompt e informados na orientação

**RESULTADO ENTREGUE PELA IA:**
- Refatoração de `index.html`, `login.html`, `sobre.html` e `trabalhe-conosco.html` com **HTML simples e sem CSS**, conforme solicitado para a primeira entrega.
- Diferenciação entre destinações administrativas e leilões no conteúdo do site.
- Preservação inicial dos animais e imagens existentes.
- Manutenção do login somente com e-mail e senha e validação nativa do HTML5.
- Manutenção da página de vagas sem o formulário completo de candidatura, adiado para etapa posterior.
- Estrutura com `header`, `main`, `aside` e `footer` preparada para posterior aplicação de estilos; revisão de títulos, links, imagens, acessibilidade estrutural e acentuação.

**NOSSAS ALTERAÇÕES E DECISÕES:**
- **Determinamos a separação das entregas**, adiando deliberadamente CSS e formulário completo para etapas posteriores.
- **Escolhemos manter o HTML simples**, atendendo à semântica e aos requisitos do edital, sem complexidade desnecessária.
- **Revisamos manualmente o conteúdo textual** e identificamos a necessidade de melhorar a seleção dos animais exibidos, o que motivou o segundo prompt.

### 2.3. Prompt 2 — Adequação de animais, imagens e textos

**Prompt original fornecido à IA:**

Fiz algumas alterações nos textos do projeto, não é necessário falar que tudo é ficticio, já é subentendido isso. Agora sobre os animais, faça alterações, pavao, galinha sedosa e etc não são apreensoes recorrentes do ibama. gere as novas imagens no padrao das anteriores, e faça a alteração no caminho, alt e etc para adequar os novos animais no html

**RESULTADO ENTREGUE PELA IA:**
- Substituição das imagens referentes aos animais considerados inadequados à proposta apresentada.
- Geração de novas imagens seguindo o padrão visual das anteriores.
- Atualização dos caminhos das imagens nos atributos `src` e de suas descrições alternativas em `alt`.
- Atualização de legendas em `figcaption`, quando existentes, para corresponder aos novos animais.

**NOSSAS ALTERAÇÕES E DECISÕES:**
- **Já havíamos realizado mudanças manuais nos textos** antes de enviar o prompt, ajustando a comunicação do projeto.
- **Identificamos o problema de coerência temática** em animais como pavão e galinha sedosa e orientamos a substituição por exemplos mais compatíveis com o contexto proposto.
- **Revisamos a correspondência entre conteúdo, imagem, descrição alternativa e legenda** para garantir que comunicassem a mesma informação.

### 2.4. Prompt 3 — Criação da folha de estilos CSS e responsividade

**Prompt original fornecido à IA:**

**Contexto e Objetivo:** Preciso que você crie a estrutura de arquivos e o código CSS customizado para o projeto integrador **Amazonas Leilão** (plataforma institucional de leilão administrativo de animais apreendidos em parceria com o IBAMA).

**Organização de Pastas e Arquivos:**

- Crie uma pasta dedicada para os arquivos HTML (ex: `/pages` ou manter na raiz limpa) e uma nova pasta `/css` contendo o arquivo de estilos (ex: `style.css`).

**Regras Técnicas e de Layout Obrigatórias:**

1. **Proibição de Frameworks:** É estritamente proibido o uso de Bootstrap, Tailwind, Bulma ou qualquer framework pronto. Todo o CSS deve ser escrito do zero.
2. **Sistemas de Layout:**
   - Utilizar **Flexbox** obrigatoriamente para a estruturação e alinhamento do `<header>` (e itens de navegação).
   - Utilizar **CSS Grid** obrigatoriamente para a estruturação do `<main>` / `<body>` (distribuição de seções, lotes e áreas principais).
3. **Responsividade (3 Breakpoints Obrigatórios):**
   - Mobile (até ~480px)
   - Tablet (~768px)
   - Desktop (~1200px+)
4. **Acessibilidade e Contraste:**
   - Garantir um contraste mínimo de cor de **4.5:1** entre o texto e o fundo (em conformidade com o WebAIM Contrast Checker).

**Cuidados Técnicos Críticos a Serem Respeitados:**

- **Evite aplicar Flex/Grid no elemento pai incorreto** (verifique a árvore de elementos antes de definir o container).
- **Não insira propriedades de `padding` ou espaçamentos inadequados em elementos do tipo link inline** (`<a>` simples sem bloco).
- **Não deixe itens vazios ou sem área definida** nas malhas do Grid (`grid-template-areas` ou colunas definidas).
- Utilize as referências visuais de cores apenas como inspiração estética, garantindo que o padrão estrutural e semântico siga rigorosamente o escopo do anexo da SATEC

**Instrução de Execução:** Gere o código CSS limpo, modularizado (com variáveis `--custom-properties` no `:root`), com os seletores organizados e os `@media queries` para os 3 breakpoints solicitados.

**RESULTADO ENTREGUE PELA IA:**
- Criação do diretório `css` e de uma única folha `css/style.css`, vinculada às quatro páginas HTML.
- Uso de CSS próprio, sem frameworks, com variáveis centralizadas em `:root`.
- Aplicação de **Flexbox** ao cabeçalho e à navegação e de **CSS Grid** às áreas principais e aos cartões.
- Inclusão de media queries referentes às larguras de 480 px, 768 px e 1200 px.
- Implementação de indicadores de foco visível; a resposta da IA informou contraste calculado acima de 4,5:1.
- A IA relatou ter conferido a organização e o carregamento dos arquivos, **mas não realizou teste visual nas três larguras**, pois o navegador de prévia estava indisponível.

**NOSSAS ALTERAÇÕES MANUAIS APÓS A ENTREGA DA IA:**
- **Separamos o `style.css` compartilhado em arquivos de CSS específicos para cada página**, organizando-os em uma estrutura modular. Isso evita que mudanças em uma página afetem desnecessariamente as demais.
- **Modificamos manualmente a paleta de cores e os tamanhos de fonte** para melhorar a correspondência com o protótipo do Figma e a hierarquia visual.
- **Reposicionamos elementos, ajustamos alinhamentos e espaçamentos**, corrigindo diferenças entre o resultado inicial e o layout pretendido.
- **Reorganizamos pastas e referências de arquivos**, buscando facilitar futuras manutenções.

### 2.5. Nossa conferência dos arquivos HTML

**NOSSA VALIDAÇÃO:** Submetemos os quatro arquivos HTML ao [W3C Markup Validation Service](https://validator.w3.org/) e **obtivemos resultados sem avisos**.

### 2.6. Prompt 4 — Formulário de candidatura na página Trabalhe Conosco

**Prompt original fornecido à IA**

Na página **Trabalhe Conosco**, localize a `<section>` chamada `candidaturas` e adicione um formulário simples para envio de candidaturas.

O formulário deve conter:

- **Nome completo:** campo de texto obrigatório.
- **E-mail:** campo do tipo `email`, obrigatório.
- **Vaga pretendida:** campo de texto obrigatório.
- **Botão:** "Enviar candidatura".

**Requisitos:**

- Utilizar exclusivamente **HTML5 e CSS3 puro**, sem JavaScript, frameworks ou bibliotecas externas.
- Manter o padrão visual, as cores, fontes e o estilo já utilizados no projeto.
- Criar um layout limpo, organizado e responsivo.
- Utilizar tags semânticas e associar corretamente os `labels` aos campos.
- Utilizar a validação nativa do HTML5.
- Não modificar outras seções ou funcionalidades da página.
- Não implementar backend ou lógica de envio. O formulário deve ser apenas visual e estrutural, sem simular o envio da candidatura.

**RESULTADO ENTREGUE PELA IA**

- Inclusão do formulário na seção Candidaturas, identificada no HTML pelo ID `candidatura`, em `paginas/trabalhe-conosco.html`.
- Associação dos rótulos aos três campos obrigatórios e uso do tipo `email` para a validação nativa.
- Uso de `method="dialog"` fora de um elemento `<dialog>` para que o botão acione a validação sem transmitir dados.
- Estilos responsivos em `paginas/trabalhe-conosco.css`, restritos à seção e baseados nas cores, na tipografia e nos espaçamentos do projeto.
- Conferência do HTML e do CSS nos arquivos. O teste em navegador ficou pendente. A validação W3C registrada no item 2.5 ocorreu antes desta alteração.



## 3. Revisão técnica — modificações manuais e justificativas

Os itens abaixo sintetizam as intervenções descritas no fluxo e apresentam o formato exigido pelo edital: **o que a IA gerou / o que alteramos / por que fizemos a alteração**.

### 3.1. Reorganização da arquitetura e das pastas

- **O que a IA gerou:** páginas HTML e a estrutura inicial de diretórios, com uma folha de estilos CSS compartilhada na etapa de estilos.
- **Reorganizamos manualmente a disposição das pastas e dos arquivos, incluindo a forma de separar os estilos.**
- **Justificativa técnica:** tornar a estrutura mais clara, facilitar a localização de recursos e melhorar a manutenção.

### 3.2. Separação do CSS por página

- **O que a IA gerou:** **um único `css/style.css` para as quatro páginas**, com regras compartilhadas.
- **Criamos arquivos de CSS próprios para cada página e organizamos os estilos de forma modular**.
- **Justificativa técnica:** diminuir o risco de uma modificação visual interferir em outras páginas e facilitar correções específicas.

### 3.3. Personalização das cores e da tipografia

- **O que a IA gerou:** definições iniciais de cores, fontes e tamanhos das letras.
- **Ajustamos manualmente cores e tamanhos de fonte**.
- **Justificativa técnica:** aproximar o resultado do protótipo no Figma e melhorar a hierarquia visual e a legibilidade.

### 3.4. Reposicionamento de elementos e alinhamentos

- **O que a IA gerou:** layout inicial das seções e componentes por meio de regras de Flexbox e CSS Grid.
- **Corrigimos manualmente posições, alinhamentos e espaçamento de elementos da interface.**
- **Justificativa técnica:** corrigir diferenças de composição em relação ao layout pretendido e organizar melhor a ocupação do espaço.

### 3.5. Revisão e adequação do conteúdo textual e visual

- **O que a IA gerou:** conteúdo textual inicial e imagens, posteriormente atualizadas com apoio da própria IA.
- **Editamos manualmente os textos, identificou animais inadequados e verificou a adequação de imagens e descrições**.
- **Justificativa técnica:** manter consistência entre a proposta institucional do projeto, o conteúdo exibido e os elementos de acessibilidade das imagens.

## 4. Observações sobre o registro

- **Autoria e revisão:** utilizamos IA na produção inicial e na refatoração. Elaboramos o protótipo, definimos o escopo, revisamos os resultados e fizemos as alterações manuais descritas.
- **Prompts completos disponíveis:** os quatro prompts transcritos acima, seus complementos e as respostas de alinhamento foram mantidos no teor fornecido.
- **Limite das verificações:** a aprovação dos HTML foi realizada no validador W3C, os testes visuais em diferentes larguras e visualização dos arquivos foram utilizados as seguintes ferramentas:
extensão Live Code, navegador Chrome, Figma, Codex.

