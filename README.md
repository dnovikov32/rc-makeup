# reform-city.ru makeup

### Информация
- Frontend http://reform-city.t1000.su  
- Backend http://admin.reform-city.t1000.su  
- Репозиторий проекта https://bitbucket.org/novikovd/rc/src/master/

### Ресурсы
- Кое-какие изображения, например, изображения категорий 
  каталога для главной страницы [/app/frontend/web/images/](https://bitbucket.org/novikovd/rc/src/master/app/frontend/web/images/)

- Svg иконки [/app/frontend/assets/src/svg/](https://bitbucket.org/novikovd/rc/src/master/app/frontend/assets/src/svg/)

- Шаблоны [/app/frontend/views/layouts/](https://bitbucket.org/novikovd/rc/src/master/app/frontend/views/layouts/) 
  и [/app/frontend/themes/](https://bitbucket.org/novikovd/rc/src/master/app/frontend/themes/)
  
### Пожелания

Сделать сайт чуть-чуть больше по ширине, чем на макетах.  
Максимальная ширина ~1280px, примерно, как [тут](http://reform-city.t1000.su/)  
Я использовал Bootstrap grid с такими breakpoints:
```scss
$grid-breakpoints: (
    xxs: 0,
    xs: 468px,
    sm: 576px,
    md: 768px,
    lg: 992px,
    xl: 1280px
);
```

Хотелось бы иметь возможность переиспользовать некоторые 
повторные/похожие блоки на других страницах сайт.
Т.е. иметь верстку таких блоков не прибитую к странице или родительскому блоку.

Пример повторных блоков:
- Блок "Скидка 35%" на главной странице
- Постеры "Карта покупок" и "Советы" на главной странице
- Блок "Сопутствующие товары" на странице товара
- Блок "Правое меню"

Хотелось бы обойтись 3-я шрифтами (без italic):
- MuseoSansCyrl300 - light
- MuseoSansCyrl500 - normal
- MuseoSansCyrl700 - bold

Я бы не отказался от использования Boostrap 5
