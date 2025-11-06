# En: Skillbox_JavaScript-module-19_classes_task-2
# Ru: Skillbox_JavaScript-модуль-19_классы_задание-2

#### Please give this project a star ⭐ if you found it interesting
#### Пожалуйста, поставьте звезду ⭐ если этот проект Вас заинтересовал

### En:
#### Task 
Task 2
Extend the delivery list mini-application from Task 1:
Add an “Edit” button to each delivery card and introduce an additional delivery status attribute that affects the card’s appearance.
Each delivery should have one of the following three statuses:
- delivery — in transit
- delivered — delivered
- canceled — canceled
To complete this task, use inheritance:
Based on the existing Delivery class, create a new class called EditDelivery.
Example initialization:
new EditDelivery("Dmitry", "7 Zadachnaya St.", 3, "delivered");


When the “Edit” button is clicked, a delivery editing window should appear with the following fields:
- Name — text input
- Address — text input
- Distance — text input
- Status — dropdown menu
The new features (editing and status handling) should be implemented in the inherited class.
The delivery status must be modifiable from outside the class.


_________________________________________________________________________________________________

### Ru:
#### Задача 2
Доработайте мини-приложение списка доставок из задания 1: создайте для каждой карточки кнопку для изменения (редактирования) доставки и дополнительный атрибут со статусом доставки, влияющий на внешний вид карточки. Всего у доставки должно быть три статуса:

delivery — доставляется;
delivered — доставлен;
canceled — отменён.

Для выполнения задачи используйте наследование и на основе готового класса Delivery создайте новый EditDelivery. 

Пример инициализации: 

new EditDelivery("Дмитрий", "ул. Задачная, д. 7", 3, "delivered");
При клике на кнопку «Изменить» должно отобразиться окно редактирования доставки с полями:

имя — текстовое поле;
адрес — текстовое поле;
расстояние — текстовое поле;
статус — выпадающий список.

Новые возможности (редактирование и добавление статуса) должны быть выполнены в унаследованном классе. Для статуса доставки предусмотрите возможность изменения за пределами класса.

## En: Technologies Used
## Ru: Используемые технологии

- HTML5
- CSS
- JavaScript

## En: License
This project is for educational purposes only. Do not copy or redistribute without permission.

## Ru: Лицензия
Этот проект предназначен исключительно для образовательных целей. Не копируйте и не распространяйте без разрешения.

## En: Demonstration
## Ru: Демонстрация
![1_1-2](https://github.com/user-attachments/assets/7f5da135-2f2e-40e2-99ae-42d2dae139ca)































