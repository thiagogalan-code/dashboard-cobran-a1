# 📊 Controle de Cobranças Uvel

Dashboard financeiro para controle de cobranças nas cidades de **Umuarama - PR**, **Jaraguá do Sul - SC** e **São Bento do Sul - SC**.

## ✅ Funcionalidades

- 🏙️ **Multi-cidade** — dados separados por cidade
- 📊 **Dashboard** — visão geral com KPIs e gráficos
- 💰 **Recebidos** — registro diário com auto-soma
- ⚠️ **Inadimplentes** — controle de dias em atraso
- 👥 **Clientes** — base importada da planilha
- 📂 **Importar Planilha** — upload de .XLS, .XLSX e .CSV

## 🚀 Como hospedar

### Opção 1 — Netlify Drop (mais rápido, sem conta)
1. Acesse [netlify.com/drop](https://netlify.com/drop)
2. Arraste a pasta `uvel-dashboard` inteira
3. Pronto — link gerado automaticamente

### Opção 2 — GitHub + Netlify
1. Suba esta pasta no GitHub como repositório
2. No Netlify, conecte o repositório
3. Deploy automático a cada atualização

### Opção 3 — GitHub Pages
1. Suba no GitHub
2. Vá em **Settings → Pages**
3. Selecione a branch `main` e pasta `/root`
4. Acesse via `https://seu-usuario.github.io/uvel-dashboard`

## 📁 Estrutura

```
uvel-dashboard/
├── index.html   ← arquivo principal (tudo em um só arquivo)
└── README.md    ← este arquivo
```

## 🛠️ Tecnologias
- HTML, CSS e JavaScript puro
- [SheetJS](https://sheetjs.com/) para leitura de Excel
- Dados salvos no `localStorage` do navegador
