# Components — Kartka

Окремі UI-компоненти: специфікації, стани й (згодом) реалізація. Будуються на
токенах із [`../tokens/`](../tokens/). Складаються в патерни в
[`../design-system/`](../design-system/).

## Кандидати (з фіч MVP)

- [ ] `Button` (primary / secondary / ghost / danger)
- [ ] `Input`, `Select`, `DatePicker` — оптимізовані під **швидке введення**
- [ ] `MemberAvatar` / `MemberCard` — член сім'ї
- [ ] `RecordRow` — запис документа / ліків / аналізу
- [ ] `QuickAddSheet` — нижній лист швидкого додавання (повтор останнього, шаблони)
- [ ] `ParameterChart` — графік аналізу в часі
- [ ] `ReminderCard` — нагадування про візит (зокрема повторюване)
- [ ] `EmptyState`, `Toast`, `Tag/Chip` (тип документа, алерген)

## Для кожного компонента

- Призначення й коли використовувати.
- Усі стани: default / hover / focus / active / disabled / error / loading.
- Доступність (фокус, ARIA, контраст).
- Які токени споживає.
