# Дмитрий Шишов

**AI Automation / LLM Engineer · ML/NLP**

Москва · Telegram: [@P0n9L](https://t.me/P0n9L) · Email: dimashishov484@yandex.ru

Проектирую AI-ассистентов и автоматизации: дообучение моделей под tool-calling, подключение баз знаний, интеграции с внешними системами через REST и вебхуки. Опыт оптимизации процессов на производстве и автоматизации в собственных проектах. Работаю с замерами: доля корректных вызовов инструментов 73% → 85%, время ответа ассистента 3 с → 1 с.

---

## Стек

| Категория | Технологии |
|---|---|
| **Языки и данные** | Python, SQL, Bash, Pandas, NumPy |
| **ML / DL** | scikit-learn, XGBoost, LightGBM, CatBoost, PyTorch |
| **LLM / NLP** | Transformers, PEFT (QLoRA), tool-calling, TF-IDF, STT/TTS |
| **Интеграции и автоматизация** | FastAPI, REST API, вебхуки, cron, Telegram Bot API, Docker |
| **Практики** | pytest, Git, CI (GitHub Actions), Linux |

---

## Проекты

**Интеграции и автоматизация**

- [**Шлюз «телефония → 1С»**](https://github.com/P0n9L1/telephony-1c-gateway) — приём вебхуков о звонках и создание документов «Звонок» в 1С. Идемпотентность на обеих сторонах, нормализация номеров к E.164, двухуровневый retry, очередь доставки. 38 unit-тестов + 18 сквозных проверок
- [**CRM-воронка с AI-ассистентом**](https://github.com/P0n9L1/crm-funnel-emulator) — движок правил автоматизации (SLA, уведомления, контроль зависших сделок) и ассистент по базе знаний: подбор статьи по тексту обращения, черновик ответа с указанием источника. 45 unit-тестов + 22 сквозные проверки

**LLM и NLP**

- [**Люси — голосовой ассистент**](https://github.com/P0n9L1/lucy-voice-assistant) — Qwen2.5-1.5B, дообученная QLoRA под tool-calling; пайплайн push-to-talk → Vosk (STT) → LLM (GGUF, CUDA) → агентский цикл → TTS

**Машинное обучение**

- [**MLP с нуля**](https://github.com/P0n9L1/mlp-implementation) — двухслойная сеть для табличных данных: forward/backward pass, Adam/SGD, Xavier/He
- [**CNN для классификации изображений**](https://github.com/P0n9L1/cnn-image-classification) — свёрточная сеть на PyTorch, 9 классов, оценка по AUROC
- [**Food & Nutrition**](https://github.com/P0n9L1/food-nutrition-ds) — end-to-end DS-пайплайн: EDA, ансамбли (Voting, Bagging, Stacking), USDA FoodData Central API, CLI для генерации меню
- [**Линейная регрессия и регуляризация**](https://github.com/P0n9L1/linear-regression-ml) — LR/Ridge/Lasso/ElasticNet с нуля (SGD + аналитическое решение), MLE/MAP
- [**Деревья решений и ансамбли**](https://github.com/P0n9L1/decision-trees-ensembles) — CART → Random Forest → ExtraTrees → GBDT с нуля → XGBoost/LightGBM/CatBoost; DART, early stopping
- [**Кластеризация**](https://github.com/P0n9L1/clustering-ml) — K-means с нуля, DBSCAN, Agglomerative, GMM + EM; кластерные метки как признаки для Lasso
- [**Снижение размерности**](https://github.com/P0n9L1/dimensionality-reduction) — PCA, SVD, NMF, t-SNE, UMAP, LLE; сжатие изображений, визуализация

---

## Образование

- **РЭУ им. Г.В. Плеханова** — Бакалавриат, Менеджмент товаров (2023–2027), GPA 4.0
- **School 21 (Сбер)** — DS/ML (2026), трек пройден за 2 месяца вместо 18; топ 5 из 1202 студентов
