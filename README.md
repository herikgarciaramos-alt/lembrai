# 🔔 Lembrai — Seu app de lembretes pessoal

App PWA (Progressive Web App) para lembretes com notificações. Funciona no celular e no computador, instala como app nativo e funciona offline.

---

## Como hospedar gratuitamente no GitHub Pages

### Passo 1 — Criar conta no GitHub
1. Acesse https://github.com e clique em **Sign up**
2. Crie sua conta (é gratuita)

### Passo 2 — Criar o repositório
1. Clique no **+** no canto superior direito → **New repository**
2. Nome do repositório: `lembrai` (importante: minúsculas)
3. Marque **Public**
4. Clique em **Create repository**

### Passo 3 — Fazer upload dos arquivos
1. Na página do repositório, clique em **uploading an existing file**
2. Arraste todos os arquivos desta pasta para a área de upload:
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `icon-192.png`
   - `icon-512.png`
3. Clique em **Commit changes**

### Passo 4 — Ativar o GitHub Pages
1. No repositório, clique em **Settings** (engrenagem)
2. No menu lateral, clique em **Pages**
3. Em **Branch**, selecione `main` e pasta `/ (root)`
4. Clique em **Save**
5. Aguarde 1-2 minutos

### Passo 5 — Acessar seu app
Seu app estará disponível em:
```
https://SEU_USUARIO.github.io/lembrai
```

---

## Como instalar no celular

### Android (Chrome)
1. Acesse a URL do seu app no Chrome
2. Toque nos 3 pontinhos (⋮) → **Adicionar à tela inicial**
3. Confirme — o app aparece como ícone na tela inicial

### iPhone (Safari)
1. Acesse a URL no Safari
2. Toque no botão de compartilhar (□↑)
3. Role para baixo → **Adicionar à Tela de Início**
4. Confirme — o app instala como app nativo

---

## Funcionalidades

- ✅ Três tipos: Tarefa, Compromisso e Estudo
- ✅ Notificações reais no horário marcado
- ✅ Funciona offline (após primeira visita)
- ✅ Modo escuro automático
- ✅ Dados salvos no próprio aparelho (privacidade total)
- ✅ Abas: Hoje / Próximos / Todos

---

## Estrutura dos arquivos

```
lembrai/
├── index.html      → App principal
├── manifest.json   → Configuração do PWA
├── sw.js           → Service Worker (offline + notificações)
├── icon-192.png    → Ícone do app
├── icon-512.png    → Ícone grande (splash screen)
└── README.md       → Este arquivo
```

---

Feito com 💚 usando HTML puro, sem dependências.
