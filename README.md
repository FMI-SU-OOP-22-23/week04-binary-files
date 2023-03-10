# Двоични файлове, кога и как да ги ползваме

## Преди това обаче какво е reinterpret_cast? https://en.cppreference.com/w/cpp/language/reinterpret_cast

# Задачи

## Задача 1
Разглеждаме двоичен файл numbers.dat. В него се съдържат целочислени стойности от тип int. Искаме да върнем това число, което е най-голямото от тях.

## Задача 2
Разглеждаме
struct Order {
double gross_price;
double vat;
int customerID;
}, която описва за един магазин направена поръчка
В двойчен файл storeOrders.dat е запсана информацията за магазин и поръчките, които са направени, посредством тази структура. Искаме да разберем, кой потребител е направил най-много поръчки, кой е направил най-скъпата поръчка, и сумарно кой е платил най-много.
Тази информация отново трябва да се запише в двоичен файл topCustomers.dat

Да има възможност да се въвежда информация за нови поръчки през конзолата, докао програмата работи и след това те да бъдат записвани във файла storeOrders.dat

## Задача 3
Разглеждаме структура
struct Customer {
  char* name;
  int customerID;
  int age;
}

Подгответе тестови данни за тази структура в двойчен файл customers.dat . Има ли потенциален проблем с char* name?
На базата на задача 2, да се изведат имената и възрастта на всички топ потребители и да се запишат във файл topCustomersInfo.dat. 
