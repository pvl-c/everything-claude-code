# Product roadmap для одного senior developer

Roadmap предполагает, что разработчик одновременно является product/business partner. Поэтому custom build ограничен. Оценки — относительные и требуют технического discovery.

## Дни 1–14 — concierge prototype

- Определить data dictionary для H01/H03 и one asset type.
- Настроить managed CRM, secure deal room, task board и MFA.
- Создать вручную собираемый Investment Thesis template и Deal Memo template.
- Ввести claim/source/reviewer table и conflict register.
- Настроить AI только в shadow mode на публичных/обезличенных документах.
- Подготовить privacy/processors/retention inventory с counsel.

**Не писать:** custom portal UI, marketplace, valuation engine.

## Дни 15–45 — первые платные cases

- Guided intake web form.
- Internal deal database: mandate, buy box, asset, claim, risk, task, decision.
- Memo generation из approved fields.
- Document extraction с page citations и review queue.
- Клиентский read-only status view или white-label managed portal.
- Instrumentation: time per stage, missing fields, AI corrections.

**Gate:** минимум 3 paid H01/H03 cases. Без них развитие UI останавливается.

## Дни 46–90 — repeatability

- Camping/hospitality minimum data schemas.
- Comparative shortlist и scenario assumptions.
- Access levels teaser/NDA/DD.
- Weekly brief generator с approval.
- Partner assignment/SLA tracker.
- Client decisions and conflict/fee disclosures.
- Security review, restore test, deletion workflow.

**Gate:** два acquisition mandates и один seller-readiness pilot; critical claim citation coverage 100%.

## Месяцы 4–6 — клиентский cockpit

- Custom lightweight portal только для подтверждённых recurring journeys.
- Role-based access: principal, spouse/partner, CFO, lawyer, technical.
- Versioned scenario comparison.
- Seller passport and data-room readiness score.
- Multilingual summaries with original-source access.
- Private matching для verified buy boxes, без публичного marketplace.

**Gate:** >70% weekly usage, снижение manual status work, минимум 10 cases в общей schema.

## Месяцы 7–12 — защищаемость

- Benchmarks только из permissioned/anonymised case data.
- Reusable camping/hospitality risk libraries.
- Partner quality/SLA analytics.
- Optional owner-reporting pilot для 3 assets.
- API/imports только для систем, реально встреченных в cases.
- Automated monitoring of licences/deadlines там, где есть authoritative source.

## Capacity budget

Ориентир времени developer-партнёра на первые 90 дней:

- 35% client case/product discovery;
- 30% data model/workflows;
- 15% security/privacy/reliability;
- 10% integrations/managed tools;
- 10% polish/website/analytics.

Если client delivery требует >50%, custom build уменьшается. Сервис важнее software roadmap.

## Технические критерии выхода из shadow mode

- 50+ документов одного типа проверены человеком;
- field-level accuracy на critical fields измерена, не предполагается;
- известны false-positive/false-negative patterns;
- есть source citation и confidence;
- есть rollback/audit log;
- processor terms, location, retention and access одобрены;
- клиент проинформирован об AI use там, где требуется.

