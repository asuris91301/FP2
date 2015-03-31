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




### My Library: (library name here)
Write what you did!
Remember that this report must include:
 
* a narrative of what you did
* the code that you wrote
* output from your code demonstrating what it produced
* any diagrams or figures explaining your work 
 
The narrative itself should be no longer than 350 words. Yes, you can add more files and link or refer to them. This is github, handling files is awesome and easy!

Ask questions publicly in the Piazza group.

### How to Do and Submit this assignment

1. To start, [**fork** this repository][forking].
1. Modify the README.md file and [**commit**][ref-commit] changes to complete your solution.
  2. (This assignment is just one README.md file, so you can edit it right in github without cloning)
  3. (You may need to clone and push if you want to add extra files)
1. [Create a **pull request**][pull-request] on the original repository to turn in the assignment.

<!-- Links -->
[piazza]: https://piazza.com/class/i55is8xqqwhmr?cid=411
[schedule]: https://piazza.com/class/i55is8xqqwhmr?cid=453
[markdown]: https://help.github.com/articles/markdown-basics/
[forking]: https://guides.github.com/activities/forking/
[ref-clone]: http://gitref.org/creating/#clone
[ref-commit]: http://gitref.org/basic/#commit
[ref-push]: http://gitref.org/remotes/#push
[pull-request]: https://help.github.com/articles/creating-a-pull-request

