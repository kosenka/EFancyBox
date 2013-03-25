EFancyBox - FancyBox is a tool for displaying images, html content and multi-media in a Mac-style "lightbox" that floats overtop of web page
=======

## Установка

* Скачать ([zip](https://github.com/kosenka/EFancyBox/zipball/master), [tar.gz](https://github.com/kosenka/EFancyBox/tarball/master)).

* Распаковать архив в папку `application.extensions.EFancyBox` . Должно получиться следующее:

```
protected/
├── components/
├── controllers/
├── ... application directories
└── extensions/
    ├── EFancyBox/
    │   ├── assets/
    │   └── ... другие файлы расширения EFancyBox
    └── ... другие расширения
```

## ССылки

* [Demo](http://kosenka.ru/#tab1)
* [Extension project page](https://github.com/kosenka/EFancyBox)


## Использование
В представлении/шаблоне прописать так:

```php
<? $this->widget('ext.EFancyBox.EFancyBox', array('selector'=>'a[rel=gallery]','options'=>array('overlayColor'=>'#000')));?>
```

