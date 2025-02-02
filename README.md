Звёздное небо с созвездиями

О проекте

Этот проект представляет собой интерактивное звёздное небо с перспективой, живым фоном и отображением созвездий. Он позволяет визуализировать ночное небо с возможностью добавления новых созвездий.

Возможности

Отображение звёздного неба с реалистичной перспективой

Анимированные звёзды и кометы

Визуализация известных созвездий

Динамическое добавление новых созвездий

Живой фон, имитирующий изменение цвета ночного неба

Как помочь проекту

Мы ищем энтузиастов, которые могут помочь с:

Добавлением новых созвездий в constellations.json

Улучшением визуального отображения

Оптимизацией рендеринга звёзд

Добавлением новых функций, например, выделение созвездий или их поиск

Как добавить новые созвездия

Откройте файл constellations.json

Добавьте новый объект в массив с таким форматом:

{
   "name": "Название созвездия",
   "points": [
     { "x": -30, "y": 15 },
     { "x": -10, "y": 10 },
     { "x": 10, "y": 10 },
     { "x": 30, "y": 15 },
     { "x": 10, "y": 5 }
   ],
   "connections": [
     [0, 1],
     [1, 2],
     [2, 3],
     [1, 4],
     [2, 4]
   ]
}

Сохраните изменения и протестируйте в браузере.

Как запустить проект

Откройте index.html в любом современном браузере

Убедитесь, что файл constellations.json загружен корректно

Наслаждайтесь звёздным небом!

Поддержка проекта

Если вам нравится этот проект и вы хотите помочь, пожалуйста, внесите свой вклад или оставьте звезду ⭐ на нашем GitHub!

_______________________________________________________________________________________________________________________________________

Starry Sky with Constellations

About the Project

This project is an interactive starry sky with perspective, a live background, and constellation rendering. It allows you to visualize the night sky and add new constellations dynamically.

Features

Realistic starry sky with perspective

Animated stars and comets

Visualization of known constellations

Dynamic addition of new constellations

Live background simulating night sky color changes

How to Contribute

We are looking for contributors to help with:

Adding new constellations to constellations.json

Improving visual representation

Optimizing star rendering

Adding new features such as constellation highlighting or search

How to Add New Constellations

Open constellations.json

Add a new object to the array using this format:

{
   "name": "Constellation Name",
   "points": [
     { "x": -30, "y": 15 },
     { "x": -10, "y": 10 },
     { "x": 10, "y": 10 },
     { "x": 30, "y": 15 },
     { "x": 10, "y": 5 }
   ],
   "connections": [
     [0, 1],
     [1, 2],
     [2, 3],
     [1, 4],
     [2, 4]
   ]
}

Save the changes and test in the browser.

How to Run the Project

Open index.html in any modern browser

Ensure that constellations.json loads correctly

Enjoy the starry sky!

Support the Project

If you like this project and want to help, please contribute or give a ⭐ on our GitHub!



