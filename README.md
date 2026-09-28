# Meu Plano

App de celular (PWA) do plano de treino e alimentação: registro das refeições por cards, "o que falta" em cada refeição, trocas do docinho e do Oakberry, treino do dia, peso e resumo semanal.

- Site estático: `index.html`, `manifest.json`, `sw.js` e `icons/`. Sem servidor, sem banco de dados, sem dependências externas.
- Os dados ficam só no celular de quem usa (armazenamento do navegador). Nada é enviado para lugar nenhum.
- Valores dos alimentos: tabela TACO, rótulos comuns e tabela oficial da Oakberry.

## Publicar no GitHub Pages

1. Criar um repositório **público e novo** chamado `meu-plano` (não usar o repositório de outro site).
2. Subir estes arquivos na raiz da branch `main`.
3. Em Settings → Pages: "Deploy from a branch", branch `main`, pasta `/ (root)`.
4. O endereço fica `https://SEU-USUARIO.github.io/meu-plano/`.

## Instalar no iPhone

1. Abrir o link no **Safari**.
2. Tocar em Compartilhar → "Adicionar à Tela de Início".
3. Usar sempre pelo ícone. O app instalado guarda os dados com segurança; no Safari comum, o iPhone apaga dados de sites parados há 7 dias.

## Atualizar

Trocar os arquivos no repositório. O app busca a versão nova sozinho quando tem internet.
