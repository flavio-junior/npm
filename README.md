# npm

**O que é o npm?: ``` - é um gerenciador de pacotes gerenciado pela Node Js. ```**

- **É necessário baixar o node js para utilizar o npm que já vem instalado com node js.**

[Site do npm](https://www.npmjs.com/)

**Ver versão instalada do npm:**
```
npm --version
```

**Crir pacote default:**
```
npm init --yes
```

**Criar pacote respondendo algumas perguntas básicas:**
```
npm init
```

**Para encontrar uma dependência, basta procurar no site e baixar a versão desejada:**
![Screenshot (39)](https://github.com/flavio-junior/npm/assets/59364674/bc097ced-d5dc-463f-b9d8-77a7b77b0b61)

![Screenshot (41)](https://github.com/flavio-junior/npm/assets/59364674/4f6e1fdc-6151-43fe-a811-e87be98c8684)

**Instalar pacote:**
```
npm i lodash
```

**Instalar pacote apenas em desenvolvimento:**
```
npm i typescript --save-dev
```

**Mover pacote de produção para dev:**
```
npm i node-sass --save-dev
```

**Desistalar pacote:**
```
npm uninstall node-sass
```

**Apagar node_modules com o Pawer Shell:**
```
Remove-Item -Recurse -Force ./node_modules
```

## Atenção! A pasta node_modules deve ser ignorada no gitignore.

**Verificar vunerabilidades do pacote:**
```
 npm audit
```

**Forçar correção de vunerabilidades:**
```
npm audit fix --force
```
