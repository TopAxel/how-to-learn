# __Научиться учиться__ 
## проект от [яндекс.практикум](https://practicum.yandex.ru/web/) ## 

# описание проекта: 
## одностраничный сайт посвещенный  эффективным подходам к обучению ## 
___
# Функциональности: #
1. CSS-анимации с помощью @keyframes 
```css
@keyframes rotation {
    from {
      transform: rotate(0deg);
    }
  
    to {
      transform: rotate(360deg);
    }
  }
 .rotation {
    animation: rotation 20s linear infinite normal;
  }
```
*пример анимации:*

![maygif](../how-to-learn/images/gif/%D0%90%D0%BD%D0%B8%D0%BC%D0%B0%D1%86%D0%B8%D1%8F.gif)

2. Встроенные видео (YouTube IFrame Player API)
```html
<iframe class="video__iframe" src="https://www.youtube.com/embed/5MgBikgcWnY" title="YouTube video player"
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
            allowfullscreen></iframe>
```
3. встроенные картинки 

# Технологии: #
* CSS
* HTML
* БЭМ
* Файловая структура по БЭМ 
* Медиафайлы 

