class: slide-fullscreen-content, slide-ruda
background-image: url(../images/general/Primary.png)

# Webowe Pogawędki #1

---

# Dekoratory w <span class="slim">JavaScript</span>

<div style="height: 300px"></div>

<https://github.com/piecioshka/test-decorators>

---

# Finalna lista nowych rzeczy w <span class="slim">ES2020</span>

<div style="height: 250px"></div>

<https://2ality.com/2019/12/ecmascript-2020.html>

---

# Narzędzie do testów

<div style="height: 300px"></div>

* <https://webhook.site>
* <https://twitter.com/MichalZalecki/status/1247119937317068800>

---

# Darmowe kursy z powodu #lockdown

<div style="height: 220px"></div>

* <https://fullstackopen.com/en>
* <https://www.pluralsight.com/offer/2020/free-april-month>

---

# <del>Deno Community <span class="slim">umiera!</span></del>

<img class="float-left" src="images/deno-warsaw/deno-poland.png" style="width: 500px">
<img class="float-left" src="images/deno-warsaw/deno-warsaw.png" style="width: 500px">

<div class="clear"></div>
<br/>2020-04-06

---

# Nowa wersja Expo

<div style="height: 300px"></div>
<https://blog.expo.io/expo-sdk-37-is-now-available-dd5770f066a6>

---

# _WarsawJS Workshop #43_

<img src="images/warsawjs/Promo.png" style="width: 600px">

Źródło: <https://www.facebook.com/events/1451686585009422/>

---

## .bold[Jak usunąć właściwość w obiekcie?]

.size25[

```js
const car = {
    price: '300',
    color: 'purple'
};
```

```js
// Delete Operator
delete car.price;
console.log(car); // {color: "purple"}
```

```js
// Destructuring Assignment + Spread Operator
const { price, ...carWithoutPrice } = car;
console.log(carWithoutPrice); // {color: "purple"}
```

]

Źródło: <https://twitter.com/housecor/status/1243562849311563777>

---

# Dyskusja 🎙

<div style="height: 250px"></div>

* Kto używa <a href="https://prettier.io/">Prettiera</a> i jak?
* Przykład na projekcie z Git `pre-commit`
    + <https://github.com/piecioshka/test-prettier>

---

# Make my day 😂

Jak można się pomylić:

<img src="images/tweet-jake.jpeg">

Źródło: <https://twitter.com/jaffathecake/status/1243219575845597184>

---

class: slide-fullscreen-content, slide-ruda
background-image: url(../images/general/Primary.png)

# Thanks
