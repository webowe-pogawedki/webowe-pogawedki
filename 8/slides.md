class: slide-fullscreen-content, slide-ruda
background-image: url(../images/general/Primary.png)

# Webowe Pogawędki #TODO

---

class: master-center

<video src="../videos/podcast.mp4" controls autoplay loop></video>
<br/>.slim[(odpinanie video)]

---

# TODO: News

<div style="height: 250px"></div>

* ...

---

# TODO: News

<div style="height: 250px"></div>

* ...

---

# 🛠 TODO: Tools

<div style="height: 250px"></div>

* ...

---

# 🛠 TODO: Tools

<div style="height: 250px"></div>

* ...

---

# Notatki początkującego frontendowca 💡

<div style="height: 200px"></div>

* <https://github.com/kasiaizak/notatki>
* <https://dev.kasiaizak.pl/>

---

# .size50[Mock Interfaces, Not Internals] 💡

```javascript
import React from "react";
import { render } from "@testing-library/react";
import App from "./App";

jest.mock("./utils/currency", () => {
  return {
    convert: jest.fn().mockImplementation(() => {
      return 1.42;
    }),
  };
});

test("renders learn react link", async () => {
  const { findByText } = render(<App />);
  const element = await findByText(/USD to CAD: 1.42/i);
  expect(element).toBeInTheDocument();
});
```

* <https://www.leighhalliday.com/mock-fetch-jest>

---

# Let's talk! 🗣

## Twitter pozwoli pracownikom pracować w domu<br/>NA ZAWSZE

<div style="height: 200px"></div>

* <https://www.buzzfeednews.com/article/alexkantrowitz/twitter-will-allow-employees-to-work-at-home-forever>

---

class: color-white
background-image: url(../images/general/Key_Right.png)
background-size: contain

# Make my day 😂

<img src="images/EXabA7xXgAErBZN.jpeg" style="width: 450px">

---

class: slide-thanks
background-image: url(../images/general/Key_Right.png)
background-size: contain

# Thanks

<div style="height: 100px"></div>

<div class="wrap width-60">

<div class="youtube">
    <img src="../images/icons/like.svg">
    <p>Spodobał Ci się film? <strong>Zostaw lajka</strong></p>
</div>

<div style="height: 50px"></div>

<!-- <iframe width="100%" height="166" scrolling="no" frameborder="no" allow="autoplay" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/100513066&color=%23ff5500&auto_play=false&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=true"></iframe> -->

<div style="height: 50px"></div>

<div class="music-player">
    <img class="note" src="../images/icons/004-music-note-yellow.svg">
    <div class="song">
        <h4 class="title">
            "Morning Sunshine New Progression"
            <a href="https://soundcloud.com/user-396861444/morning-sunshine-new-progression-1/s-935NEIbf2O8" target="_blank">
                <img class="icon" src="../images/icons/soundcloud.svg">
            </a>
        </h4>
        <p class="author">
            Wykonawca: <a href="">MYSEN</a>
        </p>
    </div>
</div>

</div>
