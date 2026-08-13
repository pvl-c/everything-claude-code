# E07 — Ева Рока, proptech/AI product и data governance

**Статус:** `SYNTHETIC`.  
**Опыт:** 15 лет в real-estate software, document workflows, GDPR и applied AI.  
**Мандат:** проверить исполнимость одним senior developer и не допустить AI-theatre.

## Основные заметки

- Главная интеллектуальная собственность — data model, workflow и evidence trail, а не LLM-wrapper.
- В первом году нельзя строить marketplace, valuation engine, full CRM, mobile app и autonomous agents одновременно.
- Сначала использовать managed services и manual concierge behind the interface; автоматизировать повторяемое после 10–20 кейсов.
- Любой agentic workflow требует least privilege, isolated tools, human approvals, logging, retention policy и incident response.
- Паспорта, bank/source-of-funds, health/insurance data нельзя смешивать в общий vector store.
- Клиент должен видеть, где текст AI-generated, кем проверен и на каких документах основан.

## Вердикт

H07 — enable now на готовых компонентах; H03 — лучший wedge для собственного software layer; H09 — только после реальных data integrations; H11 — простой matching workflow, не marketplace.

## Жёсткий вопрос

«Если AI ошибся в одном извлечённом ограничении, кто это заметит до arras и как система покажет источник?»

