# AI-ArtInfo

![](https://i.gifer.com/origin/78/78013ac9f22c3c8f5713d28fa31c6211.gif)

## Основная идея проекта:<br>
**Создание телеграмм-бота, помогающий определить автора и стиль картины по фотографии, а также найти по описанию наиболее подходящую картину.** <br>
<br>
Полезные особенности и преимущества:<br>
- Интерфейс на двух языках<br>
- Быстрый доступ к интересующей информации<br>
- Доступная информация для изучения искусства<br>
- Отсутствие необходимости ручного поиска<br>

## Как мы его создали?<br>
- Этот бот использует датасет, который был частично получен из [сайта](https://allpainters.ru/) с использованием спарсинга данных, а частично собран вручную.<br>
- Затем применили [модель](https://huggingface.co/Salesforce/blip-image-captioning-large), чтобы сгенерировать описание для каждой картинки.<br>
- Чтобы бот работал на двух языках использовали модели для перевода датасета: [RU_EN](https://huggingface.co/Helsinki-NLP/opus-mt-ru-en)[EN-RU](https://huggingface.co/Helsinki-NLP/opus-mt-ru-en)<br>
- Для создания функций бота использовали модели: Resnet50 и TfidfVectorizer.<br>

## Алгоритм использования бота<br>
![](img/shema.png)

## Над проектом работали:<br>
[Анна Савицкая](https://github.com/SaviAnn)<br>
[Мария Козлова](https://github.com/MARI-posa)<br>
[Виктория Князева](https://github.com/vvv-knyazeva)<br>

Art Guide
https://drive.google.com/file/d/1nHM5dy5fqjx9ux_hl1cgklgf-ajNrIrF/view?usp=sharing

