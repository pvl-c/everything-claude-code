# AI/data governance checklist

Перед каждым новым agentic workflow:

- [ ] Определена бизнес-задача и метрика, а не только возможность автоматизации.
- [ ] Указаны data owner, lawful basis, sensitivity и retention.
- [ ] Проверены model/provider terms, subprocessors и region.
- [ ] PII/KYC/health data исключены или обрабатываются в разрешённом отдельном контуре.
- [ ] Agent получает минимальные tools/permissions.
- [ ] External send, publish, contract, payment и access changes требуют approval.
- [ ] Output показывает source, version, confidence и reviewer.
- [ ] Есть тесты на prompt injection через документы и malicious links.
- [ ] Логи не содержат лишних персональных данных.
- [ ] Определены incident, rollback и deletion procedures.
- [ ] Клиентская transparency/disclosure проверена по AI Act/GDPR с counsel.
- [ ] Люди, использующие систему, обучены и знают границы.

