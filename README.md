# model-for-determining-the-shape-of-a-face

Этот проект использует предобученную модель (ResNet18) для классификации формы лица на одну из 5 категорий:

•	Круглое (Round)

•	Овальное (Oval)

•	Прямоугольное (Oblong)

•	Квадратное (Square)

•	Сердцевидное (Heart)

**Установка**

```
git clone https://github.com/Evgeiy23/model-for-determining-the-shape-of-a-face.git
cd model-for-determining-the-shape-of-a-face
pip install -r requirements.txt
```

**Визуализация обучения**

Скрипт сохраняет графики:

•	Потери на train/val

•	Точность

•	Confusion matrix


**Возможные улучшения**

•	Использовать ResNet50 или EfficientNet

•	Детектировать лицо автоматически перед классификацией

•	Веб-интерфейс (Gradio, Streamlit)

•	Telegram-бот
