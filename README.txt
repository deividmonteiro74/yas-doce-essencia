Yas Doce Essência — V22 (ícone/PWA com a logo oficial)
Login administrativo: admin / 1234

IMPORTANTE — ESTA VERSÃO TEM VÁRIOS ARQUIVOS, NÃO SÓ O index.html
Dessa vez, pra ícone funcionar direito no iPhone/Android/navegador, o
sistema depende de arquivos extras que precisam ir TODOS juntos, na mesma
pasta (raiz) do repositório no GitHub, lado a lado com o index.html:

  index.html              (o site em si, atualizado)
  favicon-32x32.png       (ícone da aba do navegador)
  favicon-16x16.png       (ícone da aba do navegador, versão menor)
  apple-touch-icon.png    (ícone ao salvar na tela de início do iPhone)
  icon-192.png            (ícone PWA Android, tamanho padrão)
  icon-512.png            (ícone PWA Android, tamanho grande/splash)
  manifest.webmanifest    (arquivo que diz ao Android/Chrome o nome do
                           atalho "Yas Doce Essência" e qual ícone usar)

COMO SUBIR NO GITHUB
1. Abra o repositório deividmonteiro74/yas-doce-essencia.
2. Use "Add file → Upload files" e arraste TODOS os 7 arquivos acima de
   uma vez (inclusive substituindo o index.html antigo).
3. Confirme que todos ficaram na raiz do repositório (mesma pasta,
   nenhum dentro de subpasta) — os links no index.html apontam pra
   "favicon-32x32.png" etc. sem caminho, então precisam estar juntos.
4. Faça o commit. A Vercel publica sozinha em seguida.

O QUE MUDOU
- Ícone genérico "Y" eliminado: agora usa sua logo oficial em todo lugar
  que o navegador/celular mostra um ícone do site.
- Fundo branco da logo removido (ela fica limpa, redonda).
- iPhone: ao usar "Adicionar à Tela de Início" no Safari, aparece a logo
  de verdade, com o nome "Yas Doce Essência" embaixo.
- Android/Chrome: mesma coisa, com ícone adaptado ao formato que o
  Android usa (círculo, quadrado arredondado etc. — qualquer formato).
- A logo também foi atualizada dentro do próprio site (topo, tela de
  boas-vindas) para essa versão mais limpa que você enviou.

PARA TESTAR
No celular, abra o site pela Vercel (não local) e use "Adicionar à Tela de
Início" (iPhone) ou o aviso de instalar app / menu → "Instalar app"
(Android/Chrome). O ícone que aparecer deve ser a logo roxa, não mais a
letra "Y" genérica.
