FROM node:16-alpine

# Задаем рабочую директорию
WORKDIR /home/ilovedocker/app

# Копируем файл hello.sh в рабочую директорию
COPY hello.sh ./

# Задаем скрипт hello.sh в качестве команды запуска образа
ENTRYPOINT ["sh", "hello.sh"]