<!DOCTYPE html>
<html lang="uk">
<head>
<meta charset="UTF-8">
<title>Калькулятор- «Точка беззбитковості»</title>
<style type="text/css">
  a{
color: #fff;
text-decoration: none;
}
html{
background: #FFF8CC;
min-height: 100%;
font-family: Helvetica;
display: flex;
flex-direction: column;
}
body{
margin: 0;
padding: 0 15px;
display: flex;
flex-direction: column;
flex: auto;
}
button {
        width: 66px;
        height: 40px;
        margin: 5px;
        display: inline-block;
        background-color: #007BFF;
        color: white;
        text-align: center;
        line-height: 40px;
        cursor: pointer;
        border-radius: 5px;
        font-size: 18px;
        transition: background-color 0.3s ease;
    }
</head>
  <body>
  <div>
  <div>
<p>Початкові дані для розрахунку:</p>
  <p>Точка беззбитковості (в одиницях)= </p>
q1 = int (input("Постійні витрати: "))
q2 = int (input("Ціна продажу: "))
q3 = int (input("Змінні витрати на одиницю товару: "))
r=float(q1/(q2-q3))
  b="Точка беззбитковості (в одиницях)"
  t=b
 <h1>("Відповідь:",t," = ",r)</h1>
  </div>
  </div>
</body>
</html>
