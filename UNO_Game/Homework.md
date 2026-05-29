## <font color="Red"> **Homework - Complete the UNO Game Loop** </font>

Using the UNO project we built in class, continue improving the game.

### Required

1. Add a second player.

   The game should have:
   - Player 1
   - Player 2

2. Give each player 5 cards at the beginning of the game.

3. Let Player 1 and Player 2 take turns.

   On each turn:
   - print the current top card
   - print the current player's hand
   - ask the current player to choose a card
   - check whether the chosen card can be played

4. If the chosen card can be played:
   - remove it from the player's hand
   - make it the new top card

5. If the chosen card cannot be played:
   - tell the player the card cannot be played
   - the player should draw one card from the deck

6. The game should continue until one player has no cards left.

7. Print which player wins.

---

### Challenge

Add special cards:

- Skip
- Reverse
- Draw Two

For example:

- Skip: the next player loses their turn
- Reverse: changes the direction of play
- Draw Two: the next player draws 2 cards

---

### Bonus Challenge

Add Wild cards.

A Wild card should:
- be playable on any card
- let the player choose a new color