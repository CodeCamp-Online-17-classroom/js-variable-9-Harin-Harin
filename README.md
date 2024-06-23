# js-lab-9
### Lab9 DataTypes&Variable: ระบุค่า
ให้ระบุค่าของ a, b, c , d และ e หลังจากจบการทำงานในแต่ละ statements
หริณ มาเบ้า มิก

```JavaScript
let a = 1;
let b = 2;
let c = a++;
let d = ++c;
let e = ++d + d++ + d;
```
ค่า a, b, c , d และ e ที่ได้
```shell
statements 1   a = 1
app.js:4 statements 2   a = 1 ,b = 2
app.js:6 statements 3   a = 2 ,b = 2 ,c = 1
app.js:8 statements 4   a = 2 ,b = 2 ,c = 2 ,d = 2
app.js:10 statements 5   a = 2 ,b = 2 ,c = 2 ,d = 4 ,e = 10
```
