# percent-of-time

Процент прошедшего времени

```php
$day1 = strtotime(date('Y-03-20'));              // Начало
$today = strtotime(date('Y-m-d'));;               // Текущая дата
$day2 = strtotime(date('Y-03-30'));              // Конечная дата  
$procent = ($day2-$today)*100/($day2-$day1);

echo "Прошло ".$procent."% времени";
```
