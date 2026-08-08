# 🎈 Festive Float - Gerenciador de Festas e Balões

**Aplicativo completo para decoradores de festas gerenciarem clientes, orçamentos, estoque e cronograma de eventos.**

![Festive Float](https://img.shields.io/badge/Version-1.0.0-brightgreen)
![HTML5](https://img.shields.io/badge/HTML5-E34C26?style=flat&logo=html5&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=flat&logo=tailwind-css&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

---

## 📱 Telas Incluídas

| # | Tela | Descrição |
|---|------|-----------|
| 1 | **Dashboard** | Visão geral de eventos e tarefas do dia |
| 2 | **Catálogo de Portfólio** | Vitrine visual para clientes |
| 3 | **Novo Orçamento** | Calculadora automática com integração WhatsApp |
| 4 | **Gestão de Clientes** | Banco de dados de contatos e status |
| 5 | **Controle de Estoque** | Monitoramento de insumos |
| 6 | **Agenda** | Calendário mensal de festas |
| 7 | **Aprovação de Orçamento** | Página externa para cliente aprovar |
| 8 | **Login/Cadastro** | Fluxo de autenticação |
| 9 | **Configurações** | Tabela de preços e perfil |

---

## 🚀 Tecnologias

- **Frontend:** HTML5, Tailwind CSS, JavaScript Vanilla
- **Mobile:** Capacitor / Cordova (Android & iOS)
- **Design System:** Festive Float Custom
- **Storage:** LocalStorage + IndexedDB
- **API Integration:** REST (pronta para backend)

---

## 📁 Estrutura do Projeto

```
festive-float/
├── index.html                 # Login/Entrada
├── dashboard.html             # Dashboard Principal
├── portfolio.html             # Catálogo de Portfólio
├── budget.html                # Novo Orçamento
├── clients.html               # Gestão de Clientes
├── inventory.html             # Controle de Estoque
├── agenda.html                # Agenda/Calendário
├── approval.html              # Aprovação (Cliente)
├── settings.html              # Configurações
│
├── css/
│   ├── tailwind.css           # Tailwind compilado
│   ├── design-system.css      # Design System Festive Float
│   └── components.css         # Componentes customizados
│
├── js/
│   ├── app.js                 # Inicialização
│   ├── auth.js                # Autenticação
│   ├── budget.js              # Lógica de orçamentos
│   ├── clients.js             # Gestão de clientes
│   ├── inventory.js           # Controle de estoque
│   ├── calendar.js            # Calendário
│   ├── storage.js             # LocalStorage/IndexedDB
│   ├── api.js                 # Chamadas API
│   └── utils.js               # Utilitários
│
├── assets/
│   ├── images/                # Imagens e ícones
│   ├── fonts/                 # Tipografia
│   └── icons/                 # SVG icons
│
├── capacitor.config.json      # Config Capacitor
├── package.json               # Dependencies
└── docs/                      # Documentação completa
```

---

## 🎨 Design System - Festive Float

### Paleta de Cores
- 🎀 **Primary:** #FF6B9D (Rosa Festivo)
- 🎈 **Secondary:** #FFC93D (Amarelo Dourado)
- ✨ **Accent:** #A78BFA (Roxo Suave)
- 🌈 **Success:** #10B981 (Verde)
- ⚠️ **Warning:** #F59E0B (Laranja)
- ❌ **Error:** #EF4444 (Vermelho)

### Tipografia
- **Font:** Quicksand (Google Fonts)
- **Sizes:** 12px, 14px, 16px, 18px, 20px, 24px, 32px
- **Weights:** 300, 400, 600, 700

---

## 🛠️ Como Começar

### Pré-requisitos
- Node.js 16+
- npm ou yarn
- Git

### Instalação

```bash
# Clone o repositório
git clone https://github.com/KauaSantos0409/festive-float.git
cd festive-float

# Instale as dependências
npm install

# Inicie o servidor de desenvolvimento
npm start
```

### Build para Produção

```bash
npm run build
```

### Build Mobile (Capacitor)

```bash
npm run build:ios    # iOS
npm run build:android # Android
```

---

## 📊 Funcionalidades Principais

✅ Dashboard com eventos do dia  
✅ Catálogo de portfólio  
✅ Calculadora de orçamentos com WhatsApp  
✅ Gestão de clientes  
✅ Controle de estoque  
✅ Agenda com calendário  
✅ Aprovação de orçamento (cliente)  
✅ Sistema de autenticação  
✅ Configurações de preços  

---

## 📈 Status do Desenvolvimento

- [x] Estrutura base
- [ ] Componentes Tailwind
- [ ] Páginas HTML
- [ ] Lógica JavaScript
- [ ] Storage local
- [ ] Integração WhatsApp
- [ ] Capacitor setup
- [ ] Testes
- [ ] CI/CD
- [ ] Deploy

---

## 📄 Licença

MIT License - Veja [LICENSE](LICENSE)

---

**Feito com ❤️ para decoradores que amam balões!** 🎈
