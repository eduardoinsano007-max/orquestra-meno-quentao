# Orquestra dos meno quentão

Site oficial do **Orquestra dos meno quentão**, um festival fictício de música que mistura São João brasileiro, forró, música eletrônica e cultura de rua.

## Briefing

### Público
Jovens e adultos de 18 a 35 anos, moradores de Recife e região, que gostam de música ao vivo, experiências visuais, festas de rua, cultura nordestina e eventos com personalidade. Esperam um festival acessível, fotogênico, seguro e com programação diversa.

### Clima em 3 palavras
**Quente, elétrico, coletivo.**

### Paleta

| Cor | Hex | Uso |
|---|---|---|
| Azul noite | `#171B31` | Hero, footer e seções de contraste |
| Amarelo milho | `#F7C84B` | Destaques, títulos, ticker e CTAs especiais |
| Vermelho pimenta | `#E8513F` | Botões, marca e elementos de ação |
| Azul piscina | `#62B9C7` | Cards, detalhes e sensação de frescor |
| Creme papel | `#FFF7E7` | Fundo principal e áreas de leitura |

### Tipografia
- **Bebas Neue** para títulos: tem presença de cartaz de festa e cria uma voz popular, forte e memorável.
- **DM Sans** para textos: é legível em telas pequenas, neutra e equilibrada para não competir com os títulos.

### Referências visuais
- [Coala Festival](https://www.coalafestival.com.br/) — gostamos da forma como o site transforma o festival em uma experiência visual vibrante.
- [Bateko1](https://bateko1.com/) — gostamos da energia jovem, das cores contrastantes e da linguagem direta.
- [Rock in Rio](https://www.rockinrio.com/) — gostamos da hierarquia de conteúdo e da organização da programação.

## Páginas

- `index.html` — início, datas, local, chamada e três atrações em destaque.
- `lineup.html` — oito artistas com imagem, dia, horário e palco.
- `ingressos.html` — três categorias com preço e benefícios.
- `informacoes.html` — endereço, como chegar, mapa ilustrado e regras.
- `faq.html` — seis perguntas expansíveis e formulário de contato visual.

## Refinamento com IA

Prompts que mais fizeram diferença:

1. “Crie uma identidade visual para um festival que misture xilogravura nordestina com rave contemporânea, evitando o visual genérico de evento corporativo.”
2. “Use um layout editorial com títulos enormes, cards assimétricos e bastante textura, mas mantenha a leitura confortável em mobile.”
3. “Transforme a navegação em uma experiência de festival: menu compacto, CTAs claros, ticker em amarelo milho e microinterações rápidas.”
4. “Revise todas as páginas para que tenham propósitos diferentes, mantendo header, menu, footer e style.css compartilhados.”

## Tecnologias

O site foi feito somente com **HTML, CSS e JavaScript**, sem frameworks ou backend. As imagens de referência ficam em `client/img/` e todas as páginas compartilham `client/style.css` e `client/script.js`.

## Como rodar localmente

```bash
cd client
python3 -m http.server 8080
```

Depois, acesse `http://localhost:8080`.

## Publicação

O projeto foi estruturado como site estático para publicação na Vercel. No dashboard da Vercel, importe o repositório, use `client` como diretório raiz e deixe o build vazio; os arquivos HTML podem ser servidos diretamente.

> Link da Vercel: preencher após a publicação.

## Autoria

Feito por **Maria & João**, com apoio de Inteligência Artificial.
