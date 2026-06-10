# Submission

## Ссылка на репозиторий с заданием

- Repo URL: https://github.com/vhamz/movie-rag

## Автор

- ФИО / ник: Юсупов Хамзат, БАСБ-251

## Комментарий

- Кратко: RAG по сюжетам фильмов на CMU Movie Summary Corpus (42306 записей в источнике, 1500 в datasets.json, ~5800 чанков в индексе). Pipeline: ingest -> chunking -> TF-IDF -> retrieval -> ответ по контексту с отказом -> Streamlit UI. 12 тестов green. Реализовано улучшение UI (порог score, подсветка совпавших слов, история запросов), еще два описаны в IMPROVEMENTS.md.
