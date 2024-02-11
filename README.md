# Product for creating glossary from recorded lecture

## Demo 
https://bobs-ai.ru

Dream team
![image](https://github.com/boldirev-as/digitalhack-msk/assets/60057518/a090c2d1-8afb-4864-ab2c-9c6ed53ecae8)




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
