# yc-landing

## Установка и настройка

* используетсяnode 7.1 (можно использовать nvm)
* склонировать репозиторий
* `npm i && npm start`
* в качестве вебсервера я использую ws
  * `npm install -g local-web-server`
  * запускаю из папки `public`: `ws -p 2000` 
  * в браузере вбиваю `http://localhost:2000`

Кроме ws ничего глобально ставить не надо. Разве что babel может потребовать sudo права на глобальную установку. 
Можно поставить локально и вызывать из node_modules: `./node_modules/local-web-server/bin/cli.js -p 1900 -d public`

## Используемые технологии
* nodejs 7.1
* webpack 2
* typescript 2.3.4 (latest)
* stylus для верстки


> Думал еще попробовать использовать jade в качестве шаблонизатора; Он для лендинга хороший вариант, но не разобрался сходу, как конвертировать index.html через webpack 2. Нет с ним опыта работы. Только с первой версией
