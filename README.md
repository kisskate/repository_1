# Общее описание решения
1) Клонировала репозиторий
2) Открыла папку geometric_lib
3) Создала ветку new_1
4) Переключилась на ветку
5) Добавила файлы: rectangle.py, triangle.py
6) Сделала сообщение об изменениях в файлах
7) Исправила ошибку в файле и сделала соответствующее сообщение
8) Посмотрела историю всех коммитов
9) Вывела хэши двух последних файлов
10) Переклюсчилась на ветку main и произвела слияние веток
11) Сделала pull request
12) Удалила ветку new_1
## Функции и примеры вызова
## Circle
¬¬¬python
def area(r):  
return math.pi * r * r
¬¬¬
#### Принимает значение радиуса и возвращает значение площади

def perimeter(r):  
return 2 * math.pi * r
#### Принимает значение радиуса и возвращает значение периметра
#### Примеры вызова:  
input 2  
output 12.56 12.56  
## Rectangle
def area(a, b):  
return a * b
#### принимает значения сторон прямоугольника и возвращает значение площади
def perimeter(a, b):  
return 2*(a + b)
#### принимает значения сторон прямоугольника и возвоащает значение периметра
#### Примеры вызова:  
input 2 4  
output 8 12
## Romb
def area(a, b):  
return (a * b) / 2
#### функция принимает значение диагоналей ромба и возвращает значение площади
def perimeter(a):  
return 4 * a
#### функция принимает значение стороны ромба и возвращает значение периметра
#### Примеры вызова:  
input 2 4  
output 4  
input 2  
output 8  
## Square
def area(a):  
return a * a
#### функция принимает значение стороны квадрата и возвращает его площадь
def perimeter(a):  
return 4 * a
#### функция принимает значение стороны квадрата и возвращает его периметр
#### Примеры вызова:  
input 2  
output 4 8  
## Triangle
def area(a, h):  
return a * h / 2
#### принимает на вход значение стороны и высоты треугольника, возвращает S
def perimeter(a, b, c):  
return a + b + c
#### принимает на вход значения трёх сторон треугольника, а возвращает значение периметра
#### Примеры вызова:  
input 2 4  
output 4   
input 2 4 10  
output 16  
# История изменения проекта с хэшами коммитов
commit 77697bf9617e772af75b6fe78ce3281c7c53d274 (origin/main, origin/HEAD)
Merge: a8fda2c e8afe28
Author: kisskate <144919979+kisskate@users.noreply.github.com>
Date:   Tue Sep 26 18:38:36 2023 +0300

    Merge pull request #1 from Trechiket/new_F

    add romb
commit e8afe28ca98ad1f9306d83fabbe5ebfc0e2d8e92
Author: Trechiket <gregory.b9@mail.ru>
Date:   Tue Sep 26 18:36:53 2023 +0300

    add romb

diff --git a/romb.py b/romb.py
new file mode 100644
index 0000000..508bf5c
--- /dev/null
+++ b/romb.py
@@ -0,0 +1,5 @@
+def area(a, b):
+    return (a * b) / 2
+
+def perimeter(a):
+    return 4 * a
+ commit a8fda2cdf7d3443fec4ff2c104094e2838a35afb
  Author: kisskate <linelakate@gmail.com>
  Date:   Tue Sep 26 12:14:04 2023 +0300

  errors are excluded

diff --git a/rectangle.py b/rectangle.py
index 70ee97d..48b048f 100644
--- a/rectangle.py
+++ b/rectangle.py
@@ -1,4 +1,4 @@
def area(a, b):
return a * b
def perimeter(a, b):
-return a + b
+return 2*(a + b)
diff --git a/triangle.py b/triangle.py
new file mode 100644
index 0000000..62291ed
--- /dev/null
+++ b/triangle.py
@@ -0,0 +1,4 @@
+def area(a, h):
+return a * h / 2
+def perimeter(a, b, c):
+return a + b + c
commit 4299a95184a9b0fa48c6d997cd64c61b6eefe167
Author: kisskate <linelakate@gmail.com>
Date:   Tue Sep 26 12:10:32 2023 +0300

    add file

diff --git a/rectangle.py b/rectangle.py
new file mode 100644
index 0000000..70ee97d
--- /dev/null
+++ b/rectangle.py
@@ -0,0 +1,4 @@
+def area(a, b):
+return a * b
+def perimeter(a, b):
+return a + b
commit d078c8d9ee6155f3cb0e577d28d337b791de28e2
Author: smartiqa <info@smartiqa.ru>
Date:   Thu Mar 4 14:55:29 2021 +0300

    L-03: Docs added

diff --git a/docs/README.md b/docs/README.md
new file mode 100644
index 0000000..63f8727
--- /dev/null
+++ b/docs/README.md
@@ -0,0 +1,10 @@
+# Math formulas
+## Area
+- Circle: S = πR²
+- Rectangle: S = ab
+- Square: S = a²
+
+## Perimeter
+- Circle: P = 2πR
+- Rectangle: P = 2a + 2b
+- Square: P = 4a
\ No newline at end of file
commit 8ba9aeb3cea847b63a91ac378a2a6db758682460
Author: smartiqa <info@smartiqa.ru>
Date:   Thu Mar 4 14:54:08 2021 +0300

    L-03: Circle and square added

diff --git a/circle.py b/circle.py
new file mode 100644
index 0000000..c3eb864
--- /dev/null
+++ b/circle.py
@@ -0,0 +1,10 @@
+import math
+
+
+def area(r):
+    return math.pi * r * r
+
+
+def perimeter(r):
+    return 2 * math.pi * r
+
diff --git a/square.py b/square.py
new file mode 100644
index 0000000..0f98724
--- /dev/null
+++ b/square.py
@@ -0,0 +1,7 @@
+
:

