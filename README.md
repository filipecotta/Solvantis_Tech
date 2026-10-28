# Solvantis Tech

Site institucional e de orçamentos da **Solvantis Tech**, empresa fictícia criada para a disciplina de Redes de Computadores. O foco é atender empresas que precisam de serviços de redes: cabeamento, infraestrutura, segurança, Wi-Fi e suporte técnico.

## Sobre o projeto

O site apresenta os serviços da empresa e permite que o cliente monte um orçamento escolhendo serviços e quantidades. A lista é enviada pelo WhatsApp ou por e-mail com a mensagem já preenchida, sem servidor nem banco de dados.

## Contato configurado

| Canal | Dado |
|---|---|
| WhatsApp | (31) 98906-0446 |
| E-mail | filipegabi13@gmail.com |
| Atendimento | Segunda a sexta, 8h às 18h |

## Funcionalidades

- Página inicial com a logo, a proposta da empresa e uma faixa com os padrões usados (Cat6/Cat6A, NBR 14565, fibra óptica, Wi-Fi 6/6E, PoE, VLAN/firewall/VPN)
- 9 serviços organizados em 3 grupos, com valores de referência de mercado
- Painel lateral de orçamento com quantidades e estimativa de valor
- Envio do orçamento por WhatsApp ou e-mail
- Seção "O que entregamos na prática", com a parte técnica de cada serviço
- Seção "Como trabalhamos" com as 5 etapas do atendimento
- Seção de diferenciais da empresa
- Perguntas frequentes (FAQ)
- Formulário de contato que envia por WhatsApp ou e-mail
- Botão flutuante de WhatsApp
- Layout responsivo, funciona em celular e computador

## Animações e novos botões (versão atual)

**Serviços redesenhados como painéis de rack**
- Cada serviço é um painel de equipamento com ícone próprio, LEDs piscando e uma fileira de 8 portas que acendem em sequência ao passar o mouse.
- Uma linha de luz percorre o topo do card no hover. O card selecionado fica com borda em destaque e todas as portas acesas.
- Os títulos dos grupos têm um LED de status ao lado.

**Botões no padrão atual do mercado de redes**
- Botões em formato pill com seta (chevron) que desliza no hover e brilho que varre o botão.
- Textos de ação: "Solicitar proposta", "Falar com especialista" e "Agendar visita técnica".
- "Adicionar à proposta" virou um **interruptor (toggle)** que muda para "Na proposta".
- O botão do cabeçalho passou de "Orçamento" para "Proposta", e o botão do WhatsApp ganhou pulso.

**Animações pelo site**
- Topologia do topo com anéis girando, nós pulsando e pacotes de dados em todos os enlaces.
- Indicador "Rede ativa" com LED verde e latência que varia em tempo real (é um efeito decorativo, não uma medição).
- Linha de varredura (scan) passando pelo topo, logo flutuando e barra de progresso de rolagem no cabeçalho.
- Contagem animada nos números da faixa de especificações.
- Entrada suave dos blocos ao rolar a página, com atraso escalonado.
- Na arquitetura, um pacote de luz percorre as 5 camadas e cada nó pulsa.
- Na metodologia, a linha das etapas se desenha ao aparecer.
- Nos setores, uma linha cresce no hover. Nas dúvidas, a resposta abre com efeito suave.
- Faixa de chamada com fundo em movimento e botão pulsando.
- Quem usa "reduzir movimento" no sistema vê o site sem animações.
- No celular, o texto do topo agora vem antes da topologia.

## Redesign visual anterior (versão "grande empresa de redes")

Nesta versão o site foi redesenhado para ter a aparência de uma empresa grande de infraestrutura. A lógica do orçamento, os preços e os dados de contato foram mantidos.

