---
id: 5900f40d1000cf542c50ff1f
title: 'Завдання 160: кінцеві цифри факторіала'
challengeType: 1
forumTopicId: 301794
dashedName: problem-160-factorial-trailing-digits
---

# --description--

Для будь-якого $N$ нехай $f(N)$ буде останніми п’ятьма цифрами перед кінцевими нулями в $N!$.

Наприклад,

$$\begin{align}   & 9! = 362880 \\; \text{тому} \\; f(9) = 36288 \\\\
  & 10! = 3628800 \\; \text{тому} \\; f(10) = 36288 \\\\ & 20! = 2432902008176640000 \\; \text{тому} \\; f(20) = 17664 \end{align}$$

Знайдіть $f(1 000 000 000 000)$

# --hints--

`factorialTrailingDigits()` має повернути `16576`.

```js
assert.strictEqual(factorialTrailingDigits(), 16576);
```

# --seed--

## --seed-contents--

```js
function factorialTrailingDigits() {

  return true;
}

factorialTrailingDigits();
```

# --solutions--

```js
// solution required
```
