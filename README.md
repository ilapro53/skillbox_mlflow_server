## Запуск

1. `cd mlflow-server && docker-compose up -d --build`
2. Открыть http://localhost:9001/
3. Ввести логин, пароль
4. Вкладка [Buckets](http://localhost:9001/buckets)
5. "[Create Bucket](http://localhost:9001/buckets/add-bucket)"
6. Имя баккета: "datasets"
7. Создать
8. Загрузить в баккет файл "kinopoisk_train.csv"
10. Запустить `train.py`: `cd .. && python train.py`
