# nathan-problem
solving problem in movie x+y using pythons

Question:

Twenty random cards are placed in a row all face down. A turn consists of taking two adjacent cards where the left one is face up and the right one can be face up or face down and flipping them both. Show that this process must terminate. (with all the cards facing up).

Answer:

Give 0 to face up cards and 1 to face down.

Initially all the cards are face down so the initial row is 1111...

A move can either change 10 to 01 or 11 to 00 and so the resulting number in binary is strictly less than the previous one.

Thus starting from 1111.. the number decreases with each move, hence the moves must eventually terminate at 000…

No matter what face down card you choose you will end up getting all face up cards
