# Swag Labs — Smoke Checklist

## Scope

Проверка основной работоспособности формы авторизации Swag Labs.

## Test environment

- URL: https://www.saucedemo.com/
- Browser: Google Chrome
- Test type: Manual testing
- Approach: Black-box testing

## Status legend

- ⬜ Not Run
- ✅ Passed
- ❌ Failed
- ⚠️ Blocked

## Checklist

| ID | Проверка | Статус |
|---|---|:---:|
| SM-01 | Страница авторизации успешно открывается | ⬜ |
| SM-02 | Поле `Username` отображается | ⬜ |
| SM-03 | Поле `Password` отображается | ⬜ |
| SM-04 | Кнопка `Login` отображается и доступна для нажатия | ⬜ |
| SM-05 | В поле `Username` можно вводить данные | ⬜ |
| SM-06 | В поле `Password` можно вводить данные | ⬜ |
| SM-07 | Введенный пароль скрывается маской | ⬜ |
| SM-08 | Пользователь может авторизоваться с валидными учетными данными | ⬜ |
| SM-09 | После успешной авторизации открывается страница товаров | ⬜ |
| SM-10 | При вводе неверных учетных данных отображается сообщение об ошибке | ⬜ |

## Test data

| Тип данных | Username | Password |
|---|---|---|
| Валидные данные | `standard_user` | `secret_sauce` |
| Невалидные данные | `invalid_user` | `invalid_password` |
