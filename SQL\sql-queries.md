# SQL Testing

## 1. SELECT – получение всех пользователей

SELECT * FROM users;

## 2. WHERE – поиск пользователя по ID

SELECT * FROM users
WHERE id = 1;

## 3. ORDER BY – сортировка пользователей

SELECT * FROM users
ORDER BY name ASC;

## 4. COUNT – подсчёт пользователей

SELECT COUNT(*) FROM users;

## 5. JOIN – объединение таблиц

SELECT users.name, orders.order_id
FROM users
JOIN orders
ON users.id = orders.user_id;

## 6. Проверка пустых значений

SELECT * FROM users
WHERE email IS NULL;
