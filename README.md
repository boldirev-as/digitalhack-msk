# Geekbrains сервис для создания конспектов

## Demo 
https://bobs-ai.ru

## Запуск решения
1) Укажите env переменные, как в .env.example файле
2) Запустите контейнер
```bash
docker compose up -d
```

## Запуск решения вместе с генеративной моделью Saigа
- Для запуска обязательно установить gpu драйвера на вашем сервере
- Рекомендуемое железо Intel Xeon E-2236 3.4 ГГц, GPU A2 16 ГБ GDDR6 и лучше
- Убедиться, что решение запускается на gpu 

1) Укажите env переменные, как в .env.example файле
3) Раскомментируйте сервис worker в docker-compose.yml
2) Запустите контейнер
```bash
docker compose up -d
```