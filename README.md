# Nuxt Very Simple Blog

Este projeto é um blog minimalista desenvolvido com [Nuxt 3](https://nuxt.com/), focado em simplicidade, desempenho e fácil manutenção. Ideal para quem deseja criar um blog rápido, moderno e fácil de personalizar.

## Objetivo

O objetivo deste projeto é fornecer uma base simples para blogs, utilizando Nuxt 3, permitindo que desenvolvedores possam rapidamente criar, publicar e gerenciar posts, além de servir como ponto de partida para customizações e novos recursos.

## Estrutura do Projeto

A estrutura básica do projeto é:

```
nuxt-very-simple-blog/
├── components/      # Componentes Vue reutilizáveis
├── pages/           # Páginas do blog (home, post, etc.)
├── public/          # Arquivos estáticos (imagens, favicon, etc.)
├── assets/          # Estilos, imagens e outros assets
├── composables/     # Funções reutilizáveis (composables)
├── app.vue          # Componente raiz
├── nuxt.config.ts   # Configuração do Nuxt
├── package.json     # Dependências e scripts
└── README.md        # Documentação do projeto
```

## Como Utilizar


### Criando uma cópia em sua conta

Clique com o botão direito em **Copiar Exercício** e abra o link em uma nova aba.

   <a id="copy-exercise" target="_blank" href="https://github.com/new?template_name=nuxt-very-simple-blog&template_owner=jaisonschmidt&name=nuxt-very-simple-blog-class&owner=%40me&visibility=public">
      <img src="https://img.shields.io/badge/📠_Copiar_Exercício-008000" height="30pt"/>
   </a>

### 1. Instale as dependências

Escolha seu gerenciador de pacotes favorito:

```bash
# yarn
yarn install

# npm
npm install

# pnpm
pnpm install
```

### 2. Ambiente de Desenvolvimento

Inicie o servidor de desenvolvimento em http://localhost:3000:

```bash
npm run dev
```

### 3. Build para Produção

Para gerar a versão de produção:

```bash
npm run build
```

Para visualizar o build localmente:

```bash
npm run preview
```

### 4. Estrutura dos Posts

Os posts podem ser organizados na pasta `content/` (ou conforme implementado), geralmente em formato Markdown ou JSON. Consulte a documentação ou o código para detalhes de como adicionar novos posts.

## Personalização

- Adicione ou edite componentes em `components/`
- Crie novas páginas em `pages/`
- Altere estilos em `assets/`
- Configure rotas, plugins e módulos em `nuxt.config.ts`

## Deploy

Para mais informações sobre deploy, consulte a [documentação oficial do Nuxt](https://nuxt.com/docs/getting-started/deployment).

---

Sinta-se à vontade para contribuir ou adaptar este projeto conforme suas necessidades!
