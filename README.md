# Bulb ON/OFF Switch Project 💡

A simple and interactive web project built using **HTML** and **JavaScript DOM Manipulation** that allows users to turn a light bulb on and off with a click of a button.

---

## 🚀 Live Demo
* [View Live Website](https://github.com/Harshlokhande07/Bulb-ON-OFF) 

---

## 🛠️ Technologies Used
* **HTML5:** For structuring the webpage and buttons.
* **JavaScript (ES6):** For DOM manipulation and handling click events to change the bulb images dynamically.

---

## 💻 Live Visual Representation

Here is how the project functions in a web browser. When a user clicks the **Turn On** button, the JavaScript swaps the image to the lit bulb. Clicking **Turn Off** restores the unlit bulb image.

```text
       +---------------------------------------------+
       |             [ 💡 Bulb Project ]             |
       +---------------------------------------------+
                              |
                     +-----------------+
                     |                 |
                     |      OFF        |  <-- Default State (bulb.off.png)
                     |                 |
                     +-----------------+
                        /           \
                       /             \
            [ Turn ON ]               [ Turn OFF ]
            (Click event)             (Click event)
                  |                         |
                  v                         v
       +-----------------+       +-----------------+
       |                 |       |                 |
       |       ON        |       |      OFF        |  <-- Switched State (bulb.on.png)
       |                 |       |                 |
       +-----------------+       +-----------------+
