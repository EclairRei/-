# Контент-план «Автоматизация в тапочках» — v2

**Канал**: [@lex_automata](https://t.me/lex_automata)
**Период**: 1 июня 2026 — 30 августа 2026 (13 недель)
**Версия**: v2 — после аудита (см. `audit-notes-v2.md`)

---

## Что изменилось с v1

| Правка | Что сделано |
|---|---|
| Конфликты дат (4 шт.) | Разнесены на ±3-7 дней |
| Дубли тем (3 шт.) | «Эмбеддинги» / «Саммари» / «Душевность» — слиты или перепрофилированы |
| Перекос «Какой ИИ выбрать?» (~30% плана) | Сокращено до 1 слота (Вт). Освободившиеся слоты заняли новые рубрики |
| Воскресенье «3 рубрики в одном слоте» | Воскресенье = только Интерактив. Продающее → Чт (чётные недели) |
| Понедельник монотонный | 4 формата в ротации: словарь / разбор ноды / новости / мини-разбор подписчика |
| Юридика/деньги/налоги — нет | +7 постов (ФЗ-152, оферта, ИП, налоги, ROI, ценообразование) |
| Новости индустрии — нет | +13 «дайджест недели» (связка с собственным конвейером Тех-Разведчик) |
| Сезонные привязки — нет | +5 постов (отпуск, Чёрная пятница, начало учебного года) |
| Гостевые — нет | +2 совместки запланировано |
| Серии/марафон — нет | +1 марафон «Соберём ИИ-агента за 7 дней» (август) |

---

## Правила слотов (новая схема)

| День | Рубрика | Формат | Тон |
|---|---|---|---|
| **Пн** | 📚 Словарь / 🧰 Разбор ноды / 📰 Новости / 💬 Мини-разбор подписчика (по неделе месяца W1/W2/W3/W4) | Короткий пост 600-900 знаков | Теплый, обучающий |
| **Вт** | 🤖 Какой ИИ выбрать | Гайд / сравнение | Аналитический, с числами |
| **Ср** | 🛋 Кейсы в тапочках | Кейс с цифрами «было / стало» | Истории клиентов |
| **Чт (нечётная неделя)** | 🧯 Антикейс / провал | Разбор ошибки + урок | Честный, самоироничный |
| **Чт (чётная неделя)** | 🌸 Продающее | Прайс / FAQ / соц.доказательство | Прямой, без душноты |
| **Пт** | 💌 Истории из жизни автоматизатора | Сторителлинг / личное / lex_life | Ламповый, душевный |
| **Сб** | ✨ Туториал по субботам / Behind-the-scenes (2-я Сб месяца) | Пошаговая инструкция | Технический, дружелюбный |
| **Вс** | 🎈 Интерактив (опрос / мем / Q&A) | Только вовлечение | Игровой |

### Особые форматы (раз в месяц)
- **Подкаст / голосовой**: последняя пятница месяца (28 июня → 31 июля → 28 августа)
- **Гостевой пост**: 3-й четверг месяца чётной недели (12 июня, 14 августа)
- **Behind-the-scenes**: 2-я суббота месяца (вместо обычного туториала)
- **Q&A анонс + ответы**: каждое второе воскресенье

---

## Брендированные хэштеги

Уже используются:
- `#lex_words` — словарь / термины
- `#lex_ai` — про ИИ-модели
- `#lex_life` — личное, lex_automata
- `#lex_fail` — антикейсы
- `#lex_money` — деньги, цены, ROI

Добавить:
- `#lex_law` — юридика, ФЗ-152, оферты
- `#lex_news` — еженедельный дайджест
- `#lex_tools` — обзоры инструментов
- `#lex_voice` — голосовые/подкасты
- `#lex_qa` — ответы на вопросы подписчиков

---

## Визуальный стиль (для Pollinations / Midjourney)

**Базовый промпт-«скелет» Лекси** — переиспользуй в каждой картинке:

```
cozy lo-fi anime illustration, young woman with short dark hair and round glasses
(named Lexi), warm cardigan, fluffy slippers, sitting at a wooden desk with a
laptop, soft lamp light, indoor plants, ginger cat sleeping nearby, warm
autumn color palette (terracotta, mustard, cream), Studio Ghibli vibes,
flat illustration style, no text on image
```

**Модификаторы под формат**:

| Формат | Что добавить в промпт |
|---|---|
| Словарь | `+ floating glowing word "[TERM]" above laptop, dictionary book open on desk` |
| Сравнение моделей | `+ split screen showing [N] different robot characters, each with unique personality` |
| Кейс | `+ before/after split with messy office on left, clean automation on right` |
| Антикейс | `+ tangled cables and confused expression, smoke from laptop, cat looking concerned` |
| История | `+ window with rain, steaming tea cup, journal with handwritten notes` |
| Туториал | `+ holographic UI elements floating, schematic blueprints on wall, focused expression` |
| Продающее | `+ clean minimal background, golden hour light, gentle smile, subtle confidence` |
| Интерактив | `+ playful expression, speech bubbles, raised hand inviting conversation` |
| Behind-the-scenes | `+ messy desk view, multiple monitors, snack wrappers, post-it notes everywhere` |
| Голосовой | `+ headphones around neck, microphone visible, soft glow on face` |

**Технические параметры Pollinations**:
- Размер: `1024x1024` (для Telegram оптимально)
- Модель: `flux` (лучше `turbo` по детализации)
- Параметры URL: `?width=1024&height=1024&nologo=true&model=flux&seed=<random>`

---

# Календарь публикаций

## ИЮНЬ 2026

| Дата | День | Рубрика | Тема | Формат | Хэштеги | Image-промпт-добавка | Статус |
|---|---|---|---|---|---|---|---|
| 01.06 | Пн | 📚 Словарь (W1) | RAG в одной картинке: библиотека, библиотекарь и ваш вопрос | Пост | `#lex_words #lex_ai` | `+ library shelves with glowing books, librarian holding the right book` | Идея |
| 02.06 | Вт | 🤖 Какой ИИ | Какой ИИ для кода в Code-ноде n8n — кто лучше пишет JS | Гайд | `#lex_ai` | `+ code editor floating, JavaScript logo glow` | Идея |
| 03.06 | Ср | 🛋 Кейс | Бот-продавец в Direct/WhatsApp для селлеров | Кейс | `#lex_cases` | `+ phone screen with chat, smiling shop owner in background` | В работе |
| 04.06 | Чт (W1, нечёт) | 🧯 Антикейс | Workflow, который сломался в самый неподходящий момент (Black Friday-style) | Разбор | `#lex_fail` | `+ falling boxes, panic mode, smoking laptop` | Идея |
| 05.06 | Пт | 💌 История | OpenAI vs OpenRouter vs VsegPT vs ProxyAPI — через кого платить из РФ | Гайд | `#lex_money #lex_life` | `+ payment terminals around, contemplating Lexi` | Идея |
| 06.06 | Сб | ✨ Туториал | Какой ИИ для саммари: 3 кейса (отзывы, вакансии, длинные документы) | Гайд | `#lex_ai` | `+ paper stacks shrinking into one short note` | Идея (объединил с 7 июля) |
| 07.06 | Вс | 🎈 Интерактив | Опрос: «Какая задача бесит вас больше всего?» | Опрос | `#lex_qa` | `+ question marks floating, four character archetypes` | Идея |
| 08.06 | Пн | 🧰 Разбор ноды (W2) | 5 недооценённых нод n8n: Split In Batches, Merge, Wait, Respond to Webhook, HTML Extract | Гайд | `#lex_tools` | `+ five glowing node icons in a row, schematic style` | Идея |
| 09.06 | Вт | 🤖 Какой ИИ | Прогнала один промпт через 7 моделей — результаты, цена, победитель | Гайд | `#lex_ai #lex_money` | `+ seven robots in a row, one with golden trophy` | Идея |
| 10.06 | Ср | 🛋 Кейс | Автоответы на отзывы WB/Ozon | Кейс | `#lex_cases` | `+ stars rating, robot typing reply with care` | Идея |
| 11.06 | Чт (W2, чёт) | 🌸 Продающее | Считаем ROI автоматизации: 8000₽ за workflow vs 40 часов менеджера/мес | Гайд | `#lex_money` | `+ split: pile of cash on left, exhausted manager on right, equal sign` | Идея |
| 12.06 | Пт | 💌 История | **Гостевой пост / совместка** (договорись с дружественным каналом) | Совместка | `#lex_life` | `+ two characters at desk together, chai cups, friendly chat` | **NEW** |
| 13.06 | Сб | ✨ Туториал | Какой ИИ для «живых» историй и кейсов в твоём канале — тест стиля | Гайд | `#lex_ai #lex_life` | `+ four robots writing in different styles, scrolls floating` | Идея (был дубль 13.06+04.08, оставил один) |
| 14.06 | Вс | 🎈 Интерактив | Q&A анонс: «Накидайте вопросы — отвечу на 5 в следующий вторник» | Q&A | `#lex_qa` | `+ open notebook with question marks, friendly invite gesture` | **NEW** |
| 15.06 | Пн | 📰 Новости (W3, новый формат) | Дайджест недели: что нового в self-hosted AI и n8n | Новости | `#lex_news` | `+ newspaper folding, holographic news cards floating` | **NEW** |
| 16.06 | Вт | 🤖 Какой ИИ | ChatGPT vs Perplexity vs You.com — кто лучше ищет в интернете | Гайд | `#lex_ai` | `+ three search engines as characters, magnifying glasses` | Идея |
| 17.06 | Ср | 🛋 Кейс | «Цифровой помощник риелтора» (Циан/Авито → TG) | Кейс | `#lex_cases` | `+ apartment cards floating to phone, satisfied client` | Идея |
| 18.06 | Чт (W3, нечёт) | 🧯 Антикейс | «Самая дорогая ошибка с токенами» — как сжечь $X за ночь | Разбор | `#lex_fail #lex_money` | `+ tokens flying out of jar, shocked face at bill` | Идея (перенос с 21.05) |
| 19.06 | Пт | 💌 История | Какой ИИ для перевода «русский ↔ английский» в контексте обучения | Гайд | `#lex_ai` | `+ flags merging, dictionary opening` | Идея |
| 20.06 | Сб | ✨ Туториал | Фото чека → Excel (OCR: Tesseract или GPT-Vision) | Туториал | `#lex_tools` | `+ paper receipt transforming into spreadsheet` | Идея |
| 21.06 | Вс | 🎈 Интерактив | Q&A: ответы на 5 вопросов из понедельника + новый опрос | Q&A | `#lex_qa` | `+ five answer cards spreading on desk` | **NEW** |
| 22.06 | Пн | 💬 Разбор подписчика (W4, новый формат) | По пятницам разбираю один присланный workflow — формат подачи, как прислать | Объявление | `#lex_qa` | `+ inbox icon, magnifying glass over workflow diagram` | Идея (перенос) |
| 23.06 | Вт | 🤖 Какой ИИ | Какой ИИ для аналитики таблиц и Excel — разбор на реальных файлах | Гайд | `#lex_ai` | `+ Excel cells turning into charts, robot pointing at insights` | Идея |
| 24.06 | Ср | 🛋 Кейс | Мониторинг воркфлоу: Uptime Kuma + алерт в Telegram, когда упало | Туториал-кейс | `#lex_tools` | `+ red alarm bell, green checkmarks, dashboard glow` | Идея |
| 25.06 | Чт (W4, чёт) | 🌸 Продающее | До/после клиента: скрины workflow + цифры экономии часов | Кейс-продающее | `#lex_money #lex_cases` | `+ before/after cleaning montage, hours counter dropping` | Идея |
| 26.06 | Пт | 💌 История | День в жизни автоматизатора — что я автоматизирую для себя | Пост | `#lex_life` | `+ daily routine collage, chai → laptop → cat → walk` | Идея |
| 27.06 | Сб | ✨ Туториал | Голосовое → задача в Notion/ClickUp (Whisper локально) | Туториал | `#lex_tools` | `+ voice waves transforming into task cards` | Идея |
| 28.06 | Вс | 🎈 Интерактив | **Голосовой пост / подкаст-пилот**: «История одного workflow» (5 мин) | Аудио | `#lex_voice #lex_life` | `+ headphones, microphone, soft podcast glow` | **NEW** |

## Месячный итог июнь
- Постов: 28 (~6.5/неделю)
- Распределение: Какой ИИ — 6, Кейсы — 4, Антикейсы — 2, Продающее — 2, Истории — 4, Туториалы — 4, Интерактив — 4, Словарь/Ноды/Новости/Разбор — 4
- Новые форматы протестированы: дайджест новостей, Q&A, гостевая, голосовой

---

## ИЮЛЬ 2026

| Дата | День | Рубрика | Тема | Формат | Хэштеги | Image-промпт-добавка | Статус |
|---|---|---|---|---|---|---|---|
| 29.06 | Пн | 📚 Словарь (W1) | Бухгалтер-лайт для микробизнеса (концепт + словарик терминов) | Кейс+словарь | `#lex_words #lex_cases` | `+ calculator, receipts, robot accountant friendly` | Идея (объединил с кейсом) |
| 30.06 | Вт | 🤖 Какой ИИ | Whisper vs GigaAM vs YandexSpeechKit — кто лучше распознаёт русскую речь | Гайд | `#lex_ai` | `+ three microphones with sound waves` | Идея |
| 01.07 | Ср | 🛋 Кейс | Бухгалтер-лайт: чеки из банка → GPT категоризирует → отчёт | Кейс | `#lex_cases #lex_money` | `+ receipt waterfall into clean categorized table` | Идея |
| 02.07 | Чт (W1, нечёт) | 🧯 Антикейс | «Когда автоматизация НЕ нужна» — 5 ситуаций, где автоматизировать = только вред | Пост | `#lex_fail` | `+ stop sign, hand gesture, simple human task glow` | Идея |
| 03.07 | Пт | 💌 История | **NEW**: Самозанятая или ИП — что выгоднее автоматизатору в 2026 | Пост | `#lex_money #lex_law` | `+ two paths diverging, signs with tax rates` | **NEW** |
| 04.07 | Сб | ✨ Туториал | **NEW** Behind-the-scenes #1: «Как я собрала кейс по риелтору» — за кадром | Backstage | `#lex_life` | `+ messy desk, multiple monitors, debug screens` | **NEW** |
| 05.07 | Вс | 🎈 Интерактив | «Расскажи про свою задачу — подберём модель» (интерактив в комментах) | Интерактив | `#lex_qa #lex_ai` | `+ chat bubbles flying, helpful gesture` | Идея |
| 06.07 | Пн | 🧰 Разбор ноды (W2) | Cron и Trigger — кто будит ваши воркфлоу по утрам | Пост | `#lex_words #lex_tools` | `+ alarm clock with workflow gears, sunrise` | Идея (перенос с 03.08) |
| 07.07 | Вт | 🤖 Какой ИИ | Какой ИИ для Telegram-бота поддержки — скорость ответа важнее всего | Гайд | `#lex_ai` | `+ stopwatch, fast typing robot, satisfied user` | Идея |
| 08.07 | Ср | 🛋 Кейс | AI-подбор репетитора (форма → расписание → бронь) | Кейс | `#lex_cases` | `+ form filling out, calendar slots glowing, handshake` | Идея |
| 09.07 | Чт (W2, чёт) | 🌸 Продающее | **NEW**: Как я считаю стоимость workflow — формула + примеры | Гайд | `#lex_money` | `+ formula on chalkboard, clean math, cozy` | **NEW** |
| 10.07 | Пт | 💌 История | «Утро автоматизатора»: как выглядит мой день | Пост | `#lex_life` | `+ morning routine: tea, pet, laptop, journal` | Идея |
| 11.07 | Сб | ✨ Туториал | Автобронь встреч через Calendly + AI | Туториал | `#lex_tools` | `+ calendar with auto-filling slots, smooth flow` | Идея (перенос с 04.07) |
| 12.07 | Вс | 🎈 Интерактив | Q&A анонс #2: «Что хочется узнать про самозанятость и налоги» | Q&A | `#lex_qa #lex_money` | `+ tax form, calculator, friendly invite` | **NEW** |
| 13.07 | Пн | 📰 Новости (W3) | Дайджест недели: новые модели и инструменты автоматизации | Новости | `#lex_news` | `+ news feed scrolling, hot takes glow` | **NEW** |
| 14.07 | Вт | 🤖 Какой ИИ | Reasoning-модели (o3, DeepSeek-R1, Claude Thinking): когда брать, а когда слив токенов | Гайд | `#lex_ai #lex_money` | `+ thinking robot with gears visible, token meter` | Идея |
| 15.07 | Ср | 🛋 Кейс | Автоворонка для инфобиза в Telegram | Кейс | `#lex_cases` | `+ funnel with leads filtering down, hot ones glowing` | Идея |
| 16.07 | Чт (W3, нечёт) | 🧯 Антикейс | «Workflow, который делал больше вреда, чем пользы» (расширенная версия) | Разбор | `#lex_fail` | `+ overthinking robot, manual task simpler glow` | Идея |
| 17.07 | Пт | 💌 История | Как не попасть на лимиты маркетплейсов: Wait + Rate Limit + очереди | Туториал | `#lex_tools` | `+ traffic light system, queue of requests, calm flow` | Идея |
| 18.07 | Сб | ✨ Туториал | «Развенчаем мифы»: «GigaChat хуже», «DeepSeek всё выкачает», «локалка = бесплатно» | Гайд | `#lex_ai` | `+ three myths bursting like soap bubbles` | Идея |
| 19.07 | Вс | 🎈 Интерактив | Q&A ответы #2: налоги, ИП, ценообразование — ответы на вопросы из понедельника | Q&A | `#lex_qa #lex_money` | `+ five answer cards on tax theme` | **NEW** |
| 20.07 | Пн | 💬 Разбор подписчика (W4) | Первый разбор присланного workflow от подписчика (если будут заявки) | Разбор | `#lex_qa` | `+ workflow under magnifying glass, post-its with notes` | Идея |
| 21.07 | Вт | 🤖 Какой ИИ | Парсер тендеров/госзакупок (утренние карточки) — какой ИИ для парсинга | Гайд+кейс | `#lex_ai #lex_cases` | `+ documents flying, structured cards on phone screen` | Идея |
| 22.07 | Ср | 🛋 Кейс | **NEW**: «Передача проекта клиенту» — кейс безболезненной передачи workflow | Кейс | `#lex_cases #lex_law` | `+ documentation handover, two hands meeting` | **NEW** |
| 23.07 | Чт (W4, чёт) | 🌸 Продающее | 5 бесплатных инструментов для селлера WB/Ozon, которые дружат с n8n | Гайд | `#lex_tools` | `+ five tool icons, marketplaces glow, cost-free badge` | Идея |
| 24.07 | Пт | 💌 История | Почему я ушла с Zapier навсегда | Пост | `#lex_life` | `+ Zapier logo fading, n8n logo welcoming, cozy switch` | Идея |
| 25.07 | Сб | ✨ Туториал | Self-hosted AI-стек 2026: Ollama + LiteLLM + OpenWebUI + n8n (docker-compose) | Туториал | `#lex_tools` | `+ four containers stacking up, harmonious system` | Идея |
| 26.07 | Вс | 🎈 Интерактив | 10 задач, которые автоматизирую за 3 дня (мини-прайс с примерами) | Прайс-интерактив | `#lex_money` | `+ menu of tasks, prices on small tags` | Идея |
| 27.07 | Пн | 📚 Словарь | Альтернативы n8n: Activepieces, Windmill, Flowise — кому подойдут | Гайд | `#lex_tools #lex_words` | `+ four similar but distinct tool characters` | Идея (перенос с 27.07 — корректно) |
| 28.07 | Вт | 🤖 Какой ИИ | Как правильно читать бенчмарки моделей — почему MMLU и Arena не про ваш бизнес | Гайд | `#lex_ai` | `+ benchmark charts with skeptical look, real-world test glow` | Идея |
| 29.07 | Ср | 🛋 Кейс | **NEW**: Конкурс — «Опиши свой процесс, один соберу бесплатно» (старт) | Конкурс-кейс | `#lex_qa` | `+ trophy, friendly competition vibe, three contestants` | Идея (перенос с 31.05) |
| 30.07 | Чт (W5, нечёт) | 🧯 Антикейс | **NEW**: «Пять моих самых больших факапов в self-hosted» | Разбор | `#lex_fail` | `+ five small disasters in cute illustration style` | **NEW** |
| 31.07 | Пт | 💌 История | **Голосовой пост #2**: «Open Source или проприетарная — мои 3 года опыта» | Аудио | `#lex_voice #lex_ai` | `+ podcast setup, headphones, vinyl-like vibe` | **NEW** |

## Месячный итог июль
- Постов: 30
- Новые: самозанятость/налоги, behind-the-scenes #1, голосовой #2, Q&A блок про деньги, передача проекта
- Серии запущены: дайджест #2, Q&A #2

---

## АВГУСТ 2026

| Дата | День | Рубрика | Тема | Формат | Хэштеги | Image-промпт-добавка | Статус |
|---|---|---|---|---|---|---|---|
| 01.08 | Сб | ✨ Туториал | MCP + n8n (подключаем Model Context Protocol) | Туториал | `#lex_tools` | `+ protocol bridge between AI and database, glowing connection` | Идея |
| 02.08 | Вс | 🎈 Интерактив | До/после клиента: скрины workflow + цифры экономии часов (карусель) | Кейс-продажи | `#lex_money #lex_cases` | `+ before/after split, hours saved counter` | Идея |
| 03.08 | Пн | 📚 Словарь (W1) | **NEW**: Эмбеддинги vs Vector Store — чем отличаются (на примере шкафа с полочками) | Пост | `#lex_words #lex_ai` | `+ wardrobe with labeled shelves, items finding their slot` | **NEW** (перепрофилирован дубль) |
| 04.08 | Вт | 🤖 Какой ИИ | Какой ИИ для парсинга и структурирования JSON — где function calling адекватный | Гайд | `#lex_ai` | `+ messy text turning into clean JSON tree` | Идея |
| 05.08 | Ср | 🛋 Кейс | Анализ причин возвратов на маркетплейсах | Кейс | `#lex_cases` | `+ return packages clustering into reason buckets` | Идея |
| 06.08 | Чт (W1, нечёт) | 🧯 Антикейс | Как я потеряла 20 workflow за одну ночь (и что спасло бы меня) — расширенная | Сторителлинг | `#lex_fail` | `+ candle going out, then backup glowing rescue` | Идея |
| 07.08 | Пт | 💌 История | «Тапочные» автоматизации дома: напоминалки, умный свет, траты в семейный чат | Пост | `#lex_life` | `+ cozy home, lights on schedule, family chat glow` | Идея |
| 08.08 | Сб | ✨ Туториал | Свой кастомный GPT на базе n8n + RAG (с UI и логами) | Туториал | `#lex_tools` | `+ custom interface mockup, RAG flow visualization` | Идея |
| 09.08 | Вс | 🎈 Интерактив | Опрос: «На каком вы этапе автоматизации?» (новичок/уже n8n/уже AI/агенты) | Опрос | `#lex_qa` | `+ four growth stages of a plant, choose your level` | Идея |
| 10.08 | Пн | 🧰 Разбор ноды (W2) | **NEW**: Code-нода в n8n — когда писать JS, когда не стоит | Гайд | `#lex_tools` | `+ code editor with friendly cursor, decision tree` | **NEW** |
| 11.08 | Вт | 🤖 Какой ИИ | Какой ИИ для карточек товара WB/Ozon — 4 модели side-by-side + цена | Гайд | `#lex_ai #lex_cases` | `+ four product cards with subtle differences, price tags` | Идея |
| 12.08 | Ср | 🛋 Кейс | Один пост — во все соцсети сразу (TG/VK/Dzen/Threads) | Туториал-кейс | `#lex_tools` | `+ central hub broadcasting to four platforms` | Идея |
| 13.08 | Чт (W2, чёт) | 🌸 Продающее | FAQ: «почему это не дорого», «почему n8n», «что если ты уйдёшь» | FAQ | `#lex_money #lex_law` | `+ answer cards floating, gentle reassurance` | Идея |
| 14.08 | Пт | 💌 История | **Гостевой пост / совместка #2**: дружественный канал про fail-проекты | Совместка | `#lex_life #lex_fail` | `+ two characters laughing over notebook, shared coffee` | **NEW** |
| 15.08 | Сб | ✨ Туториал | Бэкапы n8n по расписанию (архив → S3/Я.Диск) | Туториал | `#lex_tools` | `+ snapshot icons rolling into cloud safety` | Идея |
| 16.08 | Вс | 🎈 Интерактив | Q&A анонс #3: «Что про юридику и ФЗ-152 хотите узнать» | Q&A | `#lex_qa #lex_law` | `+ legal documents friendly, Q-mark not scary` | **NEW** |
| 17.08 | Пн | 📰 Новости (W3) | Дайджест недели + лучшие находки за квартал | Новости | `#lex_news` | `+ summer roundup, best-of stickers` | **NEW** |
| 18.08 | Вт | 🤖 Какой ИИ | **NEW**: Можно ли скармливать ИИ персональные данные клиентов? ФЗ-152 на пальцах | Гайд | `#lex_law #lex_ai` | `+ shield icon over data, gentle compliance` | **NEW** |
| 19.08 | Ср | 🛋 Кейс | Бэкап + перенос всего стека на новый VPS (реальный кейс миграции) | Кейс | `#lex_cases #lex_tools` | `+ moving boxes glowing, server moving smoothly` | Идея (перенос с 30.08) |
| 20.08 | Чт (W3, нечёт) | 🧯 Антикейс | **NEW**: «Договор без оферты — как чуть не потеряла деньги» | Сторителлинг | `#lex_fail #lex_law` | `+ paper handshake breaking, then signed contract glow` | **NEW** |
| 21.08 | Пт | 💌 История | Первая встреча с клиентом — что спрашиваю и по какому чек-листу иду | Чек-лист | `#lex_life #lex_money` | `+ checklist on clipboard, friendly meeting setup` | Идея |
| 22.08 | Сб | ✨ Туториал | **МАРАФОН старт**: «Соберём ИИ-агента за 7 дней» — день 1 | Серия | `#lex_tools #lex_ai` | `+ day 1 of 7, foundation laying, anticipation` | **NEW** |
| 23.08 | Вс | 🎈 Интерактив | Голосовалка рубрик: «о чём написать дальше» | Опрос | `#lex_qa` | `+ category cards spreading, voting hand` | Идея (перенос с 30.08) |
| 24.08 | Пн | 💬 Разбор подписчика (W4) / марафон день 2 | Марафон день 2: настройка стека для агента | Серия | `#lex_tools` | `+ day 2 of 7, environment setup` | **NEW** |
| 25.08 | Вт | 🤖 Какой ИИ | **NEW**: Договор-оферта на автоматизацию — чек-лист, что точно прописать | Гайд | `#lex_law #lex_money` | `+ contract template, important highlights` | **NEW** |
| 26.08 | Ср | 🛋 Кейс / марафон день 3 | Марафон день 3: первый сигнал агента в Telegram | Серия | `#lex_tools` | `+ day 3 of 7, first message glow` | **NEW** |
| 27.08 | Чт (W4, чёт) | 🌸 Продающее / марафон день 4 | Марафон день 4: подключаем память (Postgres/Redis) | Серия | `#lex_tools` | `+ day 4 of 7, memory module connecting` | **NEW** |
| 28.08 | Пт | 💌 История / марафон день 5 | **Голосовой пост #3**: «Зачем я делаю марафон + день 5» | Аудио+серия | `#lex_voice` | `+ day 5, podcast moment of marathon` | **NEW** |
| 29.08 | Сб | ✨ Туториал / марафон день 6 | Марафон день 6: добавляем инструменты (tools) и тестируем | Серия | `#lex_tools` | `+ day 6 of 7, multi-tool agent in action` | **NEW** |
| 30.08 | Вс | 🎈 Интерактив / марафон день 7 финал | Марафон финал: готовый агент + опрос «Что собираете дальше?» | Серия+опрос | `#lex_tools #lex_qa` | `+ day 7 of 7, finished agent, celebration` | **NEW** |

## Месячный итог август
- Постов: 30
- Главное событие: **Марафон «Соберём ИИ-агента за 7 дней»** (22-30.08)
- Юридический блок: ФЗ-152, оферта, антикейс по договору (3 поста за месяц)
- Серия закрепит подписчиков на «эффект ожидания» (продолжения)

---

# Список новых тем — добавить в банк идей

Эти темы я предлагаю в плане, **отметить статусом «банк идей»**, использовать в сентябре-ноябре или вставить в свободные слоты:

## Юридика и риски
1. **Что такое DPA (data processing agreement) и нужен ли маленькому бизнесу** — `#lex_law`
2. **Авторские права на результат работы ИИ — кто владелец** — `#lex_law #lex_ai`
3. **Хранение клиентских данных в облаке: что точно нельзя** — `#lex_law`

## Деньги
4. **Авансы / постоплата / поэтапная — что я выбрала и почему** — `#lex_money`
5. **5 ошибок в налогах для начинающего автоматизатора** — `#lex_money`
6. **Сколько я заработала за 1-й, 2-й, 3-й год: честные цифры** — `#lex_money #lex_life`
7. **Прайс vs «обсудим индивидуально» — что лучше работает** — `#lex_money`

## Карьерный сторителлинг
8. **Как я зашла в автоматизацию (моя история)** — `#lex_life`
9. **Что я выкинула из стека за последний год** — `#lex_life #lex_tools`
10. **Самое глупое, что я делала с n8n в первый месяц** — `#lex_life #lex_fail`
11. **Книги/каналы/подкасты, от которых я заряжаюсь** — `#lex_life`

## Сезонные (привязать к датам)
12. **Автоматизация в отпуск: 5 настроек, чтобы клиент не паниковал без вас** — июль
13. **Готовим маркетплейс к Чёрной пятнице автоматизациями** — ноябрь
14. **Чек-лист: что автоматизировать перед новогодними каникулами** — декабрь
15. **1 сентября: автоматизация для онлайн-школ к началу сезона** — конец августа

## Технические серии (после марафона)
16. **Серия «30 нод за 30 дней»** — каждый день одна нода
17. **«Сериал»: один проект, 5 эпизодов** — глубже чем обычный кейс
18. **Behind-the-scenes #2 и #3** — раз в месяц процесс работы

---

# План внедрения

## На этой неделе (20-25 мая)
- [ ] Импортируй этот файл в Notion (Notion → New page → Import → Markdown)
- [ ] Сравни с текущим планом, помечай конфликты
- [ ] Добавь новые хэштеги (`#lex_law #lex_news #lex_tools #lex_voice #lex_qa`) в шапку канала
- [ ] Договорись с дружественным каналом про совместку 12.06

## До 1 июня (старт периода)
- [ ] Подготовь систему хэштегов и закреплённый «навигатор по канал**у»
- [ ] Заведи отдельную таблицу «Банк идей» (15+ тем выше)
- [ ] Запиши пилотный голосовой пост (для 28.06)
- [ ] Подключи свой пайплайн «Тех-Разведчик» к рубрике «Дайджест недели» — 1-2 топ-сигнала из конвейера в формат еженедельного дайджеста

## Раз в неделю (поддержка)
- [ ] Обновляй статусы постов: Идея → В работе → Опубликовано
- [ ] Логируй реакции / комменты / охваты — чтобы понять, что заходит
- [ ] Раз в воскресенье — план на следующую неделю + готовые драфты

## Раз в месяц (ретро)
- [ ] Выбираешь топ-3 заходов и топ-3 провалов
- [ ] Корректируешь долю рубрик по результату
- [ ] Обновляешь банк идей: что взяла, что добавила

---

# Метрики, на которые смотреть

| Метрика | Где смотреть | Целевой ориентир (квартал) |
|---|---|---|
| ER (engagement rate) | Telegram analytics | >5% к концу квартала |
| Просмотры на пост | Встроенная статистика | Растёт от мес.1 к мес.3 |
| Доля «продающих» постов с реакциями | Ручной подсчёт | Не падает ниже среднего ER канала |
| Заявки в ЛС (с источником «канал») | Свой CRM/таблица | +30% от мес.1 к мес.3 |
| Подписчики из совместок | UTM-метки в ссылках | минимум 50 за совместку |

---

**Готовый файл лежит в репо**. Когда импортируешь в Notion — каждая строка таблицы станет карточкой, а поле «Image-промпт-добавка» можешь автоматизировать через тот же n8n: воркфлоу #4 Lexi Touch уже умеет генерировать картинки через Pollinations.
