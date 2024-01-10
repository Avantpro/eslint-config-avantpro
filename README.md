# eslint-config-avantpro

Configuração ESLint usada pelo avantpro

## O que está incluído?

- Base de configuração padrão
- Prettier

## Setup

### Node.js

Instalar dependências:

```
npm i -D eslint prettier @avantpro/eslint-config/node @typescript-eslint/parser eslint-config-prettier eslint-plugin-import-helpers eslint-plugin-prettier

ou

yarn add -D eslint prettier @avantpro/eslint-config/node @typescript-eslint/parser eslint-config-prettier eslint-plugin-import-helpers eslint-plugin-prettier


```

Dentro do `.eslintrc.json`

```
{
  "extends": "@avantpro/eslint-config/node"
}
```
