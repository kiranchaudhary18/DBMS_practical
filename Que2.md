
INSERT INTO MenuItems (item_id, item_name, price, category)
VALUES (1, 'Burger', 120, 'Fast Food');

INSERT INTO MenuItems (item_id, item_name, price, category)
VALUES (2, 'Pizza', 250, 'Fast Food');

INSERT INTO MenuItems (item_id, item_name, price, category)
VALUES (3, 'Coffee', 80, 'Beverage');



UPDATE MenuItems
SET price = 150
WHERE item_id = 1;


DELETE FROM MenuItems
WHERE item_id = 3;


SELECT AVG(price) AS average_price
FROM MenuItems;


SELECT SUM(price) AS total_price
FROM MenuItems;
