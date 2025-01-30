# Дискретная математика.
Это репозиторий с моими заметками и курсами, касающиеся
- (наивной) теории множеств
- теории графов
- комбинаторики
и любой математики, которую принято называть "дискретной".

На данный момент в репозитории есть только учебные ветки вида ``hse$YEAR$-mod$N$-$specialization$``
- в ``src/homeworks/`` лежат исходники листков из ДЗ
- в ``src/practices/`` лежат исходники листков с семинаров
- в ``src/notes/`` лежат заметки

### Сборка листочков

- Убедитесь что у вас есть две следующие символические ссылки 
    - ```src/homeworks/images/```   
    - ```src/practices/images/```  
    - ```src/notes/images/```  

на директорию ```images/``` в корне репозитория. Также, установите и настройте пакеты ``minted`` и ``memorize``. 

Команда для сборки:
```shell
    lualatex --shell-escape --output-dir=%WORKSPACE_FOLDER%  filename.tex
```
где ```%WORKSPACE_FOLDER%``` это корневая директория репозитория (возможно потребуется сборка два раза)


