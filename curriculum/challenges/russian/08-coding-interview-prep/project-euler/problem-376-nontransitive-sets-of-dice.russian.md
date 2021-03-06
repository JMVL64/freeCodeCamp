---
id: 5900f4e51000cf542c50fff7
challengeType: 5
title: 'Problem 376: Nontransitive sets of dice'
videoUrl: ''
localeTitle: 'Задача 376: Непереходные множества кубиков'
---

## Description
<section id="description"> Рассмотрим следующий набор кубиков с нестандартными пипами: <p> Die A: 1 4 4 4 4 4 Die B: 2 2 2 5 5 5 Die C: 3 3 3 3 3 6 </p><p> В игре играют два игрока, которые в свою очередь собирают штамп и катят его. Побеждает игрок, который набирает наибольшее значение. </p><p> Если первый игрок выбирает A, а второй игрок выбирает B, мы получаем P (побеждает второго игрока) = 7/12&gt; 1/2 </p><p> Если первый игрок выбирает штамп B, а второй игрок выбирает die C, мы получаем P (выигрывает второй игрок) = 7/12&gt; 1/2 </p><p> Если первый игрок выбирает кубик C, а второй игрок выбирает die A, мы получаем P (второй игрок выигрывает) = 25/36&gt; 1/2 </p><p> Так что, какой бы ни был первый игрок, второй игрок может выбрать другого умения и иметь более 50% шансов на победу. Набор кубиков, обладающих этим свойством, называется непереходным множеством кубиков. </p><p> Мы хотим исследовать, сколько существует множеств непереходных кубиков. Будем считать следующие условия: Есть три шестигранных кубика, каждая из которых имеет от 1 до N пипсов включительно. Кубики с одинаковым набором пипсов равны, независимо от того, на какой стороне на матрице расположены точки. То же самое значение пика может появляться на нескольких игральных костях; если оба игрока откатывают то же значение, ни один из игроков не выигрывает. Множества кубиков {A, B, C}, {B, C, A} и {C, A, B} являются одним и тем же множеством. </p><p> При N = 7 мы находим 9780 таких множеств. Сколько из них существует для N = 30? </p></section>

## Instructions
undefined

## Tests
<section id='tests'>

```yml
tests:
  - text: <code>euler376()</code> должен вернуться 973059630185670.
    testString: 'assert.strictEqual(euler376(), 973059630185670, "<code>euler376()</code> should return 973059630185670.");'

```

</section>

## Challenge Seed
<section id='challengeSeed'>

<div id='js-seed'>

```js
function euler376() {
  // Good luck!
  return true;
}

euler376();

```

</div>



</section>

## Solution
<section id='solution'>

```js
// solution required
```
</section>
