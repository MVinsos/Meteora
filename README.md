# Meteora - Moda de Impacto Positivo

## Descrição

Este é o projeto de uma página web para a loja de moda "Meteora". A página foi criada baseado neste [figma](https://www.figma.com/file/2TLgt8UjsWUViWlmpXu5Fz/Challenge-Front-end-%7C-Loja-Meteora?node-id=2386%3A3188&mode=dev) e exibe diversas funcionalidades típicas de um site de e-commerce, incluindo um cabeçalho de navegação, banners, categorias de produtos e seções de produtos em destaque.

## Estrutura do Projeto

O projeto HTML está estruturado da seguinte forma:

### Cabeçalho (`<header>`)

Contém a logo da empresa, links de navegação e uma barra de busca.

- **Logo**: Imagem da logo da empresa.
- **Links de Navegação**: 
  - Home
  - Nossas lojas
  - Novidades
  - Promoções
- **Barra de Busca**: Campo de pesquisa para produtos com botão de busca.
- **Menu Burger**: Menu de navegação para dispositivos móveis.

### Principal (`<main>`)

Inclui várias seções:

1. **Seção de Banner**
   - Banners responsivos para desktop, tablet e dispositivos móveis.
   - Barra de busca integrada ao banner.

2. **Seção de Categorias**
   - Lista de categorias de produtos como camisetas, bolsas, calçados, etc.
   - Cada categoria é representada por uma imagem e um link.

3. **Seção de Produtos em Destaque**
   - Lista de produtos populares com imagem, descrição, preço e botão "Ver mais".
   - Produtos incluem: camiseta, calça alfaiataria, tênis, jaqueta jeans, óculos e bolsa.

4. **Seção de Facilidades**
   - Informações sobre facilidades oferecidas pela loja, como pagamento via PIX, trocas gratuitas e sustentabilidade.

5. **Seção de Newsletter**
   - Formulário para cadastro de e-mail para receber novidades, promoções e desconto na primeira compra.

## Dependências

O projeto utiliza os seguintes recursos externos:

- **Reset CSS**: Para normalizar os estilos padrão dos navegadores.
- **Fontes do Google**: Utiliza a fonte "Inter" com variações de peso.
- **CSS Customizado**: Estilos específicos do projeto definidos nos arquivos `reset.css` e `styles.css`.

## Estrutura de Arquivos

```plaintext
├── index.html
├── assets
│   ├── style
│   │   ├── reset.css
│   │   └── styles.css
│   ├── img
│   │   ├── Mobile
│   │   │   ├── Logo mobile.png
│   │   │   └── Banner carousel 1 _ 375.png
│   │   ├── Tablet
│   │   │   └── Banner carousel 1 _ 768.png
│   │   └── Desktop
│   │       ├── Banner carousel 1 _ 1440 (1).png
│   │       ├── Categorias
│   │       │   ├── Categoria camiseta.png
│   │       │   ├── Categoria Bolsa.png
│   │       │   ├── Categoria Calçados.png
│   │       │   ├── Categoria calça.png
│   │       │   ├── Categoria casacos.png
│   │       │   └── Categoria óculos.png
│   │       ├── Imagens Cards
│   │       │   ├── Camiseta.png
│   │       │   ├── Calça.png
│   │       │   ├── Tenis.png
│   │       │   ├── Jaqueta.png
│   │       │   ├── óculos.png
│   │       │   └── Bolsa.png
│   │       └── Ícones
│   │           ├── x-diamond (2).png
│   │           ├── arrow-repeat (2).png
│   │           └── flower1 (3).png
```
##
No momento somente o HTML e o CSS estão concluidos, futuramente adicionarei JavaScript.
