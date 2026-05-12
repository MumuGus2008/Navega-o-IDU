Aplicação estática "Apoio ao Estudo"

Conteúdo:
- `index.html` — página estática com UI, acessibilidade e modais de login/cadastro (localStorage).

Deploy no Vercel (estático):
1. Instale a CLI Vercel (opcional):

```bash
npm i -g vercel
```

2. No diretório do projeto (onde está `index.html`), faça login e deploy:

```bash
cd "c:\Users\MURILLOABRAAOPEIXOTO\Desktop\navegação"
vercel login
vercel --prod
```

3. Ou crie um novo projeto no https://vercel.com, conecte um repositório (GitHub/GitLab/Bitbucket) ou importe diretamente a pasta local usando a CLI.

Observações:
- Esse projeto é uma aplicação estática; não há backend real. O login/cadastro usa `localStorage` apenas para demonstração.
- Para integrar com API real, forneça endpoints (registro, login) e eu adapto os formulários para enviar requisições `fetch`.
