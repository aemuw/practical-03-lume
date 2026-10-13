# Фактичні перевірки підготовленої версії

Дата: 13 жовтня 2026 року. Це результати перевірки підготовлених файлів, а не твердження, що студент уже повторив кожний крок.

Браузер: Microsoft Edge 155.0.4283.45. Успішних перевірок: 65; невдалих: 0.

## Браузер

- PASS: index.html: ids
- PASS: index.html: labels
- PASS: index.html: descriptions
- PASS: index.html: buttons
- PASS: index.html: anchors
- PASS: index.html: main
- PASS: index.html: plain
- PASS: index.html: skip link focus
- PASS: index.html: skip link reaches main
- PASS: login.html: ids
- PASS: login.html: labels
- PASS: login.html: descriptions
- PASS: login.html: buttons
- PASS: login.html: anchors
- PASS: login.html: main
- PASS: login.html: plain
- PASS: login.html: skip link focus
- PASS: login.html: skip link reaches main
- PASS: register.html: ids
- PASS: register.html: labels
- PASS: register.html: descriptions
- PASS: register.html: buttons
- PASS: register.html: anchors
- PASS: register.html: main
- PASS: register.html: plain
- PASS: register.html: skip link focus
- PASS: register.html: skip link reaches main
- PASS: product-form.html: ids
- PASS: product-form.html: labels
- PASS: product-form.html: descriptions
- PASS: product-form.html: buttons
- PASS: product-form.html: anchors
- PASS: product-form.html: main
- PASS: product-form.html: plain
- PASS: product-form.html: skip link focus
- PASS: product-form.html: skip link reaches main
- PASS: login empty rejected
- PASS: invalid email rejected
- PASS: login valid accepted
- PASS: login label focuses input
- PASS: login Tab email -> password
- PASS: Enter triggers submit
- PASS: login uses POST
- PASS: registration empty rejected
- PASS: short display name rejected
- PASS: short password rejected
- PASS: HTML does not compare passwords as documented
- PASS: maxlength clips name to 80
- PASS: product empty rejected
- PASS: short product title rejected
- PASS: short description rejected
- PASS: empty category rejected
- PASS: price below range rejected
- PASS: price above range rejected
- PASS: price precision rejected
- PASS: missing status rejected
- PASS: Space activates radio
- PASS: arrow changes radio choice
- PASS: Space activates checkbox
- PASS: checkbox label activates control
- PASS: valid product accepted
- PASS: FormData includes both selected finishes
- PASS: unchecked finish omitted
- PASS: FormData keys match all expected product fields
- PASS: GET writes only search to URL

## Nu HTML Checker

Оригінали всіх чотирьох файлів надіслано для перевірки через HTTPS POST до https://validator.w3.org/nu/?out=json. Для index.html, login.html, register.html, product-form.html список messages порожній: 0 помилок, 0 попереджень. Повні відповіді збережено в evidence/nu-results.json.

## Межі перевірки

- Браузерні перевірки автоматизовані; код перевірки виконувався поза сайтом і не входить до HTML-проєкту.
- Склад даних товару перевірено через FormData; форма не надсилала пароль до сервера. Enter перевірено з перехопленням submit лише в тестовому браузері.
- Справжню серверну обробку POST не перевірено: Backend відсутній за умовою.
- Скринридер, усі браузери та менеджери паролів не перевірялися.
- Перевірено базову клавіатурну поведінку й семантику; це не повний аудит відповідності WCAG.
- Публікацію GitHub і доступність її посилання потрібно підтвердити після фактичного створення репозиторію.

## Матеріали

- evidence/browser-checks.json — усі результати та приклад даних товару.
- evidence/nu-results.json — відповіді Nu HTML Checker.
- evidence/login.png, register.png, product-form.png — вигляд форм без CSS.
