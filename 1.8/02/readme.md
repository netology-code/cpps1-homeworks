# Задача 2. Снова swap

### Описание
В этом задании наша задача - реализовать уже знакомую вам функцию `swap` (вспомнить можно [здесь](../../1.6/02)), но с помощью указателей, а не ссылок

### Пример работы программы
```
a = 5, b = 8
a = 8, b = 5
```
#### Подсказки

> Не читайте этот раздел сразу, попытайтесь сначала решить задачу самостоятельно :)

<details>

<summary>Подсказка. Что использовать для решения?</summary>

Для того, чтобы функция  `swap`  могла изменять значения в тех переменных, которые в неё передали, вы должны передать в функцию не сами переменные, а указатели на них. Внутри функции нужно применить к указателям операцию разыменования (`*`)

Для вывода на консоль использовать  `std::cout`

</details>