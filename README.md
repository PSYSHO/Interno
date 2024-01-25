# Итоговая атестация по курсу FrontEnd разработчик
## Техническое задание

Посмотреть [Техническое задание](https://gbcdn.mrgcdn.ru/uploads/asset/5668666/attachment/5a4b32939f7165e4aeebff3acde8c9b4.pdf)

## Реализованные задачи

1. Применение HTML, CSS, JavaScript, Vue.js.
2. Использование flexbox, Grid, формат изображений svg, png.
3. Использование библиотеки Swiper JS для создания слайдера на странице Project Details (при двойном нажатии на изображение слайдера оно увеличивается для предпросмотра)
4. Реализован компонентный подход для добавления похожих блоков на сайте:
   - Header
   - Footer
   - ArticleCard
   - BlackButton
   - Navigation
   - Pagination
   - Slider
5. Все ссылки работают через VueRouting и являются переходами на страницы, указанные в ТЗ. Нерабочая ссылка ведет на страницу NotFound (404).
6. На странице Blog
   - Реализована пагинация по 6 элементов ( \"Articles & News\")
   - Подгружается последний добавленный пост из статей и новостей (\"Latest Post\")

7. На странице Blog Details
- Добавлены несколько произвольных статей, с описанием. По нажатию на кнопки в разделе «Tags» происходит сортировка статей по хештегам \"Kitchen\", \"Bedroom\", \"Building\", \"Architecture\", \"Kitchen Planning\".

8. На странице Project (\"Our Project\)
   - Реализована пагинация для перемещения по страницам в категориях \"Bathroom\", \"BedRoom\", \"Kitchen\", \"LivingArea\".
   - Добавлен функционал лайков (звёздочки). При наведении на любой компонент проекта изначально звёздочка прозрачная, при нажатии на неё, она окрашивается оранжевым цветом.
9. Кнопка «Back to home» на странице NotFound(404) ведет на главную страницу.
10. Сайт выполнен в десктопной версии.

# Интерьерное бюро \"Interno\". SPA приложение на Vue.js 3.

## Иcпользуемые технологии

- Vue.js 3
- Vuex
- Vue Router
- SCSS
- Flexbox
- Grid
- Git
- Swiper JS library

## Ссылка на макет проекта

Посмотреть [Макет](<https://www.figma.com/file/okdYD45Tj2JpKsNASccUmf/Interior-Design-Webflow-Website-Template-(Community)-(Copy)-(Copy)?type=design&node-id=1-5&mode=design&t=EPP9PdQtvZ8kah8U-0>)

## Ссылка на GitHub Pages

Посмотреть [Сайт Interno]
(https://psysho.github.io/FinalTaskGB/)

## Настройка проекта

```
npm install
```

### Компиляция и выполнение горячей перезагрузки для разработки

```
npm run serve
```

### Компиляция и сжатие для продакшена

```
npm run build
```

### Настройка конфигурации

Посмотреть [Configuration Reference](https://cli.vuejs.org/config/)
