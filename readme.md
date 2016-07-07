# Bower-пакет - 4gekkman-bower-cssgrids
---
## Оглавление

  - [Ссылки](#link1)
  - [Описание](#link2)
  - [Инструкция (для меня) по созданию новых bower-пакетов](#link3)
  - [Заметки к релизам](#link100)

---

## Ссылки <a id="link1"></a>
```

  > Адрес репозитория bower-пакета 4gekkman-bower-cssgrids на github
      https://github.com/4gekkman/4gekkman-bower-cssgrids

	
			
```

## Описание <a id="link2"></a>
```

  • Этот bower-пакет содержит адаптивные CSS-сетки.
  • Это требуется, поскольку сетка от bootstrap не всегда подходит.
  • Тут есть 2 версии адаптивных сеток: на float, и на position.
  • 
 
```
## Инструкция (для меня) по созданию новых bower-пакетов <a id="link3"></a>
```

  • Скопировать каталог "4gekkman-bower-sample".
  • Заменить "sample" на что-нибудь другое, например: "4gekkman-bower-jslibrary".
  • Отредактировать файлы "bower.json", "composer.json" и "readme.md".
  • Выполнить в каталоге:
    ▪ git init
    ▪ git remote add <имя пакета> git@github.com:4gekkman/<имя пакета>.git 
  • Добавить задачу авто-push на github в файл "GitAutoPushScripts.ps1".
  • Добавить, собственно, фронтенд-файлы в каталог.
  • Выполнить push нового пакета на github, введя: push
  • Зайти на github и создать новый релиз с тегом "1.0.0".
  • Зарегистрировать в репозитории bower имя для нового пакета:
    ▪ Например: bower register example git://github.com/user/example.git
 
```
## Заметки к релизам <a id="link100"></a>
```

  1.0.0
    - Первый релиз.

```










