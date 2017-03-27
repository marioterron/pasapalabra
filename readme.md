[![HTML5 & CSS3 Standard](https://www.w3.org/html/logo/badge/html5-badge-h-css3-semantics.png)](http://www.w3.org/)  [![Standard - JavaScript Style Guide](https://img.shields.io/badge/code%20style-standard-brightgreen.svg)](http://standardjs.com/)

## Pasapalabra Game
Version of the Pasapalabra game **_created with HTML, CSS and JavaScript._**

---

### How it works
- Open the demo version [here](https://marioterron157.github.io/pasapalabra/)
- Once opened click on **Jugar** to start game

![Click play to start game]()

- Read the sentence under the letters and **write in the blank box the answer**.
- Press **Enviar** to send the answer.
- If you don't know the answer, press on **Pasapalabra** and you _can answer later_.

![Sentence and answer]()

- If the answer is **_correct_** the letter will turn **green**, if it is **_wrong_** it will turn **red**.

![Colors letters]()

- If the countdown arrives to **0** the game ends.
- When the **game is finished**, the correct results are shown.


![Game Finished]()

### How to change the words for others
- In the file **script.js** _(it is inside the folder js)_, from **line 3 to 27 are the words**, to put others only have to be replaced by the new words.
- The order of each word should be:
```javascript
    new Word (idNumber, 'letter', ,'hint', 'definition', 'word')
```
