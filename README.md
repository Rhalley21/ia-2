# Big Monster · Hamburgueria Artesanal

Site de apresentação da **Big Monster**, hamburgueria artesanal em Valença do Piauí (PI).

- Rua São João, 471 · Centro · Valença do Piauí
- Aberto todos os dias, das 17:30 às 00:30
- WhatsApp: (89) 99404-1551
- Instagram: [@bigmonstervalenca](https://www.instagram.com/bigmonstervalenca/)
- Cardápio online: [bigmonstervalenca.menudino.com](https://bigmonstervalenca.menudino.com)

## O que tem no site

- Abertura com fotos reais empilhadas em 3D, que acompanham o mouse
- Seção em profundidade: as fotos vêm do fundo da tela enquanto você rola
- Carrossel 3D de fotos (arraste para girar, toque para ampliar)
- Cardápio completo com abas (lanches, porções, molhos, doces e bebidas), filtros e fotos reais de cada lanche
- Passo a passo de como pedir, horário com dia atual destacado e status "aberto agora"

Os preços ainda não foram incluídos. Os itens sem foto real mostram "Foto real em breve".

## Estrutura

```
index.html        página única (HTML, CSS e JS sem dependências)
img/              fotos da galeria e da abertura
img/menu/         fotos de cada lanche do cardápio
```

Não precisa de build nem de `npm install`. As fontes vêm do Google Fonts.

## Publicar no GitHub Pages

1. Crie um repositório no GitHub e envie estes arquivos para a branch `main`.
2. No repositório, abra **Settings > Pages**.
3. Em **Source**, escolha **Deploy from a branch**, depois `main` e a pasta `/ (root)`. Salve.
4. Em um ou dois minutos o site fica disponível em `https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/`.

Para testar no computador, basta abrir o `index.html` no navegador.

## Onde editar

- **Cardápio:** no `index.html`, procure por `const MENU=`. Cada lanche é uma linha `L('Nome','Descrição',[tags],'selo')`.
- **Preços:** troque o texto `Preço em breve` dentro da função `card()`, ou acrescente um campo de preço em cada item.
- **Fotos do cardápio:** coloque o arquivo em `img/menu/` e ligue o nome do lanche ao arquivo nos objetos `PH` e `IMG`.

## Fotos

Todas as fotos são da própria Big Monster (Instagram e cardápio online oficial). Antes de publicar, confirme a autorização da casa e, se possível, troque pelos arquivos originais em alta resolução.
