class: slide-fullscreen-content, slide-ruda
background-image: url(../images/general/Primary.png)

# Webowe Pogawędki #7

---

class: master-center

<video src="../videos/podcast.mp4" controls autoplay loop></video>
<br/>.slim[(odpisanie video)]

---

# Windows Terminal 1.0

<img src="images/terminal-preview.png"
    style="
        position: absolute;
        right: 80px;
        top: 100px;
        width: 400px;
        box-shadow: none;
    ">

<div style="height: 330px"></div>

* <https://devblogs.microsoft.com/commandline/windows-terminal-1-0/>
* <https://github.com/microsoft/terminal>

---

# React Native dla macOS

<div style="height: 350px"></div>

* <https://microsoft.github.io/react-native-windows/blog/2020/05/19/rn4mupdadates>

---

# _WarsawJS Workshop #44_

<img src="images/Promo.png" style="width: 600px">

Źródło: <https://www.facebook.com/events/550742222516496/>

---

# eslint-plugin-smells 🛠

<div style="height: 250px"></div>

* <https://www.youtube.com/watch?v=JVlfj7mQZPo>
* <https://github.com/elijahmanor/eslint-plugin-smells>

---

# .size50[Łatwe i przyjemne Animacje CSS] 🛠

<div style="height: 250px"></div>

* <https://animista.net/play/attention/shake>

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
background-image: url(../images/general/Plain-Vertical.png)

# Make my day 😂

<img src="images/EXabA7xXgAErBZN.jpeg" style="width: 400px">

---

class: middle, slide-invert-colors
background-image: none

<img src="../images/icons/004-music-note.svg" style="
    position: absolute;
    top: 150px;
    right: 100px;
    width: 300px;
">

## .size35[`Morning Sunshine New Progression`]

#### MYSEN

<div style="width: 470px; margin: 50px 0;"><hr/></div>

Wykonawca: MYSEN

---

class: slide-fullscreen-content, slide-ruda
background-image: url(../images/general/Primary.png)

# Thanks
