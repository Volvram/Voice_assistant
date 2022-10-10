# Voice_assistant
#Установка пакетного менеджера PIP:
1.	Проверяем  командой в терминале установлен ли pip
 py -m pip --version
2.	Если нет – устанавливаем:
 py get-pip.py
3.	Если есть – обновляем
 python -m pip install --upgrade pip
# Установка пакетов:
1.	Заходим на PYPI.ORG – репозиторий фреймворков и библиотек для Python. Вводим строку поиска «SpeechRecognition». Устанавливаем пакет:
 pip install SpeechRecognition
2.	Вводим pyttsx3. Устанавливаем пакет:
 pip install pyttsx3
3.	Устанавливаем пакет gTTS (Google Text-to-Speech). gTTS представляет собой API Google Translate – библиотеку преобразования текста в речь. Позволяет записать озвученные mp3 данные в файл, файловый объект (байтовую строку) для дальнейшей обработки звука или в стандартный поток stdout
 pip install gTTS
4.	Устанавливаем пакет PyAudio 0.2.11
 pip install PyAudio
