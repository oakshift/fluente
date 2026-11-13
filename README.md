# Fluente

Treino de conversação em inglês com o modo de voz da app do Claude, numa única página HTML sem dependências.

## O que faz

- **Falar** — escolhe o tipo de conversa (livre, situação real, dar opinião, contar uma história,
  revisão de erros, teste de nível) e o tema. A app prepara a mensagem para o Claude, com o teu nível,
  as palavras que estás a aprender e os erros que tens repetido. Copias, colas no Claude e falas.
  No fim dizes “end session”, o Claude escreve um relatório e colas-o de volta.
- **Rever** — os erros e as palavras novas de cada relatório viram cartões de repetição espaçada.
- **Progresso** — minutos a falar por semana, nível estimado pelo Claude, erros que mais te escapam
  e o histórico das conversas.
- **Guia** — kit de frases para conversar, falsos amigos, pronúncia para quem fala português, ajustes.

## Onde ficam os dados

Num repositório **privado** à parte (`fluente-dados`, ficheiro `dados.json`), lido e escrito pela app
com um token do GitHub guardado só no browser. Cada conversa e cada revisão é um commit. Sem rede, os
registos ficam no telemóvel e seguem quando houver ligação. Se outra app em `oakshift.github.io` já tiver
um token com acesso a `fluente-dados`, a app usa-o sozinha.

## Instalar no telemóvel

No Chrome: menu dos três pontos → **Instalar aplicação** ou **Adicionar ao ecrã principal**.
