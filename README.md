
# Решение для тегирования видео на RUTUBE

Наше решение представляет собой высокоэффективный алгоритм для автоматического подбора тегов к видео на платформе RUTUBE. Основная задача алгоритма — достичь оптимального баланса между скоростью обработки и точностью определения контекста видео.

## Ключевые особенности:
- **Генеративные модели:** Алгоритм использует мощные нейросетевые модели, такие как *Whisper-Large-V3*, *LLaMA-Next-Video-7B-HF* и модификации *BERT* для анализа видеопотока, аудиопотока и метаданных видео.
- **Контекстное определение тегов:** Путем векторизации данных и кластеризации мы сопоставляем контекст видео с вводными тегами для получения наиболее релевантных результатов.
- **Оптимизация ресурсов:** Для экономии ресурсов видеохостинга используются методы сжатия аудио- и видеопотока, такие как сокращение кадров и временная выборка материала, что позволяет снижать нагрузку на систему без ущерба для точности.

Алгоритм полностью реализован на Python и позволяет видеохостингу значительно улучшить процесс категоризации видео, минимизируя время обработки и повышая точность присвоения тегов.
