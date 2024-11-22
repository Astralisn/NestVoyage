# NestVoyage

Техническое Задание на Разработку Веб-приложения «NestVoyage»
1. Введение
1.1 Цель документа
Этот документ описывает требования к разработке веб-приложения «NestVoyage» для обеспечения эффективного обмена опытом между пользователями. Приложение должно поддерживать создание, изменена и удаление постов, добавление отзывов и просмотр рейтинга.
1.2 Актуальность и назначение проекта
В современном мире путешествия становятся не только необходимостью, но и важной частью жизни многих людей. С увеличением числа туристов и множеством доступных направлений, возникает потребность в качественной информации о местах, которые стоит посетить. Система «NestVoyage» предоставляет удобный инструмент для оценки различных мест и обмена опытом как между обычными туристами, так и опытными путешественниками.
1.3 Основные пользователи системы
Система предназначена для использования:
•	Пользователи —создание постов, их редактирование, написание отзывов, набор рейтинга.
•	Администраторы — управление пользователями и их постами, мониторинг активности.
2. Цели и задачи проекта
2.1 Основные цели
•	Обеспечить пользователям возможность обмена опытом и оценки.
•	Реализовать систему рейтингов среди пользователей.
2.2 Конкретные задачи
•	Разработка функционала для создания, редактирования и удаления постов.
•	Реализация системы рейтингов.
3. Требования к системе
3.1 Функциональные требования
•	Аккаунты: возможность создания, редактирования и удаления чатов.
•	Создание постов: поддержка отправки текста и изображений.
•	Отзывы: возможность оценить чужие посты.
•	Рейтинг: возможность просмотра рейтинга среди пользователей.
3.2 Нефункциональные требования
•	Масштабируемость: возможность поддерживать работу с 20+ пользователями без потери производительности.
4. Требования к пользовательскому интерфейсу
4.1 Основные экраны
•	Главная страница: отображение ленты с популярными постами
•	Страница аккаунта: отображение информации о пользователе, его посты и отзывы.
•	Страница создания постов: поле для ввода текста, добавления фотографий и тегов.
4.2 Навигация Меню должно включать разделы:
•	«Поиск»
•	«Профиль»
•	«Чаты»
•	«Выход»
4.3 Юзабилити
•	Простой и интуитивно понятный интерфейс.
•	Возможность создания поста, оценки, изменения их.
5. Требования к технической реализации
5.1 Языки и технологии
•	Frontend: React.js
•	Backend: Laravel.
•	База данных: MySQL
5.2 Архитектура системы
•	Микросервисная архитектура с использованием Inertia и WebSocket для реального времени.
•	Хранение данных в реляционной базе данных (MySQL, MongoDB).
5.3 Интеграции
•	Интеграция с внешними сервисами для отправки email-уведомлений.
6. Требования к безопасности
6.1 Аутентификация и авторизация
•	Авторизация: разграничение прав доступа — администраторы, пользователи, создание и администрирование чатов.
6.2 Шифрование данных
•	Использование HTTPS для защиты передаваемых данных.
•	Хранение паролей с использованием bcrypt.
6.3 Политики доступа
•	Защита от SQL-инъекций, XSS и CSRF-атак.
•	Ограничение доступа к административной панели по IP-адресам.
7. Ограничения и допущения
7.1 Технические ограничения
•	Приложение должно быть оптимизировано для работы на облачных сервисах (например, AWS или Azure).
7.2 Финансовые ограничения
•	Бюджет: 3 сирийские шаурмы
7.3 Сроки выполнения
•	Полная реализация проекта — 4 месяца с начала разработки.
8. Требования к тестированию и приемке
8.1 Типы тестирования
•	Функциональное тестирование: проверка всех функций (создание чатов, отправка сообщений, уведомления).
•	Нагрузочное тестирование: проверка на работу с более чем 10 пользователями.
•	Тестирование безопасности: проверка на уязвимости, включая SQL-инъекции и XSS.
8.2 Критерии приемки
•	Полное выполнение функциональных и нефункциональных требований.
•	Прохождение более 85% тестов по результатам приемочных испытаний.
9. Требования к документации
9.1 Пользовательская документация
•	Руководство пользователя с инструкциями по созданию чатов, отправке сообщений и настройке профиля.
9.2 Техническая документация
•	Описание архитектуры приложения, структура базы данных, API для взаимодействия между клиентом и сервером.
10. План реализации
10.1 Этапы разработки
1.	Анализ и проектирование — 1 месяц.
2.	Разработка прототипа — 1 месяц.
3.	Полноценная разработка и тестирование — 3 месяца.
4.	Внедрение и обучение — 1 месяц.
10.2 Сроки выполнения этапов
•	Дата начала: 10 ноября 2024 года.
•	Дата завершения: 15 декабря 2024 года.
10.3 Ответственные лица
•	Учредитель по совместительству инвестор фирмы: Ларионова А.И
Глава отдела HR: Малых В.А
Корпоративный директор заведующий отдела Back’end: Вакуров Ф.А
Корпоративный директор заведующий отдела Front’end: Галкин Н.А
•	Специалист по React.js : Подопригоров И.В
•	Ведущий разработчик: Малых В.А
11. Приложения
•	Приложение A: Примеры интерфейсов.
