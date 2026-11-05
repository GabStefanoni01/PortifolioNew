# Portfólio — Gabriel Stefanoni

Angular com prerender estático (HTML completo no primeiro carregamento, bom para SEO), hospedado na Vercel.

```bash
npm install
npm start        # desenvolvimento em http://localhost:4200
npm run build    # saída em dist/portfolio/browser
```

Deploy: importar o repositório na Vercel (framework Angular, configurado em `vercel.json`).
Conteúdo em `src/app/app.html`, estilos em `src/styles.css`, metadados em `src/index.html`.
