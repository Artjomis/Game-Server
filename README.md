/game-server
    /cmd
        /server        # основной серверный код
    /internal
        /game          # логика игры
        /auth          # аутентификация
        /match         # управление матчами
        /player        # данные игроков
        /websocket     # WebSocket-сервер
    /pkg
        /db            # работа с базой данных
        /cache         # работа с Redis
        /metrics       # мониторинг и метрики
    /scripts
        /deploy        # скрипты для деплоя
    /docs              # документация
    /Dockerfile        # контейнеризация сервера
    /docker-compose.yml
