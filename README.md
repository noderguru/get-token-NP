```bash
# Склонируйте репозиторий
git clone https://github.com/noderguru/get-token-NP.git

# Перейдите в папку проекта
cd get-token-NP

# Создайте виртуальное окружение
python3 -m venv venv

# Активируйте виртуальное окружение
source venv/bin/activate

# Установите зависимости
pip install -r requirements.txt

# Добавьте прокси и данные аккаунтов в соответствующие файлы

# Запустите скрипт
python3 get_token.py

# Результаты будут в файле token_list.txt
