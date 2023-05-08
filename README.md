Download Link: https://assignmentchef.com/product/solved-standardcard
<br>
Consider the provided abstract Card class. You will implement a concrete subclass called StandardCard. You will also modify the Card class by adding appropriate (hidden) state.

A standard deck of cards consist of 52 cards. Each card has a rank (2, 3, …, 9, 10, Jack, Queen, King, Ace) and a suit (spades, hearts, clubs, diamonds).

The ordering of standard cards is first specified by suits and then by rank if two cards have the same suits. The ordering of suits is

<pre class="ql-syntax"><span class="hljs-attribute">diamonds</span> &lt; clubs &lt; hearts &lt; spades</pre>

If two standard cards have the same suit, then ordering is based on rank as follows

<pre class="ql-syntax">2 &lt; 3 &lt; ... &lt; 9 &lt; 10 &lt; Jack &lt; Queen &lt; King &lt; Ace</pre>

Two standard cards with the same suit and rank are equal to each other.

Be sure that all inherited methods are implemented as specified (either in this document or in the comments of Card).