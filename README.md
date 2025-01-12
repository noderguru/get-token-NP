
# Вытаскиваем токен аккаунта из Nodepay

git clone https://github.com/noderguru/get-token-NP.git

cd get-token-NP

python3 -m venv venv

source venv/bin/activate

pip install -r requirements.txt


добавляем прокси и данные акков в соответствующие файлы.

python3 get_token.py

Результаты будут тут token_list.txt
