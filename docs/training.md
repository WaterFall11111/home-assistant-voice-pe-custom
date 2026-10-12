```markdown
# Обучение своей фразы активации (Wake Word)

Если вы хотите переобучить колонку на свой собственный триггер (например, «Эй Марс» или любое другое имя):

1. Используйте **microWakeWord-Trainer-AppleSilicon** (на Mac) или оригинальный **microWakeWord Trainer**.
2. Запишите сэмплы своего голоса и сгенерируйте датасет.
3. Обучите модель в формате INT8 Quantized `.tflite`.
4. Сформируйте `json` манифест.
5. Положите готовые файлы `.json` и `.tflite` в папку `/config/esphome/wake_words/` на Home Assistant.
6. Укажите новый имя файла модели в `home-assistant-voice.yaml`.