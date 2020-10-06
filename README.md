Это чистый шаблон Django проекта, с которым можно быстро начать разработку.

Установка представляет собой просто указание Python интерпретатора. Запустите:

```bash
./install.sh
```

В конфиге Django заполните настройки базы данных (`src/config/settings.py`).

Если у вас не активировалось виртуальное окружение выполните:

```bash
sourse env/bin/acrtivate
```

Перейти в дирректорию `src` и выполняем миграции:

```bash
python manage.py migrate
```

Вот и все!
