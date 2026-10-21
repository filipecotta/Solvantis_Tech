# Solvantis Tech

Site institucional e de orçamentos da **Solvantis Tech**, empresa fictícia criada para a disciplina de Redes de Computadores. O foco é atender empresas que precisam de serviços de redes: cabeamento, infraestrutura e manutenção de computadores.

## Sobre o projeto

O site apresenta os serviços da empresa e permite que o cliente monte um orçamento escolhendo os serviços desejados. A lista escolhida é enviada pelo WhatsApp, sem necessidade de servidor ou banco de dados.

## Funcionalidades

- Página inicial com a logo e a proposta da empresa
- Lista de 7 serviços com valores de referência
- Botão "Adicionar" em cada serviço e painel lateral de orçamento
- Envio do orçamento pelo WhatsApp com a mensagem já preenchida
- Seção "Como trabalhamos" com as 5 etapas do atendimento
- Seção de diferenciais da empresa
- Formulário de contato que também envia pelo WhatsApp
- Layout responsivo, funciona em celular e computador

## Serviços oferecidos

| Serviço | Valor de referência |
|---|---|
| Cabeamento estruturado | R$ 45 por ponto |
| Infraestrutura de rede | a partir de R$ 890 |
| Wi-Fi corporativo | a partir de R$ 650 |
| Manutenção de computadores | R$ 120 por máquina |
| Roteador, firewall e VPN | a partir de R$ 380 |
| Suporte técnico mensal | R$ 490 por mês |
| Rede para câmeras de segurança | a partir de R$ 520 |

Os valores são exemplos criados para o trabalho e não representam preços reais.

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

**Número do WhatsApp.** No final do arquivo, procure a linha abaixo e troque pelo seu número, com 55 + DDD + número:

```js
var WA="5531900000000";
```

**Serviços e preços.** No início do script, edite a lista `S`. Cada linha segue o formato: nome, descrição, valor, tipo de cobrança.

```js
["Cabeamento estruturado","Descrição do serviço.","45","por ponto"],
```

**Cores.** Estão no bloco `:root`, no início do CSS. As principais são `--ink` (fundo), `--bronze` (destaque) e `--graphite` (cinza).

**Telefone, e-mail e horário.** Procure a seção `id="contato"` no HTML e troque os dados de exemplo.

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
