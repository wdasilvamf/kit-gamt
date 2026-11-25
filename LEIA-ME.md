# Kit GAMT: Do sonho ao primeiro degrau

Página do kit pós-encontro "IA no mercado de trabalho". Funciona no celular, pode ser instalada como app e continua funcionando sem internet depois da primeira visita.

## Arquivos

| Arquivo | Para que serve |
|---|---|
| index.html | A página inteira |
| wbot.webp, wbot-cabeca.webp | Ilustrações do Wbot |
| manifest.webmanifest | Nome, cores e ícone do app |
| sw.js | Guarda a página para funcionar offline |
| icon-*.png, apple-touch-icon.png | Ícones da tela inicial |

## Publicar no GitHub Pages (uns 10 minutos, tudo pelo navegador)

1. Entre em github.com e clique em **New repository**.
2. Nome sugerido: `kit-gamt`. Marque **Public** (no plano grátis, o Pages só funciona com repositório público). Clique em **Create repository**.
3. Na página do repositório, clique em **uploading an existing file**.
4. Descompacte o .zip no computador e arraste **todos os arquivos** (não a pasta) para a área de upload. Clique em **Commit changes**.
5. Vá em **Settings → Pages**. Em **Branch**, escolha `main` e a pasta `/ (root)`. Clique em **Save**.
6. Espere 1 a 2 minutos e recarregue a página de Settings → Pages. O endereço aparece no topo: `https://SEU-USUARIO.github.io/kit-gamt/`.
7. Abra o endereço no celular e teste: preencher um campo, copiar um pedido, baixar o mapa.

## Atualizar depois

1. No repositório, clique em **Add file → Upload files** e arraste só os arquivos que mudaram (o GitHub substitui os antigos).
2. Se mudou o index.html, abra o sw.js e troque `primeiro-degrau-v1` por `v2`, `v3`... Isso faz os celulares pegarem a versão nova.

## Instalar como app (para os alunos)

- **Android (Chrome):** aparece o botão "Instalar como app no celular" na página. Ou menu ⋮ → "Instalar app".
- **iPhone (Safari):** botão Compartilhar → "Adicionar à Tela de Início".

## Bom saber

- O que cada aluno escreve fica salvo só no navegador dele. Trocar de celular ou limpar os dados apaga tudo. Por isso existe o botão "Baixar meu mapa".
- Dentro do Instagram ou do WhatsApp o download pode não funcionar. A página oferece abrir a imagem para salvar segurando o dedo. Melhor ainda: abrir o link no Chrome ou no Safari.
- O guia do facilitador fica no endereço da página + `#facilitador`.
