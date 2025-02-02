# 🌌 Звёздное небо с созвездиями

![Starry Sky](https://your-image-link.com/banner.png)

## ✨ О проекте
Этот проект представляет собой **интерактивное звёздное небо** с перспективой, живым фоном и отображением созвездий. Он позволяет **визуализировать ночное небо** с возможностью **добавления новых созвездий**.

## 🌟 Возможности
✅ Реалистичное звёздное небо с перспективой  
✅ Анимированные **звёзды и кометы**  
✅ Визуализация **известных созвездий**  
✅ Динамическое добавление **новых созвездий**  
✅ Живой фон, имитирующий **изменение цвета ночного неба**  

## 🤝 Как помочь проекту
Мы ищем энтузиастов, которые могут помочь с:
- 📝 **Добавлением новых созвездий** в `constellations.json`
- 🎨 **Улучшением визуального отображения**
- 🚀 **Оптимизацией рендеринга звёзд**
- 🔍 **Добавлением новых функций**, например, **выделение созвездий** или **их поиск**

### 📌 Как добавить новые созвездия
1. Откройте файл `constellations.json`
2. Добавьте новый объект в массив:
   ```json
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
   ```
3. Сохраните изменения и **протестируйте в браузере**.

Затем откройте **`index.html`** в любом современном браузере и наслаждайтесь! 🚀

## ⭐ Поддержка проекта
Если вам нравится этот проект и вы хотите помочь, **пожалуйста, внесите свой вклад** или **оставьте звезду** ⭐ на нашем GitHub!

[![GitHub Stars](https://img.shields.io/github/stars/your-repo/starry-sky?style=social)](https://github.com/your-repo/starry-sky)

---

# 🌠 Starry Sky with Constellations

![Starry Sky](https://your-image-link.com/banner.png)

## ✨ About the Project
This project is an **interactive starry sky** with perspective, a live background, and constellation rendering. It allows you to **visualize the night sky** and **dynamically add new constellations**.

## 🌟 Features
✅ **Realistic starry sky with perspective**  
✅ **Animated stars and comets**  
✅ **Visualization of known constellations**  
✅ **Dynamic addition of new constellations**  
✅ **Live background simulating night sky color changes**  

## 🤝 How to Contribute
We are looking for contributors to help with:
- 📝 **Adding new constellations** to `constellations.json`
- 🎨 **Improving visual representation**
- 🚀 **Optimizing star rendering**
- 🔍 **Adding new features** such as **constellation highlighting** or **search**

### 📌 How to Add New Constellations
1. Open `constellations.json`
2. Add a new object to the array:
   ```json
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
   ```
3. Save the changes and **test in the browser**.

Then open **`index.html`** in any modern browser and enjoy! 🚀

## ⭐ Support the Project
If you like this project and want to help, **please contribute** or **give a star** ⭐ on our GitHub!

[![GitHub Stars](https://img.shields.io/github/stars/your-repo/starry-sky?style=social)](https://github.com/your-repo/starry-sky)

