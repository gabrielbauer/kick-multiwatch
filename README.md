# Kick Multiwatch

Extensão de navegador que ganha pontos de canal da Kick em vários canais ao mesmo tempo, usando o login que você já tem na kick.com. Sem Python, sem colar token, sem abrir nenhuma live.

**Site com o guia completo:** https://gabrielbauer.github.io/kick-multiwatch/

**[♥ Apoie o dev no LivePix](https://livepix.gg/gravi7y)**

> **Aviso:** usa endpoints internos e não documentados da Kick. Simular tempo assistido pode violar os Termos de Serviço da Kick, e a sua conta pode ser restringida. Use por sua conta e risco. Projeto independente, sem relação com a Kick.

## Download

| Navegador | Arquivo |
|---|---|
| Chrome, Edge, Brave, Opera | [kick-multiwatch-chrome.zip](kick-multiwatch-chrome.zip) |
| Firefox 128 ou mais novo | [kick-multiwatch-firefox.zip](kick-multiwatch-firefox.zip) |
| Versão Python (alternativa, roda no terminal) | [kick-multiwatch-python.zip](kick-multiwatch-python.zip) |

## Como funciona

- Você adiciona os canais (pode colar vários de uma vez, separados por espaço ou vírgula).
- A Kick credita cerca de 2 canais a cada 5 minutos por conta (uns 240 pontos por hora). Por isso a extensão ganha em **2 canais ao vivo por vez** e deixa os outros **na fila**.
- **Troca automática:** quando um canal recebe os +10, a vaga passa para o canal que espera há mais tempo. Se um canal ficar 7 minutos sem receber, também passa a vez.
- Canais marcados **2×** (onde você é inscrito e ganha o dobro) ganham primeiro e não saem da vaga.
- **Resgates:** quando o saldo de um canal cai, a extensão anota o que você provavelmente resgatou. Ela nunca resgata nada sozinha.
- **Opções:** quantos canais ganham ao mesmo tempo, modo de troca, preços das recompensas, baixar ou apagar os dados da sessão.

## Instalar no Chrome, Edge, Brave ou Opera

1. Baixe `kick-multiwatch-chrome.zip` e **extraia** para uma pasta que você não vai apagar.
2. Abra `chrome://extensions` e ligue **Modo do desenvolvedor** (canto superior direito).
3. Clique em **Carregar sem compactação** e escolha a pasta extraída (a que tem o `manifest.json`).
4. Fixe a extensão no ícone de quebra-cabeça e clique no "K" para abrir o painel.

## Instalar no Firefox

1. Abra `about:debugging#/runtime/this-firefox`.
2. Clique em **Carregar extensão temporária…** e escolha `kick-multiwatch-firefox.zip`.
3. Clique no ícone "K" e, se pedir, permita o acesso à kick.com.
4. Deixe a aba do painel aberta enquanto quiser ganhar pontos. A extensão temporária some quando o Firefox fecha; é só carregar de novo.

## Primeiro uso

Entre na sua conta da kick.com no mesmo navegador. Abra o painel pelo ícone "K". Se aparecer "Faça login na Kick", entre na kick.com e clique em **Já entrei, verificar**. Depois adicione os seus canais.

## Privacidade

A extensão lê o cookie de login da kick.com só para falar com a própria Kick, não guarda esse valor e não envia nada para nenhum outro servidor. Detalhes em [privacy.html](privacy.html).
