# LLM
rag-code-review/
├── retriever/         # Python: pgvector + эмбеддинги + поиск (делаем первым)
├── orchestrator/      # C#: декомпозиция кода + сборка промптов + клиент к Ollama
├── docker-compose.yml # Postgres+pgvector, Ollama
├── rag-base/          # твои 6 .md файлов с примерами
└── README.md          # архитектура, тот самый диаграмма