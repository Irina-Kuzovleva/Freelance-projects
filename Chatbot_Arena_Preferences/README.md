## Прогнозирование предпочтений пользователей чат-ботов


Существует сервис Chatbot Arena, где разные чат-боты работающие на основе больших языковых моделей (LLM), генерируют ответы на запросы пользователей. Пользователь печатает запрос, два чат-бота предлагают свои ответы, пользователю необходимо выбрать, какой из ответов наиболее подходящий - у первого бота, второго, либо получается ничья - оба бота одинаково справились с ответами/ни один из ботов не дал подходящего ответа.

Необходимо разработать модель, которая будет предсказывать, какой чат-бот предпочтут пользователи. 

Сайт Chatbot Arena: https://lmarena.ai/

**Результат**: В рамках соревнования на платформе Kaggle разработала модель, которая будет предсказывать, какой чат-бот предпочтут пользователи. Это поможет улучшить взаимодействие чат-ботов с людьми,сделать их более соответствующими человеческим предпочтениям.

Была проанализирована текстовая информация и числовые данные. Без использования больших нейросетевых моделей получилось добиться достаточно высокого качества предсказания за сравнительно небольшое количество времени. Итоговая метрика отличается от метрики победителя соревнования примерно на 12%. 

**Стек**: python, pandas, numpy, scipy, spaCy, CountVectorizer, sklearn, RandomizedSearchCV, XGboost, big data, NLP, языковые модели, kaggle
