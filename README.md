# Hach&Change 2021 hackathon - Data engineering (kafka-spark-sql)
## team bbyby

Файлы с кодом для хакатона представлены в формате ipynb. Они запускались на Google Collab, датасеты загружались на Google drive

1) bbyby_Voice_and_data_traffic: содержит код по формированию исторического профиля клиента. На выходе получаются датасеты data_traffic, voice_traffic, client_profile. Датасеты загружаются в MongoDB в формате JSON. Есть вариант реляционного хранения (SQLlite)

2) bbyby_Kafka_streaming: содержит код по загрузке топиков в Кафка с попыткой выгрузки в Spark Streaming
