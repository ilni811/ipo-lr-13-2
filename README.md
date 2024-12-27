## Задание 1

- Создать два связанных класса:
    - **ImageHandler** — класс для базовой работы с изображениями (загрузка, сохранение, изменение размеров и форматов).
    - **ImageProcessor** — класс для обработки изображения (применение фильтров, добавление текста, поворот).
- Класс **ImageHandler** должен:
    - Принимать путь к изображению при инициализации.
    - Содержать методы для загрузки изображения, сохранения и изменения его размера.
    - Обеспечивать передачу изображения в класс **ImageProcessor**.
- Класс **ImageProcessor** должен:
    - Принимать изображение, переданное из **ImageHandler**.
    - Содержать методы для применения различных фильтров, добавления текста и других эффектов.

<aside>
🚨

В каждом классе нужно реализовать свой функционал, указанный в варианте далее

</aside>

**Картинки для работ:**

[картинки для лабы.rar](https://prod-files-secure.s3.us-west-2.amazonaws.com/d9fc6719-e1f9-49a0-8e26-8e1860bb2010/91d02c40-9eb1-4ec6-86d4-d140f669dee9/%D0%BA%D0%B0%D1%80%D1%82%D0%B8%D0%BD%D0%BA%D0%B8_%D0%B4%D0%BB%D1%8F_%D0%BB%D0%B0%D0%B1%D1%8B.rar)

# Индивидуальные задания

---

## Задание 2

### **Вариант 1**

1. В классе **ImageHandler**:
    - Реализовать метод изменения размера изображения до 300x300 пикселей.
    - Реализовать метод сохранения изображения в формате PNG.
2. В классе **ImageProcessor**:
    - Применить фильтр размытия (Blur).
    - Добавить текст "Вариант 1" в нижнем правом углу изображения.

### **Вариант 2**

1. В классе **ImageHandler**:
    - Реализовать метод для загрузки изображения и поворота его на 90 градусов.
    - Реализовать метод для обрезки изображения (crop) до размера 150x150 пикселей.
2. В классе **ImageProcessor**:
    - Применить чёрно-белый фильтр (convert('L')).
    - Добавить текст "Вариант 2" в верхнем левом углу изображения.

### **Вариант 3**

1. В классе **ImageHandler**:
    - Реализовать метод для уменьшения изображения (thumbnail) с максимальными размерами 200x200 пикселей.
    - Реализовать метод для сохранения уменьшенного изображения с новым именем.
2. В классе **ImageProcessor**:
    - Применить фильтр контуров (CONTOUR).
    - Добавить текст "Вариант 3" в центре изображения.

### **Вариант 4**

1. В классе **ImageHandler**:
    - Реализовать метод для изменения формата изображения на JPG.
    - Реализовать метод для поворота изображения на 45 градусов.
2. В классе **ImageProcessor**:
    - Применить фильтр повышения резкости (SHARPEN).
    - Добавить рамку вокруг изображения с шириной 15 пикселей.

### **Вариант 5**

1. В классе **ImageHandler**:
    - Реализовать метод для масштабирования изображения до 50% от его исходного размера.
    - Реализовать метод для сохранения изображения с добавлением текущей даты к имени файла.
2. В классе **ImageProcessor**:
    - Применить фильтр "Эмбосс" (EMBOSS).
    - Добавить водяной знак "Вариант 5" (полупрозрачный текст) в правом нижнем углу изображения.
