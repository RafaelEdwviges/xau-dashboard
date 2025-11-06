# XAU/USD Dashboard (Next.js)

Projeto pronto para deploy no Vercel. Contém:
- `pages/index.jsx` — dashboard React (dark theme)
- `pages/api/live.js` — serverless proxy para Yahoo Finance (evita CORS)
- `pages/api/calendar.js` — scraping básico do Investing.com (exemplo)
- Integração com Supabase para salvar cenários (requer variáveis de ambiente)

## Como usar (resumido)
1. Crie um repositório no GitHub e faça push destes arquivos.
2. Configure variáveis no Vercel:
   - NEXT_PUBLIC_SUPABASE_URL
   - NEXT_PUBLIC_SUPABASE_ANON_KEY
3. Importe o repositório no Vercel e clique em Deploy.
4. Acesse o link fornecido pela Vercel.

Precisa de ajuda para pushar para um repo? Posso te fornecer os comandos git.
