# 🎾 Barra Tennis Clube — Sistema de Reservas

## Como publicar no Vercel (passo a passo)

### Opção A — Pelo site do Vercel (mais fácil, sem instalar nada)

1. Acesse [vercel.com](https://vercel.com) e crie uma conta grátis (pode usar Google)
2. Acesse [github.com](https://github.com) e crie uma conta grátis
3. No GitHub, clique em **"New repository"** → dê o nome `barra-tennis` → clique em **Create**
4. Faça upload de todos os arquivos desta pasta para o repositório
5. No Vercel, clique em **"Add New Project"** → **"Import Git Repository"**
6. Selecione o repositório `barra-tennis`
7. Clique em **Deploy** — pronto! 🎉

O Vercel vai gerar um link como: `https://barra-tennis.vercel.app`

---

### Opção B — Pelo terminal (se tiver Node.js instalado)

```bash
# 1. Instale as dependências
npm install

# 2. Instale o CLI do Vercel
npm install -g vercel

# 3. Faça login
vercel login

# 4. Publique
vercel --prod
```

---

## Rodar localmente

```bash
npm install
npm run dev
```

Acesse: http://localhost:5173
