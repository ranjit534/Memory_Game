## Memory Game

This is a simple memory game where the objective is to find pairs of matching pictures to earn points. The game is built using HTML, JavaScript, and CSS.

### Game Rules
- At the beginning of each game, a set of cards with different pictures is displayed face-down on a grid.
- The player can flip two cards at a time by clicking on them.
- If the flipped cards match, they remain face-up, and the player earns a point.
- If the flipped cards do not match, they are flipped back face-down.
- The player continues flipping cards until all pairs are found.
- The game ends when all pairs have been matched.
- A congratulatory message is shown when the game is completed.

### How to Play
1. Launch the game by opening the HTML file in a web browser.
2. You will see a grid of face-down cards.
3. Click on any card to flip it.
4. Click on another card to reveal its picture.
5. If the two cards match, they will remain face-up, and you earn a point.
6. If the cards do not match, they will be flipped back face-down.
7. Continue flipping pairs of cards until all matches are found.
8. The game ends when all pairs have been matched.
9. If you successfully match all pairs, a congratulatory message will be shown.

### Technologies Used
- HTML: Used to structure the game layout and elements.
- CSS: Used to style the game and cards.
- JavaScript: Used to implement the game logic, card flipping, matching, and score tracking.

### How to Customize
If you want to customize the game, you can modify the following:

- Card Images: You can replace the images used for the cards by updating the `img` paths in the `cardArray` variable.
- Card Back: You can change the back image of the cards by modifying the path in the `card.setAttribute('src', 'images/blank.png')` line in the `createBoard` function.
- Card Front: You can update the front image of the cards by changing the `img` path in the `this.setAttribute('src', cardArray[cardId].img)` line in the `flipCard` function.
- Grid Size: You can adjust the size of the grid by adding or removing objects from the `cardArray` variable. Just make sure to maintain pairs of the same card.

Feel free to modify the code and add your own creativity to make the game more enjoyable!

Enjoy playing the memory game!
