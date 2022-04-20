# Web-Skills-with-Shikmamaru(2)
![Shikamaru](https://github.com/whitebird1016/Web-Skills-with-Shikmamaru/blob/main/1_HTGSqvOc52yfMwyLhCMjVA.jpeg)
<h2>Number Skills</h2>
<h3>1: Arrangement</h3>

```
const num1 = ~~ 1.19;
const num2 = 2.29 | 0;
const num3 = 3.09 >> 0;
// num1 num2 num3 => 1 2 3
```
<h3>2: Zero padding</h3>

```
const FillZero = (num, len) => num.toString().padStart(len, "0");
const num = FillZero(1234, 5);
// num => "01234"
```
<h3>3: Revolution value</h3>

```
const num1 = +null;
const num2 = +"";
const num3 = +false;
const num4 = +"169";
// num1 num2 num3 num4 => 0 0 0 169
```
<h3>4: Timestamp</h3>

```
const timestamp = +new Date("2022-03-22");
// timestamp => 1647907200000
```
<h3>5: Exact decimal</h3>

```
const RoundNum = (num, decimal) => Math.round(num * 10 ** decimal) / 10 ** decimal;
const num = RoundNum(1.2345, 2);
// num => 1.23
```
<h3>6: Parity</h3>

```
const OddEven = num => !!(num & 1) ? "odd" : "even";
const num = OddEven(2);
// num => "even"
```

<h3>7: Take min max</h3>

```
const arr = [0, 1, 2, 3];
const min = Math.min(...arr);
const max = Math.max(...arr);
// min max => 0 3
```

<h3>8: Generate range random numbers</h3>

```
const RandomNum = (min, max) => Math.floor(Math.random() * (max - min + 1)) + min;
const num = RandomNum(1, 10); // 5
```
