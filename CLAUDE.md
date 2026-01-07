# GT Móvel - Guia para Claude Code

## Comandos de Build
Este é um site estático HTML/CSS/JS - **não requer build**.
- `npm start` - Inicia servidor local em http://localhost:8080

## Comandos de Teste
- `npm test` - Executa todos os testes unitários
- `npm run test:watch` - Executa testes em modo watch
- `npm run test:e2e` - Executa testes end-to-end com Playwright

## Comandos de Lint
- `npm run lint` - Verifica código JavaScript
- `npm run lint:fix` - Corrige problemas automaticamente

## Arquitetura
- **Stack:** HTML5 + CSS3 + Vanilla JavaScript (ES6+)
- **Bibliotecas via CDN:** Tailwind CSS, Swiper.js
- **Sem frameworks:** Site estático puro
- **Sem bundler:** Ficheiros servidos diretamente

## Regras para Alterações de Arquitetura
⚠️ **IMPORTANTE:** Antes de grandes alterações na arquitetura, SEMPRE:
1. Consultar o sub-agente **Tech Lead** (usar Task tool)
2. Obter aprovação para mudanças que afetem:
   - Estrutura de pastas
   - Adição de frameworks/bibliotecas
   - Mudanças no sistema de navegação
   - Alterações no sistema de build/deploy

## Estrutura de Ficheiros
```
GT-Movel/
├── index.html              # Homepage com carrossel
├── assets/
│   ├── css/style.css      # Estilos customizados
│   ├── js/main.js         # JavaScript principal
│   └── js/contact.js      # Lógica do formulário
├── contactos/             # Página de contactos
├── portfolio/             # Galeria de projetos
├── sobre/                 # Sobre a empresa
└── eletrodomesticos/      # Página Tien21
```

## Padrões de Código
- JavaScript: ES6+ vanilla (sem transpilação)
- CSS: Classes utilitárias Tailwind + custom CSS
- HTML: Semântico e acessível
- Mobile-first responsive design
