# ChatWithAI (React Native + Expo)

Это мобильное приложение на React Native, которое позволяет общаться с AI (GPT-4.1), а также поддерживает выбор интерфейса чата в стиле **WhatsApp** или **Telegram**.

##  Возможности

-  Простой интерфейс чата
-  Интеграция с OpenAI GPT-4.1 API
-  Переключение между стилями WhatsApp и Telegram
-  Долгий тап по сообщению — копирует текст в буфер обмена
-  Кнопка "Отправить" меняет цвет в зависимости от выбранной темы

##  Технологии

- [React Native](https://reactnative.dev/)
- [Expo](https://expo.dev/)
- [expo-clipboard](https://docs.expo.dev/versions/latest/sdk/clipboard/)
- OpenAI 4.1 (GitHub Models Proxy)

##  Установка
1. Клонируй репозиторий:
git clone https://github.com/ТВОЙ_ЮЗЕР/chatbot.git
cd chatbot
2. В файле ChatWithAI.tsx после строки:
} from "react-native";
добавьте следующий код (для временного тестирования токена и модели):
const TOKEN = "sk-ваш_секретный_токен"; // 🔒 Не забудьте позже вынести в .env
const ENDPOINT = "https://models.github.ai/inference";
const MODEL = "openai/gpt-4.1";
3.Запусти приложение:
npx expo start
