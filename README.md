# LR6
Лабораторная работа №6
#### Настройка конфига командой git --global. Результаты изменений.
![](ForLABA6\НАЧАло.png)
#### Переход к рабочей папке
![](ForLABA6\RouteToFile.png)
#### Клонирование удаленного репозитория
![](ForLABA6\Clone.png)
#### Переход в папку с репозиторием
![](ForLABA6\AddRepositoryWithReadyFile.png)
#### Изменения репозитория в GitHub и обновление копии 
![](ForLABA6\CreateANewFile.png)

![](ForLABA6\GitPullLL.png)

##  Работа с ветками
#### Список всех веток
![](ForLABA6\SPISOk.png)

#### История операций в ветке master
![](ForLABA6\Story.png)

#### Переход в другую ветку
![](ForLABA6\Переходнабренч.png)
#### История операций в ветке branch1
![](ForLABA6\Branch1.png)
#### Слияние ветки branch1 к master. Конфликт разрешается командой mergetool
![](ForLABA6\MErge.png)
#### Переход на редактор Vim, использование команды diffoff
![](ForLABA6\Diff.png)
#### Редактирование файла mergefile.txt
![](ForLABA6\Применениеdiffoff.png)
#### Результат работы в Vim
![](ForLABA6\Результатmergetool.png)
#### Удаление побочной ветки branch1
![](ForLABA6\Удалениеветки.png)
## Перегрузка репозитория / создание коммитов
#### Добавление файлов
![](ForLABA6\Добавлениефайлов.png)
#### Фиксация изменений в коммите
![](ForLABA6\Всекоммиты.png) 
#### Откад до нижнего коммита в 1, 2 шага
![](ForLABA6\Откатдонижнегокоммита.png) 

## Заполнение отчета в README.md
#### Ветка отчет
![](ForLABA6\Отчет.png) 
## Отчет в текстовам редакторе
![](ForLABA6\Работа.png)

## Лог коммитов в текстовом формате. Численность коммитов обусловлена откатом к самому старой версии репозитория
![](ForLABA6\Комитинг.png)

## Лог команд
```
    $ cd ../SUAI/laba6/
    $ git clone https://github.com/YariLAN/LR6
    $ git pull
    $ git branch -l
    $ git log
    $ git checkout branch1
    $ git merge branch1
    $ git mergetool
    $ git status
    $ git rm <file>/<folder>
    $ echo > <file>
    $ git add . / <file> / <folder>
    $ git commit -m "merge"
    $ git commit -m "add text file"
    $ git commit -m "delete index.html of old/new version"
    $ git reset --hard HEAD~1
    $ git checkout -b otchet
    $ git log --pretty 
```
####