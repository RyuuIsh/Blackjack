# Blackjack
A Python-based implementation of the classic card game Blackjack. Play against the computer in this interactive command-line game, complete with realistic scoring and decision-making rules.

## Our Blackjack House Rules

- The deck is unlimited in size.
- There are no jokers.
- The Jack/Queen/King all count as 10.
- The the Ace can count as 11 or 1.
- Use the following list as the deck of cards:
- cards = [11, 2, 3, 4, 5, 6, 7, 8, 9, 10, 10, 10, 10]
- The cards in the list have equal probability of being drawn.
- Cards are not removed from the deck as they are drawn.
- The computer is the dealer.

## Features
- Dynamic Card Dealing: Cards are dealt randomly from a standard deck.
- Accurate Scoring: Implements blackjack rules, including handling Aces as 1 or 11.
- Realistic Gameplay:
-- The player can "hit" (get another card) or "stand" (pass).
-- The computer continues drawing cards until its score reaches at least 17.
- Blackjack Rules:
-- Win with a natural blackjack (21 with the first two cards).
-- Lose if your score exceeds 21.
-- Computer follows standard dealer rules.
- Replay Option: Easily restart the game to play multiple rounds.

## Future Improvements
- Implement multiplayer support.
- Enhance graphics by creating a graphical user interface (GUI).
