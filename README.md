# engschool2
# Отчет о выполнении задачи "Онлайн-школа английского языка  "Open Source"

## О заказчике
По требованиям заказчика, ресурс должен обеспечивать:
1. Строгую конфиденциальность обучающего материала
2. Защиту персональных данных пользователей  
3. Создание надежной защищенной базы данных
4. Возможность проведения безопасных транзакций

## Постановка задачи
Цель состоит в создании безопасной платформы для проведения онлайн-курсов английского языка, включая защиту данных пользователей, курсов и транзакций.


## Определение объектов (операций):
1. Регистрация пользователей: создание аккаунтов для студентов и преподавателей.
2. Оплата курсов: обработка платежей за обучение.
3. Управление контентом: загрузка и доступ к учебным материалам.
4. Видеоконференции: проведение онлайн-занятий через платформы для видеосвязи.
5. Оценка и тестирование: проведение тестов и оценка успеваемости студентов.
6. Общение: форумы, чаты и другие способы взаимодействия между участниками.
7. Аналитика: сбор данных о посещаемости и успеваемости.

## Инвентаризация систем
Системы:
  
| Название                             | Назначение                                                                 |
|--------------------------------------|-----------------------------------------------------------------------------|
| Системы управления обучением (LMS)   | Платформы для создания, управления и мониторинга учебных курсов |
| Платформы для видеоконференций       | Обеспечивают удаленную коммуникацию |
| Системы управления контентом (CMS)   | Инструменты для создания и распространения учебных материалов |
| Системы оценки и тестирования        | Создание и администрирование тестов и экзаменов |
| Системы коммуникации                 | Чаты, форумы и другие средства для общения между студентами и преподавателями |
| База данных пользователей            | Хранение личных данных, процесса и результатов обучения |
| Платформы для электронных платежей   | Проведение финансовыхранзакций через интернет |

![{13ADE7E0-4CCD-486E-ADBF-BF8E2AC6C025}](https://github.com/user-attachments/assets/f24ba6fe-8a65-4240-894b-4703ebe97c93)


## Выделение уязвимых объектов (операций):
1. Безопасность данных: недостаточная защита личной информации пользователей может привести к утечке данных.
2. Финансовые транзакции: уязвимости в системах оплаты могут быть использованы для мошенничества.
3. Неправильная аутентификация: слабые пароли или отсутствие двухфакторной аутентификации могут сделать аккаунты уязвимыми для взлома.
4. Уязвимости в программном обеспечении: использование устаревших или незащищённых платформ может привести к атакам.
5. Фишинг и социальная инженерия: мошенники могут пытаться получить доступ к аккаунтам пользователей путём обмана.

## Определение негативных последствий
1. Утечка личных данных:
Потеря доверия со стороны обучающихся, возможные юридические последствия и штрафы. 
2. Финансовые транзакции:
Мошенничество может привести к значительным убыткам, если деньги будут украдены.
Потеря доверия со стороны платежных систем и банков может затруднить обработку транзакций. Необходимость разбрательства по случаям ошенничества может отвлечь ресурсы от основных задач.
3. Неправильная аутентификация:
Уязвимые аккаунты могут быть взломаны = утечка информации и финансовые потери.
Злоумышленники могут использовать взломанные аккаунты для распространения вирусов и фишинговых систем.
Обучающиеся могут потерять доступ к своим курсам и материалам.
4. Уязвимости в ПО:
Устаревшие платформы могут стать мишенью для кибератак, что приведет к сбоям в работе.
Атаки могут првести к потере важных данных, включая учебные материалы и информацию о студентах.
Проблемы с системой могут вызвать перерывы в обучении и недовольство обучающихся.
5. Фишинг и социальная инженерия:
Студенты могут случайно предоставить свои данные мошенникам, что может привести к дальнейшим утечкам.
Мошенники могут использовать полученные данные для кражи денег или доступа к финансовым ресурсам.
Обучающиеся и сотрудники могут использовать стресс и беспокойство из-за угроз безопасности.

## Определение источников угроз
Внешние источники:
- Хакеры, использующие различные методы атак (фишинг, DDoS)
- Конкуренты (другие образовательные учреждения)
- Сторонние поставщики услуг (могут предоставлять угрозу в случае недостаточной безопасности их услуг)

Внутренние источники:
- Сотрудники, которые могут случайно или намеренно раскрыть данные.

## Оценка способов реализации угроз
- Фишинг: Использование поддельных писем для получения учетных данных.
- DDoS-атаки: Атаки на серверы с целью их перегрузки.
- Несанкционированный доступ: Использование уязвимостей в системе для доступа к данным.

## Оценка возможности реализации угроз
- Вероятность возникновения: Высокая (особенно для фишинга и DDoS-атак).
- Актуальность угроз: Угрозы актуальны в условиях увеличения числа онлайн-платформ и кибератак.

## Оценка сценариев реализации угроз
- Сценарий 1: Студент получает фишинговое письмо и передает свои учетные данные злоумышленнику. Это приводит к несанкционированному доступу к аккаунтам других студентов.
- Сценарий 2: Хакеры запускают DDoS-атаку на платформу, что делает ее недоступной для всех пользователей на несколько часов.
- Сценарий 3: Сотрудник случайно отправляет конфиденциальные данные третьим лицам через ошибку в электронной почте.

## Решения для выявленных сценариев
СЦЕНАРИЙ 1 - ФИШИНГ
Двухфакторная аутентификация:
- Внедрение обязательной двухфакторной аутентификации для всех учетных записей.
Мониторинг активности:
- Внедрение систем мониторинга, которые могут обнаруживать необычную активность в учетных записях и предупреждать администраторов.

СЦЕНАРИЙ 2 - DDOS-АТАКА
Использование CDN (Content Delivery Network):
- Подключение к CDN, который может помочь распределить нагрузку и защитить от DDoS-атак.
Использование DDoS-защиты:
- Применение специализированных услуг защиты от DDoS-атак, таких как Cloudflare или Akamai.
Мониторинг трафика:
- Установка систем мониторинга трафика для быстрого обнаружения аномалий и реагирования на потенциальные атаки.
План восстановения:
- Резервное копирование. Резервные серверы.

СЦЕНАРИЙ 3 - ОШИБКА ОТПРАВКИ КОНФИДЕНЦИАЛЬНЫХ ДАННЫХ
Использование доверенных и защищенных социальных сетей, почты.

## Заключение
Эта модель угроз позволяет систематически оценить риски и разработать стратегии по защите информации в онлайн-школе английского языка, обеспечивая безопасность данных студентов и преподавателей.


## Источники
Методический документ от 5 февраля 2021 по модели угроз