- **Barra superior** com WhatsApp e e-mail sempre à vista.
- **Topo (hero)** com fundo em grade técnica e uma **topologia de rede animada** desenhada em SVG, com a logo no centro e pacotes de dados percorrendo os enlaces. A animação é desligada para quem prefere movimento reduzido.
- **Faixa de especificações:** 10 Gbps de backbone, Wi-Fi 6E, meta de 99,9% de disponibilidade e 100% dos pontos certificados.
- **Soluções em grade:** os 9 serviços aparecem em cards lado a lado, agrupados em 3 categorias, com preço em destaque.
- **Arquitetura da borda ao usuário:** linha com as 5 camadas da rede (links de internet, firewall e VPN, núcleo, acesso e Wi-Fi, dispositivos).
- **Setores atendidos:** escritórios, saúde, educação, comércio, indústria e condomínios, cada um com a necessidade típica da área.
- **Metodologia**, **Por que a Solvantis** (grade 2x2) e **Dúvidas frequentes** reorganizados.
- **Faixa de chamada para ação** em destaque antes do formulário de contato.
- **Rodapé em colunas** (soluções, empresa, contato).
- Menu atualizado: Soluções, Arquitetura, Setores, Metodologia e Contato.

As especificações da faixa são metas e padrões de serviço, não números de clientes. Se tiver dados reais (clientes atendidos, anos de mercado, certificações), troque os textos da seção `class="stats"`.

## O que foi alterado na versão anterior

### Contato
- Número de WhatsApp trocado de `5531900000000` para `5531989060446`, em todos os pontos do site (script, botão flutuante e seção de contato).
- E-mail `contato@solvantis.tech` substituído por `filipegabi13@gmail.com`, agora como link `mailto:`.
- O telefone e o e-mail da seção de contato viraram links clicáveis.

### Serviços e preços
- Serviços passaram de 7 para 9, agrupados em **Instalação e rede física**, **Wi-Fi, segurança e vídeo** e **Manutenção e suporte**.
- Novos serviços: **Fibra óptica** e **Monitoramento e backup**.
- Nomes e descrições ajustados: "Roteador, firewall e VPN" virou "Firewall, VLAN e VPN"; "Rede para câmeras de segurança" virou "CFTV em rede (câmeras IP)".
- Preços revisados para valores mais próximos do mercado, sempre de mão de obra e configuração. Materiais e equipamentos são orçados à parte, e o site avisa isso.
- O aviso sob a lista de serviços agora explica o que influencia o preço final (distância, tipo de forro, tamanho do ambiente).

### Orçamento
- Serviços cobrados por unidade (ponto, access point, câmera, máquina) ganharam botões para aumentar e diminuir a quantidade.
- O painel mostra o total estimado, separando **serviços pontuais** de **mensalidade**, com aviso de que é estimativa mínima.
- A mensagem enviada inclui as quantidades (exemplo: "Cabeamento estruturado Cat6/Cat6A: 12 ponto(s)").
- O painel passou a pedir também o nome da empresa e ganhou o botão de envio por e-mail.
- Painel com rolagem, para funcionar bem em telas pequenas.

### Conteúdo novo
- Faixa de padrões e tecnologias logo abaixo da página inicial.
- Seção **O que entregamos na prática** com 6 blocos: cabeamento certificado, Wi-Fi com projeto, segmentação e segurança, fibra e links redundantes, CFTV em rede, monitoramento e backup.
- Etapas de "Como trabalhamos" reescritas com entregas concretas (medição do ambiente, lista de materiais, execução fora do horário de pico, relatório e documentação).
- Diferenciais reescritos e ampliados para 4: relatório de certificação, documentação completa, suporte com prioridade e segurança/LGPD.
- Seção de **Dúvidas frequentes** com 5 perguntas: custo do ponto de rede, Cat6 x Cat6A, Wi-Fi profissional x roteador comum, parada da operação durante a instalação e o que o suporte mensal inclui.
- Textos da página inicial e do rodapé atualizados (escritórios, clínicas, escolas e comércios; "suporte de TI").

