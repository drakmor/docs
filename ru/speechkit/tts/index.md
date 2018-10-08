# Синтез речи

_Синтез речи (text-to-speech — tts)_ — это процесс генерирования речи по печатному тексту. SpeechKit позволяет озвучить любой текст на нескольких языках. При этом можно выбрать голос (мужской или женский) и интонацию.

## Языки {#2}

- русский
- английский


## Качество синтеза

Под качеством синтезированной речи понимается сходство с человеческим голосом и способность передать эмоции с помощью интонаций.

Особенность технологии синтеза в Яндексе — мы не склеиваем фрагменты реальной речи, а обучаем акустическую модель на речи диктора. Для этого используется статистический подход на базе рекуррентных нейронных сетей. Тембр голоса, созданного таким образом, несколько искусственный, но речь получается плавной, а интонации естественными.

Статистический подход также позволяет менять параметры уже существующих голосов. Благодаря этому можно выбирать интонацию, с которой произносится текст.

# См. также
- [Речевые технологии Яндекса (пост на Хабрахабре)](https://habrahabr.ru/company/yandex/blog/243813/)
- [Под капотом у Yandex.SpeechKit (пост на Хабрахабре)](https://habrahabr.ru/company/yandex/blog/198556/)