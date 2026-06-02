# Submission

Заполните файл перед отправкой PR.

## Ссылка на репозиторий с заданием

- Repo URL: https://github.com/ak1232320/corp_dannie_rag

## Автор

- ФИО / ник: Алексей Косычев, БАСБ 251 (ak1232320)

## Комментарий

- Кратко: RAG по критериям приемлемости клинических исследований (Kaggle
  "Clinical Trial Eligibility Criteria", ClinicalTrials.gov, CC BY 4.0). Пайплайн
  данные→чанки→индекс→поиск→ответ, 1200 испытаний → 8585 чанков. 3 улучшения:
  гибридный поиск (TF-IDF + эмбеддинги), оценка качества (retrieval@k/hit-rate/MRR),
  LLM-генерация (OpenRouter) с экстрактивным фолбэком. Streamlit UI, 34 теста.
  hit@3: TF-IDF 0.875 vs Hybrid 1.000; кросс-язычные 0.125 vs 1.000.
