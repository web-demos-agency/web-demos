# Стратегия первого контакта: "Double-Tap Automation"

Этот воркфлоу описывает процесс автоматизированного захвата внимания лида через несколько каналов связи. Цель — получить "Да" на просмотр демки в первые 10 минут после контакта.

## 📡 Фаза 1: Текстовый удар (Т+0 мин)
Отправить SMS или WhatsApp сообщение с ссылкой на демку.
- **Инструмент**: Twilio / TextNow / Whatsie.
- **Шаблон**:
> "Hi [Name], it's Designer from AI Site Agency. Your [Rating] rating on Google is amazing! I actually built a live demo for [Business Name] to show you how much more you could be doing: [Link]. Check it out when you have a sec!"

## 📞 Фаза 2: ИИ-звонок (Т+5 мин)
Если в течение 5 минут нет клика по ссылке (проверка редиректа), запускать автоматический звонок через **Bland.ai**.
- **Инструмент**: Bland.ai API.
- **Сценарий**:
    - "Hi [Name], just checking if you saw the SMS I sent earlier? I built a premium demo site for [Business Name] and didn't want you to miss out on the local rank boost."

## 📱 Фаза 3: Социальный апрув (Т+24 ч)
Если лид не ответил на звонок и SMS, написать в Instagram или Facebook Direct.
- **Текст**:
> "Hi [Name], loved your work at [Business Name]. Sending you the link to the premium site we built for you one last time: [Link]. No pressure, just hope it helps!"

---

### Аналитика успеха
1. **Клик по ссылке**: Лид заинтересован (Hot Lead).
2. **Ответ на SMS**: Начинаем продажу тарифа Starter ($249/мес).
3. **Требуется ручной вход**: Если лид задает сложный вопрос про SEO или домены.
