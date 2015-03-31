### My Library:  games/cards

Narrative:

---------

The games/cards module provides a toolbox for creating card games. I explored on creating a deck, shuffling the cards and setting limits on the deck.

Code I wrote:

-------------

```
#lang racket
(require games/cards)
(define table (make-table "test" 5 2)); defines a table of 5x2
(send table show #t) ; shows the table which is empty initially
```
[This will display empty table: ](http://weblab.cs.uml.edu/~asuriset/91301/FP2picture1.png)

```
(define my-deck (make-deck))
(send table add-cards my-deck 1 1)
```
[Displays the cards in the table with the cards are all face-down, sorted lowest-suit then lowest-value: ](http://weblab.cs.uml.edu/~asuriset/91301/FP2picture2.png)
[The order can be seen from the drawn cards: ](http://weblab.cs.uml.edu/~asuriset/91301/FP2picture3.png)

