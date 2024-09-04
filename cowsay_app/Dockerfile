# Используем официальный базовый образ Python
FROM python:3.9-slim

# Устанавливаем рабочую директорию внутри контейнера
WORKDIR /app

# Копируем файлы requirements.txt и app.py в контейнер
COPY requirements.txt ./
COPY app.py ./

# Устанавливаем зависимости
RUN pip install --no-cache-dir -r requirements.txt

# Команда запуска приложения
CMD ["python", "./app.py"]
