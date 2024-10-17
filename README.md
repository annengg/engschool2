# engschool2
# Отчет о выполнении задачи "Онлайн-школа английского языка"

## Постановка задачи
Цель состоит в создании безопасной платформы для проведения онлайн-курсов английского языка, включая защиту данных пользователей, курсов и транзакций.



## Модель угроз

## Определение объектов (операций):
1. Регистрация пользователей: создание аккаунтов для студентов и преподавателей.
2. Оплата курсов: обработка платежей за обучение.
3. Управление контентом: загрузка и доступ к учебным материалам.
4. Видеоконференции: проведение онлайн-занятий через платформы для видеосвязи.
5. Оценка и тестирование: проведение тестов и оценка успеваемости студентов.
6. Общение: форумы, чаты и другие способы взаимодействия между участниками.
7. Аналитика: сбор данных о посещаемости и успеваемости.

## Выделение уязвимых объектов (операций):
1. Безопасность данных: недостаточная защита личной информации пользователей может привести к утечке данных.
2. Финансовые транзакции: уязвимости в системах оплаты могут быть использованы для мошенничества.
3. Неправильная аутентификация: слабые пароли или отсутствие двухфакторной аутентификации могут сделать аккаунты уязвимыми для взлома.
4. Уязвимости в программном обеспечении: использование устаревших или незащищённых платформ может привести к атакам.
5. Фишинг и социальная инженерия: мошенники могут пытаться получить доступ к аккаунтам пользователей через обман.

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

## Инвентаризация систем
Системы:
- Системы управления обучением (LMS): платфомы для создания, управления и мониторинга учебных курсов
- Платформы для видеоконференций
- Системы управления контентом (CMS): инструменты для создания и распространения учебных материалов
- Системы оценки и тестирования: создание и администрирование тестов и экзаменов
- Системы коммуникации: чаты, форумы и другие средства для общения между студентами и преподавателями 
- База данных пользователей (личные данные, результаты обучения)
- Платформы для электронных платежей
  
| Название                             | Назначение                                                                 |
|--------------------------------------|-----------------------------------------------------------------------------|
| Системы управления обучением (LMS)   | Платфомы для создания, управления и мониторинга учебных курсов |
| Платформы для видеоконференций       |  |
| Системы управления контентом (CMS)   | Инструменты для создания и распространения учебных материалов |
| Системы оценки и тестирования        | Создание и администрирование тестов и экзаменов |
| Системы коммуникации                 | Чаты, форумы и другие средства для общения между студентами и преподавателями |
| База данных пользователей            | Хранение личных данных, процесса и результатов обучения |
| Платформы для электронных платежей   |  |

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


### Компоненты



## Алгоритм работы решения

1. Пользователь регистрируется и инициирует сессию через веб-сервис или мобильное приложение.
2. Веб-сервис или мобильное приложение отправляет запрос на авторизацию в модуль безопасности контроля авторизаций.
3. Модуль безопасности контроля авторизаций запрашивает второй фактор аутентификации у пользователя (например, OTP).
4. Пользователь предоставляет второй фактор аутентификации.
5. Модуль безопасности контроля авторизаций проверяет предоставленные данные и, в случае успеха, генерирует уникальный токен для текущей сессии.
6. Веб-сервис или мобильное приложение направляет запрос на доступ к сессии в центр управления курсами, включая уникальный токен.
7. Центр управления курсами проверяет токен у модуля безопасности контроля авторизаций.
8. При успешной проверке токена центр управления курсами предоставляет доступ к сессии или курсу.
9. Веб-сервис или мобильное приложение информирует пользователя об успешной авторизации и предоставляет доступ к контенту.

## Безопасность

### Выполнение целей безопасности:

1. **Обеспечение безопасности передачи данных пользователей и курсов**
   - Использование протокола HTTPS для шифрования всех коммуникаций между компонентами системы.
   - Применение современных алгоритмов шифрования для защиты данных пользователей.

2. **Предоставление уникальных данных для каждой сессии**
   - Генерация уникального токена для каждой сессии модулем безопасности контроля авторизаций.
   - Использование временных меток и случайных чисел для обеспечения уникальности токенов.

3. **Обеспечение конфиденциальности данных**
   - Хранение персональных данных в зашифрованном виде.
   - Применение принципа минимальных привилегий для доступа к данным.
   - Использование токенизации для защиты данных курсов и материалов.

4. **Целостность данных и успешная доставка**
   - Использование цифровых подписей для обеспечения целостности данных курсов.
   - Реализация механизма подтверждения и сверки данных при доступе к учебным материалам.
   - Внедрение системы мониторинга и логирования для отслеживания статуса курсов и прогресса учащихся.

## Негативные сценарии и защита от них

- **Негативный сценарий:** Перехват данных при передаче
  - Защита от перехвата данных с помощью современных криптографических протоколов, HSTS и Certificate Pinning.

- **Негативный сценарий:** Нарушение целостности токенов
  - Применение криптографически стойких методов генерации токенов и ограничение времени их использования.

- **Негативный сценарий:** Компрометация мобильного приложения или веб-сервиса
  - Регулярное обновление и защита от вредоносного ПО, а также шифрование локальных данных.

## Тестирование

1. **Функциональное тестирование**
   - Проверка доступа к курсам при правильных учетных данных и вторичном факторе.
   - Тестирование уникальности токенов и устойчивости при высокой нагрузке.

2. **Тестирование безопасности**
   - Проведение тестов на проникновение, сканирование уязвимостей, и анализ безопасности компонентов.

3. **Нагрузочное тестирование**
   - Симуляция нагрузки на систему и проверка устойчивости к DDoS-атакам.

4. **Тестирование отказоустойчивости**
   - Проверка работоспособности системы при отказе одного из компонентов и восстановление после сбоев.

## Заключение
Предложенная архитектура решения учитывает безопасность данных учащихся и преподавателей, а также обеспечивает надежный доступ к курсам. Микросервисная архитектура поддерживает масштабируемость системы и безопасность критически важных компонентов. Регулярное тестирование и мониторинг позволяют своевременно выявлять и устранять уязвимости.

**Рекомендации для повышения безопасности:**
- Рассмотреть возможность внедрения машинного обучения для выявления аномального поведения.
- Использование блокчейна для повышения прозрачности и надежности данных о курсах и успеваемости учащихся.

## Источники

