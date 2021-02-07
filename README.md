# 20-dias-de-sass

De forma similar ao projeto de escrever 30 sites em 30 dias, esse projeto foca em aprender a usar Sass.

## Como Sass funciona?

Sass é tanto uma linguagem como uma ferramenta. O objetivo de Sass é cobrir algumas falhas de CSS e facilitar o desenvolvimento.

Sass lê um arquivo no formato .scss e o converte para um arquivo .css:

![Como Sass funciona](sass-blog-post-image01.jpg)


## Como usar esse repositório?

1. Faça um _fork_ do repositório para ter sua própria cópia.
2. Crie um diretório com seu nome de usário do GitHub.
2. Para cada dia, crie um diretório com o nome do site em que vai trabalhar (siga os sites na ordem listada aqui, um por dia).
    1. Rode `npm init` no diretório.
    1. Crie um diretório `src`
    1. Crie um diretório `static`
    1. Crie um diretório `public`
    1. Instale a dependenência `http-server` com `npm install --save-dev http-server`: https://github.com/http-party/http-server
    1. Dentro do `package.json` crie um script chamado `copy-static` que rode o comando `cp -r ./static ./public/` => copia o diretório `static` para dentro do `public`
    1. Dentro do `package.json` crie um script chamado `build-scss` que rode o comando `sass ./src/style.scss ./public/style.css`
    1. Dentro do `package.json` crie um script chamado `build` que rode o comando `npm run copy-static && npm run build-scss`
    1. Dentro do `package.json` crie um script chamado `serve` que rode o comando `http-server`
    1. Dentro do `package.json` crie um script chamado `run` que rode o comando `npm run build && npm run serve`
    1. Se precisar baixar imagens, coloque-as dentro do diretório `static`
4. Clone o site. **Limite seu tempo de trabalho: 4 horas no máximo!! Tente melhorar seu tempo gasto a cada dia.**. Caso as 4 horas se passem e você não tenha terminado o clone, pare mesmo assim. Reflita sobre o que poderia ter te ajudado a terminar mais rápido. Lembre-se: Não precisa ser perfeito, só precisa ser feito.
5. Pare, pense e responda as 3 perguntas abaixo:
    - 📚 Você aprendeu algo novo hoje? Se sim, o que?
    - 😓 O que poderia ter sido melhor hoje? Há algo que você queira melhorar para a próxima?
    - 🔥 O que foi bem hoje? Houve algo que você gostou?
6. Envie um _pull-request_ com seu código e coloque a respostas para as perguntas acima no conteúdo.
7. Se prepare para o próximo dia.

### Restrições

- Clone apenas a página apontada pelo link.
- Se o site tiver animações, ignore. Clone apenas a aparência.
- **Não** faça o site responsivo. Foque apenas em fazer com que ele funcione no navegador de um computador.


## Como instalar Sass

1. [Lobsters](https://lobste.rs/)
1. [WhatsApp](https://www.whatsapp.com/features/)
1. [IGDB](https://www.igdb.com/discover)
1. [Dribbble](https://dribbble.com/)
1. [Microsoft São Paulo](https://careers.microsoft.com/professionals/us/en/l-sao-paulo)
1. [Not a nomad blog](https://notanomadblog.com/categories/photography/)
1. [Google Cloud](https://cloud.google.com/gcp/)
1. [AirApps](https://airapps.co/)
1. [Tesouro direto](https://www.tesourodireto.com.br/)
1. [Indie Hackers](https://www.indiehackers.com/)
1. [Podcast hosting review](https://podcasthosting.review/)
1. [Ubiquiti](https://www.ui.com/products/#default)
1. [Transistor.fm](https://transistor.fm/pricing/)
1. [PocketCasts](https://www.pocketcasts.com/)

1. [Product Hunt](https://www.producthunt.com/)
1. [XP Investimentos](https://www.xpi.com.br/)
1. [Stripe Press](https://press.stripe.com/)
1. [Laracasts](https://laracasts.com/browse/all)
1. [GoRails](https://gorails.com/series)
1. [TappsGames](http://tappsgames.com/)
