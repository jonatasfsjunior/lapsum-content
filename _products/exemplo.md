---
title: "Nome do Produto"
subtitle: "Subtítulo, geralmente um slogan, marca, o que quiser."
description: Descrição, mínimo 80 caracteres, preferencialmente 120 para Google Search, etc.
author: # Autor do Produto, opcional.
product_code: código-de-produto # Código qualquer para indentificação de "_data/products".
layout: product # Leiaute de página, não mude por favor.
image: /img/logo/exemplo/exemplo-logo.png # Use uma render 1:1, fundo transparente, com objeto centralizado.
banner: /img/banner/exemplo/exemplo.png
price-br: "75,00" #Preço - Real Brasileiro
price-usa: "14,99" #Preço - Dólar Americano
price-euro: "13,99" #Preço - Euro
price-gbp: "12,99" #Preço - Libra Esterlina
features: # Me diga o que seu produto oferece, e por que eu deveria comprá-lo?
  - label: Modelo de boa qualidade.
  - icon: # Utiliza Font Awesome 6 Free - https://fontawesome.com/icons - Use o formato: fa-nomedoicone - Pode ser ignorado.
  - label: Fotorealista.
rating: 5 # Quantidade de estrelas - Sim, não há avaliações dinâmicas.
hide_hero: false # Ocultar Banner - Por que iria querer fazer isso?
hero_images: # Caso queira utilizar uma única imagem, use `hero_image: /exemplo.png`
  - /img/banner/exemplo/exemplo.png
  - /img/galeria/exemplo/exemplo1.png
  - /img/galeria/exemplo/exemplo2.png
hero_height: is-fullheight # Tamanho do Banner
hero_image_thumbs: true # Define se vai ter as thumbnails para livre escolha da imagem visualizada.
hero_hide_text: true # Esconde o título e subtítulo sobre o banner, mesmo sistema usado em outras partes.
tags: [Tag1, Tag2] # Tags de produto, normalmente Marcas, Classificação, Ano, etc.
category: [Carros] # Categoria única. Grupo ao qual pertence o produto, para pesquisas no site.
published: true # Caso não queira ter o produto na loja, mas não excluir os arquivos.
hidden: true # Pra página não aparecer na loja, mas continuar disponível.
---