# DISK CAÇAMBA

Landing page da DISK CAÇAMBA, aluguel de caçambas e containers em Assis - SP.

Site no ar: https://diskcacamba.netlify.app

## O que tem aqui

- `index.html`: a página inteira
- `style.css`: estilos (Tailwind já compilado)
- `img/`: logo e fotos reais da empresa
- `fonts/`: fontes Barlow Condensed e DM Sans

Todos os preços da tabela abrem o WhatsApp (18) 99751-1524 com uma mensagem pronta do item escolhido.

## Como publicar

Arraste a pasta (ou um .zip com ela) na página de Deploys do projeto `diskcacamba` no Netlify.

## Como editar

- Textos e preços: direto no `index.html`.
- Se usar classes do Tailwind que ainda não existem no `style.css`, recompile:
  `npx tailwindcss@3.4.16 -i in.css -o style.css --minify` (com o `tailwind.config.js` deste repositório).
