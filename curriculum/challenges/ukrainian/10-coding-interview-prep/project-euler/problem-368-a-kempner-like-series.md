---
id: 5900f4dd1000cf542c50ffef
title: 'Задача 368: Послідовність в стилі Кемпнер'
challengeType: 5
forumTopicId: 302029
dashedName: problem-368-a-kempner-like-series
---

# --description--

Гармонічна послідовність $1 + \dfrac{1}{2} + \dfrac{1}{3} + \dfrac{1}{4} + \ldots$ добре відома як розбіжна.

Якщо ж опустити з цієї послідовності кожне значення, де в знаменнику є 9, послідовність досить чудово сходиться приблизно до 22.9206766193. Ця змінена гармонічна послідовність називається серією Кемпнера.

Тепер розглянемо іншу модифіковану гармонічну послідовність не включаючи з гармонічної послідовності кожне значення, де знаменник має 3 або більше рівних послідовних цифр. Можна переконатися, що з перших 1200 значень гармонічної послідовності буде пропущено лише 20.

20 опущених значень:

$$\dfrac{1}{111}, \dfrac{1}{222}, \dfrac{1}{333}, \dfrac{1}{444}, \dfrac{1}{555}, \dfrac{1}{666}, \dfrac{1}{777}, \dfrac{1}{888}, \dfrac{1}{999}, \dfrac{1}{1000}, \dfrac{1}{1110}, \\\\ \dfrac{1}{1111}, \dfrac{1}{1112}, \dfrac{1}{1113}, \dfrac{1}{1114}, \dfrac{1}{1115}, \dfrac{1}{1116}, \dfrac{1}{1117}, \dfrac{1}{1118}, \dfrac{1}{1119}$$

Ця послідовність також сходиться.

Знайдіть значення, до якого сходиться послідовність. Дайте відповідь заокруглену до 10 цифр після десяткової коми.

# --hints--

`kempnerLikeSeries()` повинен повертатися як `253.6135092068`.

```js
assert.strictEqual(kempnerLikeSeries(), 253.6135092068);
```

# --seed--

## --seed-contents--

```js
function kempnerLikeSeries() {

  return true;
}

kempnerLikeSeries();
```

# --solutions--

```js
// solution required
```
