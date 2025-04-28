# SPA com Gulp, Sass e JavaScript

Projeto de estudo de uma **Single Page Application (SPA)** utilizando **Gulp**, **Sass** e **JavaScript**, desenvolvido a partir do curso ministrado por **Leonardo Moreira Leitão** na **Cod3r Cursos Online**.

---

## Tecnologias

- Gulp (automatizador de tarefas)
- Sass (pré-processador CSS)
- JavaScript
- HTML5 & CSS3

---

## Estrutura

```bash
SPA/
├── build/          # Arquivos gerados
├── gulpTasks/      # Tarefas separadas do Gulp
├── node_modules/
├── src/            # Código-fonte
│   ├── assets/     # Imagens, scripts e estilos
│   ├── paginas/    # Páginas da aplicação
│   └── index.html
├── gulpfile.js
├── package.json
└── README.md
```

---

## Desafios e Soluções

- Problemas de referência de arquivos ➔ Corrigido ajustando os caminhos no `index.html` e no JavaScript.
- Live reload não funcionando ➔ Configuração adequada do `gulp-webserver` e `gulp-watch`.
- Compilação do Sass ➔ Utilizado `gulp-sass` corretamente com `require('sass')`.

---

## Agradecimento

Agradeço ao **Leonardo Moreira Leitão** e à **Cod3r Cursos Online** por todo o conteúdo, apoio e incentivo nessa jornada de aprendizado! 🚀

---

> **Obs.:** Projeto criado apenas para fins educativos.  
> 💻 #NeverStopLearning

---
