# Interview Practice — Java Middle+/Senior

Тренажёр для подготовки к собеседованиям. Задания создаёт ассистент по указанным темам,
решения пишет студент, проверка — как на реальном собеседовании (код-ревью + вопросы).

## Структура

```
tasks/<topic>/README.md          — формулировки заданий по теме
src/main/java/org/practice/<topic>/   — решения (пакет = тема)
src/test/java/org/practice/<topic>/   — тесты к решениям
```

## Workflow

1. Называешь тему (например: «concurrency», «streams», «spring-transaction»).
2. Получаешь 2–4 задания уровня middle+/senior в `tasks/<topic>/README.md`.
3. Пишешь решение в `src/main/java/org/practice/<topic>/`.
4. Говоришь «проверяй» — получаешь ревью: корректность, краевые случаи,
   сложность, типичные вопросы интервьюера по коду.
