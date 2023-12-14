<!DOCTYPE html>
<html lang="uk">
<head>
<meta charset="UTF-8">
<title>Калькулятор- «Точка беззбитковості»</title>
<style type="text/css">
</head>
  <body>
<h1>Початкові дані для розрахунку:</h1>
  <p>Точка беззбитковості (в одиницях)= </p>
q1 = int (input("Постійні витрати: "))
q2 = int (input("Ціна продажу: "))
q3 = int (input("Змінні витрати на одиницю товару: "))
r=float(q1/(q2-q3))
  print ("Відповідь:",r)
</body>
</html>
