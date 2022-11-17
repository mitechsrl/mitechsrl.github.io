## Onit docs builder

This is a jekill builder for onit docs

### Setup

Install ruby and jekill: [https://jekyllrb.com/docs/installation/windows/](https://jekyllrb.com/docs/installation/windows/)

### Template

See [https://pmarsceill.github.io/just-the-docs/](https://pmarsceill.github.io/just-the-docs/)

### Serve or build

Use 
```js
bundle exec jekyll serve // or npm run serve
```
to start a live server, use 
```js
bundle exec jekyll build // or npm run build
```
to build a static website 

### Source md files

Put your source Markdown files into the **docs/** folder


### Helper IVAN

Questo comando genera la documentazione di onit-next partendo dalla directory specifica per il setup mio

```js
npm run build-ivan
```

I files del portale saranno generati in _site.
personalizza _config.yml -> baseurl e destination con la versione per avere un portale all'interno di una cartella per versione