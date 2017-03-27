## Pasapalabra Game
Version of the Pasapalabra game **_created with HTML, CSS and JavaScript._**

---

### How it works
- Open the demo version [here](https://marioterron157.github.io/pasapalabra/)
- Once opened click on **Jugar** to start game

![Click play to start game](https://github.com/MarioTerron157/pasapalabra/blob/master/img/1.jpeg)

- Read the sentence under the letters and **write in the blank box the answer**.
- Press **Enviar** to send the answer.
- If you don't know the answer, press on **Pasapalabra** and you _can answer later_.

![Sentence and answer](https://github.com/MarioTerron157/pasapalabra/blob/master/img/5.jpeg)

- If the answer is **_correct_** the letter will turn **green**, if it is **_wrong_** it will turn **red**.

![Colors letters](https://github.com/MarioTerron157/pasapalabra/blob/master/img/3.jpeg)

- If the countdown arrives to **0** the game ends.
- When the **game is finished**, the correct results are shown.


![Game Finished](https://github.com/MarioTerron157/pasapalabra/blob/master/img/4.jpeg)

### How to change the words for others
- In the file **script.js** _(it is inside the folder js)_, from **line 3 to 27 are the words**, to put others only have to be replaced by the new words.
- The order of each word should be:
```javascript
    new Word (idNumber, 'letter', ,'hint', 'definition', 'word')
```
