# Практика SA. Задание 2: BPMN-схемы бизнес-функции «Управление квотами и тарифными планами отельера»

**Функция.** Отель-партнёр туроператора самостоятельно задаёт квоты номеров и тарифные планы. Туроператор согласует только значимые изменения. Система публикует актуальную доступность во все каналы продаж и защищает от овербукинга.

Репозиторий продолжает [Задание 1](https://github.com/IkRyaS/sa-practice-task-1): описание функции дополнено схемами в нотации **BPMN 2.0**.

## Содержимое

- `01_business_context/`: [глоссарий](01_business_context/glossary.md) (добавлены термины BPMN), [бизнес-цели](01_business_context/business_goals.md), [конкурентный анализ](01_business_context/competitor_analysis.md)
- `02_business_process/`: [описание процесса](02_business_process/process_description.md) (новый раздел 8 «BPMN-модели»), [диаграмма Activity](02_business_process/process_diagram.png)
- `02_business_process/bpmn/` - **BPMN-схемы** (`.bpmn` - исходник, `.png` и `.svg` - изображения):
  1. [Основной процесс](02_business_process/bpmn/01_main_process.png)
  2. [Экстренное закрытие продаж (stop-sale)](02_business_process/bpmn/02_stop_sale.png)
  3. [Публикация в каналы, повторы и fail-safe](02_business_process/bpmn/03_publication.png)
  4. [Обновление через API](02_business_process/bpmn/04_api_update.png)
  5. [Проверка допуска объекта](02_business_process/bpmn/05_access_check.png)
- `03_requirements/`: [user stories](03_requirements/user_stories.md), [ограничения](03_requirements/constraints.md), [DoR](03_requirements/dor.md), [DoD](03_requirements/dod.md)
- [guide_2.md](guide_2.md) - гайд по заданию 2 (BPMN)
