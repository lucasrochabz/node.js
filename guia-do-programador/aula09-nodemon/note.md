### Instalação Global (para usar em qualquer projeto)

Instalar o Nodemon globalmente permite que você o use diretamente no terminal, sem precisar adicioná-lo como dependência em cada projeto.

Use o comando:

```
npm install -g nodemon
```

Após instalar, você pode executar sua aplicação com o comando:

```
nodemon <arquivo>
```

### Instalação no Projeto (para uso específico no projeto)

Caso prefira instalar o Nodemon apenas no projeto, adicione-o como uma dependência de desenvolvimento:
npm install --save-dev nodemon

Em seguida, configure um script no seu package.json para facilitar o uso:

```
"scripts": {
"dev": "nodemon src/index.js"
}
```

Agora, você pode iniciar sua aplicação com o comando:

```
npm run dev
```
