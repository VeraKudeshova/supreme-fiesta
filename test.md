# Знакомство с контролем версий
# Лекция1
* Контроль версий (контроль исходного кода) - практика, которая позволяет отслеживать изменения исходного кода и управлять им.
## Контроль версий необходим, чтобы:
1.  *хранить разные версии проекта;*
2.  *возвращаться к разным версиям проекта.* 
* Система контроля - это реализованная возможность замены информации с использованием сохраненных версий.

**Git** - самая популярная система контроля версий, но не единственная. Алгоритмы работы подобных систем схож.

## Команды Git ![Команды])(Команды Git.png)

* *git init* -  указываем папку, в которой
git начнёт отслеживать изменения
* *git status* - показывает текущее состояние гита, есть ли изменения, которые нужно закоммитить
* *git add* - добавляет содержимое рабочего каталога
* *git commit* - зафиксировать или сохранить
* *git log* - журнал изменений
* *git checkout* - переключение между версиями
* *git checkout master* - возврат в версию, где работаете
* *git diff* - показывает разницу между текущим файлом
и сохранённым

 # Лекция 2
 ## Ветвление
Новая команда *git branch* - позволяет создавать и просматривать новые ветки 

Новая команда *git merge* - позволяет совершать слияние любой ветки с текущей
## Команды Git
* *git branch* - просмотр всех веток
* *git branch <название новой ветки>* - создание новой ветки
* *git checkout <название ветки>* - переключение между ветками
 * *git merge <имя ветки для слияния с текущей>* - слияние любой ветки с текущей
* *git branch -d <название ветки>* - удаление ветки
* *.gitignore* - исключение ненужных файлов из загрузки
* *git log --graph* - визуализация всех веток в виде дерева
# Лекция 3
## Работа с удаленным репозиторием
## Команды Git
* *git clone* - копирование внешнего репозитория на свой ПК
* *git pull* - команда позволяет скачать всё из текущего репозитория и автоматически сделать merge с нашей версией
* *git push* - команда позволяет отправить нашу версию репозитория на внешний репозиторий
* *pull request* - команда для предложения изменений, запрос на вливание изменений в репозиторий.
 ## Спасибо за внимание!
