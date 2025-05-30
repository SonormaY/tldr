# git annotate

> Показує хеш коміту і останнього автора на кожному рядку у файлі.
> Дивіться `git blame`, якій варто віддати перевагу над `git annotate`.
> `git annotate` призначена для тих, хто знайомий із іншими системами контролю версій.
> Більше інформації: <https://git-scm.com/docs/git-annotate>.

- Виводить файл з ім'ям автора та хешем коміту доданими поперед кожного рядку:

`git annotate {{шлях/до/файлу}}`

- Виводить файл з електронною поштою автора та хешем коміту доданими поперед кожного рядку:

`git annotate {{[-e|--show-email]}} {{шлях/до/файлу}}`

- Виводить лише рядки, які відповідають регулярному виразу:

`git annotate -L :{{регулярний_вираз}} {{шлях/до/файлу}}`
