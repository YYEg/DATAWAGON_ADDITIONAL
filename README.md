# Прогнозирование спроса на грузовые железнодорожные перевозки

## Описание репозитория

### Основной трек
- `Result.ipynb`: Ноутбук с базовым решением и метриками.

### Парсинг тендеров
- `DATA_MAP.py`: Скрипт для обработки и визуализации данных о грузовых тендерах.
- `parser.py`: Скрипт для парсинга URL-адресов тендеров с веб-сайта roseltorg.ru.
- `tenders_data.json`: Файл с обработанными данными тендеров.
- `tenders_map.html`: Интерактивная карта с визуализацией распределения тендеров.
  
### Оценка результата
- `Hackathon_-_baseline_and_metric_scripts.ipynb`: Ноутбук с примерами оценки результатов и метриками.

## Описание скриптов

### DATA_MAP.py
- Очищает данные, создает интерактивную карту России с маркерами тендеров и их характеристиками.
- Визуализирует распределение тендеров в различных регионах.

### parser.py
- Собирает данные о грузовых тендерах с веб-сайта roseltorg.ru.
- Создает файл с URL-адресами тендеров и файл с обработанными данными тендеров в формате JSON.

## Зачем это полезно для хакатона?

1. **Сбор данных**: `parser.py` собирает актуальные данные о грузовых тендерах, обеспечивая наличие информации для обучения модели.

2. **Обработка данных**: `DATA_MAP.py` предварительно обрабатывает и чистит данные, подготавливая их для анализа и ввода в модель.

3. **Геопространственная визуализация**: `DATA_MAP.py` визуализирует распределение тендеров на интерактивной карте, предоставляя пространственную перспективу на спрос на грузоперевозки в различных регионах.

4. **Анализ и выводы**: Обработанные данные и визуализации служат входом для построения прогностических моделей, улучшая точность прогнозирования спроса.

## Ссылка на интерактивную карту
[Карта с распределением тендеров](https://data-wagon.vercel.app/)

