# percent-of-time

Процент прошедшего времени

```php
$day_1 = strtotime(date('Y-03-20'));              // Начало
$today = strtotime(date('Y-m-d'));;               // Текущая дата
$day_2 = strtotime(date('Y-03-30'));              // Конечная дата  
$procent = ($day_2-$today)*100/($day_2-$day_1);

echo "Прошло ".$procent."% времени";
```
