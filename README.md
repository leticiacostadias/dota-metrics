yarn create next-app project-name
yarn add typescript @types/node @types/react eslint -D

Renomear arquivos .js para .tsx ou .ts

Remover dependências do boilerplate:
    - imagens no public
    - estilos no _app.tsx e no index.tsx

yarn dev

yarn eslint --init

Remover package-lock.json

yarn

Adicionar extensão do eslint
Adicionar no settings.json:
"editor.codeActionsOnSave": {
    "source.fixAll.eslint": true
}

yarn add prettier eslint-plugin-prettier eslint-config-prettier -D

Adicionar configurações do eslint e eslintignore

Adicionar prettier.config.js
```
module.exports = {
    semi: false,
    singleQuote: true,
    arrowParens: 'avoid',
    trailingComma: 'none',
    endOfLine: 'auto'
}
```

Corrigir arquivos