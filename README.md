# [transformadoras.dev](https://transformadoras.dev) 🏳️‍⚧️✨

Quantas pessoas trans notáveis na tecnologia você consegue citar sem qualquer pesquisa prévia? Você conhece as suas biografias, os seus feitos? O projeto **Transformadoras** celebra pessoas trans na tecnologia ao recontar e reunir em um repositório as histórias do impacto que elas fazem ou um dia fizeram na área — da instrução de manuseio dinâmico generalizado até iniciativas que ajudam a tornar os nossos ambientes de discussão e colaboração mais seguros para todas as pessoas.

## O que usamos para construir o nosso site?
* 🧰 **Framework:** [Hugo](https://gohugo.io) (versão 0.73.0)
* 🎨 **Tema:** um fork do [Creative Portfolio](https://github.com/transformadoras/hugo-creative-portfolio-theme)
* 🚀 **Lançamento:** [Netlify](https://netlify.com)

## Como gerenciamos o conteúdo?
### Armazenamento de dados
Hugo oferece suporte para [o armazenamento de dados personalizados na pasta `data`](https://gohugo.io/templates/data-templates/#the-data-folder) através de arquivos YAML, JSON e e TOML que podem ser referenciados em arquivos HTML dedicados à geração de páginas. Escolhemos usar arquivos JSON ([JavaScript Object Notation](https://pt.wikipedia.org/wiki/JSON)) para receber as informações necessárias para montar as biografias de pessoas trans pela menor barreira de aprendizado, melhor legibilidade e pelas experiências positivas que uma de nossas mantenedoras teve em um caso de uso semelhante. Esses arquivos nos ajudam a controlar melhor fatores como o conjunto mínimo de informações para a criação de uma biografia (fotografia, nacionalidade, história) e a aparência e disposição de cada item na página em que ela será exibida.

### Gerenciamento das páginas
O framework também oferece [um modelo de lista](https://gohugo.io/templates/lists/) para renderizar múltiplas páginas de uma mesma categoria e um [modelo de página individual](https://gohugo.io/templates/single-page-templates/) para controlarmos a aparência e funcionamento de uma página de uma categoria específica. Ainda não decidimos a estratégia que empregaremos para categorizar as biografias que receberemos, mas a compreensão dos dois modelos citados é essencial para a construirmos uma.

## Como posso contribuir?
- 🗃️ Sugira pessoas trans para incluirmos em nosso repositório [através de um issue](https://github.com/transformadoras/website/issues)
- 🛠️ Ajude-nos a personalizar o nosso site [melhorando o nosso tema-base](https://github.com/transformadoras/hugo-creative-portfolio-theme)
- 🧠 Auxilie-nos a construir estratégias para fazer deste projeto algo ainda melhor!

## Idealizadoras
Este projeto é fruto de uma conversa e uma amizade entre [Juliana Dias](https://github.com/juuh42dias) e [Anna e só](https://github.com/contraexemplo), duas pesssoas trans na tecnologia. Ele é construído com muito amor e carinho diretamente do coração do Brasil.
