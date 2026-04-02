# Melodia - Plataforma de Streaming Musical

**Disciplina:** Desenvolvimento Web Front-End  
**Tecnologias:** HTML5, Tailwind CSS, JavaScript  
**Autor:** Felipe - 2026

---

## Descrição do Projeto

O **Melodia** é uma plataforma de streaming musical desenvolvida como projeto acadêmico para a disciplina de Desenvolvimento Web Front-End. O objetivo é criar uma interface moderna e responsiva para consumo de músicas online, simulando a experiência de plataformas como Spotify e Deezer.

---

## Estrutura do Projeto

```
Soundly/
├── index.html              # Landing page pública
├── src/
│   ├── pages/
│   │   ├── cadastro.html       # Página de registro
│   │   ├── create_account.html # Página de criação de conta
│   │   ├── dashboard.html      # Área principal do usuário
│   │   ├── login.html           # Página de login
│   │   ├── plans.html           # Planos de assinatura
│   │   └── user.html            # Perfil do usuário
│   ├── js/
│   │   └── java.js              # Arquivo JavaScript
│   └── assets/
│       ├── *.jpg/png            # Capas de álbuns
│       └── audios/              # Arquivos de áudio MP3
└── README.md
```

---

## Funcionalidades

### Página Pública (Landing Page)
- Hero section com chamada para ação
- Seção de benefícios do serviço
- Apresentação de funcionalidades principais
- Depoimentos de usuários
- Formulário de cadastro

### Sistema de Autenticação
- Login de usuários
- Criação de nova conta com validação
- Persistência de dados via LocalStorage

### Dashboard do Usuário
- Reprodução de músicas com player nativo
- Barra de progresso com seeking
- Controles: play/pause, próximo, anterior, restart
- Listagem de playlists personalizadas
- Busca de músicas
- Seção "Para você" e "Ouça novamente"

### Planos de Assinatura
- Três planos: Mensal, Trimestral e Anual
- Destaque visual para o plano popular
- Design responsivo em cards

---

## Tecnologias Utilizadas

| Tecnologia | Versão | Uso |
|------------|--------|-----|
| Tailwind CSS | CDN | Framework CSS para estilização |
| Poppins | Google Fonts | Tipografia do projeto |
| HTML5 | - | Estrutura das páginas |
| JavaScript | ES6+ | Lógica e interatividade |
| LocalStorage | - | Persistência de dados |

---

## Como Executar

1. Clone ou baixe o repositório
2. Abra o arquivo `index.html` em qualquer navegador moderno
3. Navegue pelas páginas através dos links disponíveis

> **Nota:** Para executar localmente, é necessário um servidor HTTP para evitar problemas de CORS com os arquivos de áudio. Você pode usar:

```bash
# Com Python 3
python -m http.server 8000

# Com Node.js (Live Server)
npx live-server
```

---

## Design System

### Cores Principais
- **Primary:** `#ec4899` (Pink-500)
- **Background:** `#000000` (Black)
- **Surface:** `rgba(255,255,255,0.1)` (White/10)
- **Text Primary:** `#ffffff` (White)
- **Text Secondary:** `#9ca3af` (Gray-400)

### Tipografia
- **Família:** Poppins
- **Pesos:** 300 (Light), 500 (Medium), 700 (Bold)

### Recursos Visuais
- Gradientes escuros (purple-900, pink-900)
- Glassmorphism com backdrop-blur
- Animações hover com scale
- Bordas arredondadas (rounded-xl, rounded-2xl)

---

## Requisitos Atendidos

- [x] Layout responsivo (mobile-first)
- [x] Navegação entre páginas
- [x] Formulários funcionais com validação
- [x] Player de áudio com controles completos
- [x] Persistência de dados no cliente
- [x] Interface moderna com Tailwind CSS
- [x] Tipografia customizada
- [x] Animações e transições suaves

---

## Trabalhos Futuros

Para uma versão completa, recomenda-se:

- Backend com API REST para autenticação real
- Banco de dados para armazenar músicas e usuários
- Integração com API de streaming de áudio (Spotify, Deezer)
- Sistema de recomendação baseado em histórico
- Modo offline com Service Workers
- Upload de playlists customizadas

---

## Licença

Este projeto é de uso acadêmico. Todos os direitos reservados.

---

## Contribuidores

| Nome | RM |
|------|-----|
| Felipe Menezes | 566607 |
| Vinicius Kozonoe Guaglini | 567264 |
| Murilo Jeronimo Fereira Nunes | 560641 |
