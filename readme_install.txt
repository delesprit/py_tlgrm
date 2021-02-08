Установка pip

Это менеджер пакетов. В версиях выше Python 2.7.9 и Python 3.4, а также на macOS/Linux он уже есть. Проверить это можно командой pip --version в терминале. Если же по каким-то причинам он отсутствует, установить его можно при помощи команды:

$ sudo apt-get install python-pip

Установка pyTelegramBotAPI

Есть два способа установить эту библиотеку:

    С помощью pip:

    pip install pytelegrambotapi

    Из исходников (требуется git):

    $ git clone https://github.com/eternnoir/pyTelegramBotAPI.git
    $ cd pyTelegramBotAPI
    $ python setup.py install

