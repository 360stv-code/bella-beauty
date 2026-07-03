# Bella Beauty — o que mudou (03/07/2026)

Performance: o Tailwind deixou de ser gerado por JavaScript no navegador (CDN removido) e virou CSS estatico embutido no index — a pagina nao fica mais invisivel esperando script carregar. Fotos convertidas para WebP (15 MB -> ~1 MB; a tratamento-facial.jpg tinha 10,5 MB e caiu para 39 KB). Fontes do Google agora carregam sem bloquear a renderizacao em todas as paginas.

SEO tecnico: robots.txt criado (nao existia), canonical e og:url da home corrigidos (barra final), charset movido para o inicio do head, sitemap com lastmod atualizado.

Como publicar: substitua os arquivos do repositorio pelos desta pasta (mesma estrutura). Depois envie o sitemap no Google Search Console da mesma forma que fez com a Azzurra e solicite indexacao das paginas principais.
