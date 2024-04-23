# Health Check

Небольшая утилита, которая проверяет доступность веб-сайта по указанному домену и порту.

## Использование

1. Клонирование репозитория

```git clone https://github.com/RaidoRazor/Go-Health-Check.git```

2. Переход в директорию Go-Health-Check
   
```cd Go-Health-Check```

3. Ввод команды в терминале

```go run . --domain <домен сайта>```

Пример:

```go run . --domain google.com```

Вывод:

[UP] google.com is reachable, 

 From:192.168.1.138:54936

 To: 87.240.129.133:80