### Formulário de contato
- Novo campo **Tipo de empresa** (escritório, clínica, escola, comércio, indústria, condomínio ou outro).
- Novo botão **Enviar por e-mail**, além do WhatsApp.
- Campo de mensagem com exemplo de preenchimento.

### Navegação e visual
- Menu com os novos itens **Tecnologia** e **Dúvidas**.
- Botão flutuante de WhatsApp no canto da tela.
- Identidade visual mantida: cores, fontes Michroma e Manrope, e logo.

### Busca e acessibilidade
- Título e descrição da página reescritos com os termos que as empresas procuram (cabeamento estruturado, fibra, Wi-Fi corporativo, firewall, CFTV IP).
- Dados estruturados (`schema.org`) com nome, telefone, e-mail e horário de atendimento.
- Foco visível no teclado, tecla Esc fecha o painel e animações respeitam a preferência de movimento reduzido.

## Serviços oferecidos

| Serviço | Valor de referência |
|---|---|
| Cabeamento estruturado Cat6/Cat6A | R$ 180 por ponto |
| Fibra óptica | a partir de R$ 1.200 |
| Infraestrutura de rede | a partir de R$ 1.500 |
| Wi-Fi corporativo | R$ 650 por access point |
| Firewall, VLAN e VPN | a partir de R$ 900 |
| CFTV em rede (câmeras IP) | R$ 280 por câmera |
| Manutenção de computadores | R$ 120 por máquina |
| Suporte técnico mensal | a partir de R$ 890 por mês |
| Monitoramento e backup | a partir de R$ 390 por mês |

Valores de referência de mão de obra e configuração; materiais e equipamentos são orçados à parte. Ajuste conforme a sua realidade.

## Tecnologias

- HTML5
- CSS3 (variáveis CSS, grid e flexbox)
- JavaScript puro, sem frameworks nem bibliotecas
- Fontes Michroma e Manrope, carregadas do Google Fonts

## Como usar

1. Baixe o arquivo `solvantis-tech.html`.
2. Dê dois cliques nele para abrir no navegador.

Tudo está em um único arquivo e a logo já vem embutida. Para as fontes aparecerem como no projeto, é preciso estar conectado à internet. Sem conexão, o site usa fontes padrão do sistema.

## Como personalizar

**WhatsApp e e-mail.** No final do arquivo, procure as linhas abaixo. O número usa 55 + DDD + número. Troque também os links da seção `id="contato"` e do botão flutuante (`class="wa"`).

```js
var WA="5531989060446",EM="filipegabi13@gmail.com";
```

**Serviços e preços.** No início do script, edite a lista `G`. Cada serviço segue o formato: nome, descrição, valor, texto de cobrança, tipo e unidade.

```js
["Cabeamento estruturado Cat6/Cat6A","Descrição.",180,"por ponto","q","ponto(s)"],
```

Tipos: `q` = cobrado por quantidade (aparecem os botões + e −), `u` = valor pontual único, `m` = mensalidade.

**Cores.** Estão no bloco `:root`, no início do CSS. As principais são `--ink` (fundo), `--bronze` (destaque) e `--graphite` (cinza).

**Horário e demais dados.** Procure a seção `id="contato"` no HTML. Os dados estruturados para buscadores ficam no `<script type="application/ld+json">` do `<head>`.

**Logo.** Está embutida na tag `<img class="logo">`, dentro do atributo `src`. Para trocar, substitua o conteúdo de `src` pelo caminho de outra imagem, por exemplo `src="logo.png"`.

## Como publicar online

Como é um único arquivo HTML, pode ser hospedado de graça em serviços como GitHub Pages, Netlify ou Vercel. Basta enviar o arquivo e, se necessário, renomeá-lo para `index.html`.

## Estrutura

```
solvantis-tech.html   # site completo (HTML, CSS e JavaScript)
README.md             # este arquivo
```

## Autor

Projeto desenvolvido por **[seu nome]** para a disciplina de Redes de Computadores, **[nome da escola ou faculdade]**, 2026.
