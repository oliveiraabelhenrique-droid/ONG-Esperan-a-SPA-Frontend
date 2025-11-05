# ONG-Esperan-a-SPA-FrontendAplicação Aplicativo de Página Única (SPA) para apresentação da ONG Esperança: missão, projetos, campanhas de doação e cadastro de voluntários/doadores.

Visão geral
SPA com navegação por hash e injeção dinâmica de templates
Validação de formulários com feedback ao usuário
Máscaras para CPF, telefone e CEP
Componentes de UI: menu acessível, modal de doação, cartões e crachás
Estrutura modular em JavaScript e CSS organizada
Demonstração
Página inicial com hero, histórico e imagem da equipe
Seções de projetos (Educação, Saúde, Campanha Inverno Solidário)
Modal de ação com ações acessíveis
Formulário de cadastro com validação e máscaras.

Estrutura do projeto
├── 📁 assets
│   ├── 📁 css
│   │   ├── 🎨 00-variables.css
│   │   ├── 🎨 01-base.css
│   │   ├── 🎨 02-layout.css
│   │   ├── 🎨 03-components.css
│   │   ├── 🎨 04-utils.css
│   │   └── 🎨 style.css
│   └── 📁 js
│       ├── 📄 form-validation.js
│       ├── 📄 main.js
│       ├── 📄 masks.js
│       ├── 📄 menu.js
│       ├── 📄 modal.js
│       ├── 📄 spa.js
│       └── 📄 templates.js
├── 📁 img
│   ├── 🖼️ doacoes.jpg
│   ├── 🖼️ doacoes.png
│   ├── 🖼️ equipe2.jpg
│   ├── 🖼️ equipe2.png
│   ├── 🖼️ imagem1.png
│   ├── 🖼️ imagem2.jpg
│   ├── 🖼️ projeto-educacao.jpg
│   ├── 🖼️ projeto-educacao.png
│   ├── 🖼️ projeto-saude.jpg
│   └── 🖼️ projeto-saude.png
├── 🌐 cadastro.html
├── 🌐 index.html
└── 🌐 projetos.html

Execução
Requisitos
Qualquer servidor estático (ex.: VSCode Live Server, http-server, Nginx) ou abrir via file://
Rodando localmente
Clonar o:
git clone https://github.com/Jefferson-Santana-Santos/Desenvolvimento-Web_Jefferson-/tree/main/Experi%C3%AAncia%20pr%C3%A1tica%20IlI

cd Desenvolvimento-Web_Jefferson-/tree/main/Experi%C3%AAncia%20pr%C3%A1tica%20IlI

Sirva os arquivos estaticamente (exemplos):
VSCode: extensão Live Server → “Go Live”
Nó: npx http-server .e acessarhttp://localhost:8080
Acesse index.html. Use o menu para navegar ( #home, #projetos, #cadastro).
Funcionalidades
SPA básico:
spa.jsinjeta templates não <main id="conteudo">conforme o hash da URL.
Modelos:
templates.jscontém home, projetose cadastro.
Validação de:
form-validation.jsverifica campos obrigatórios, formatos e exibe mensagens.
Máscaras:
masks.jsaplica máscara no CPF, telefone e CEP durante a digitação.
Modal de doação:
modal.jsabre/fecha via atributos data-modal-opene data-modal-close.
Menu da tarde:
menu.jscontrole o hambúrguer e o menu mobile com estados ARIA.
Convenções de código
JavaScript modular por funcionalidade
CSS organizado por camadas (variáveis, base, layout, componentes, importados)
Commits no padrão Commits Convencionais (ex.: feat(spa): ..., fix(images): ...)
Roteiro, problemas e PRs
Conquistas:
M1: Estrutura SPA
M2: Validação + máscaras
M3: UX (menu, modal, imagens)
M4: Documentação
Issues e PRs com templates e referência cruzada (Fecha #ID)
Acessibilidade
Navegação com teclado
ARIA em menus, modais e listas
Alternativas textuais em imagens
Créditos
Conteúdos, imagens e identidade fictícia da ONG Esperança para fins educacionais.
