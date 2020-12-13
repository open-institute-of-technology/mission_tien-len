# Tiến Lên

![Angel and Grim Reaper Playing Card Game](angel_and_grim_reaper_playing_card_game.jpg)

Tiến Lên is a Vietnamese [card game](https://en.wikipedia.org/wiki/Ti%E1%BA%BFn_l%C3%AAn#Rules) using the [standard deck of fifty-two playing cards](https://en.wikipedia.org/wiki/Standard_52-card_deck).

Tiến Lên is a _climbing game_ in which the aim is for players to get rid of their cards as soon as possible by beating combinations of cards played by the other players. Each player in turn must play a higher card (or combination of cards) than the previous player. A player who cannot or does not wish to beat the previous play can pass. This continues for as many rounds as necessary until someone makes a play that no one will beat. That player wins the "trick" and leads to another one.

The objective of the game is for a player to be the first to get rid of all of their cards by playing various combinations.

## Card Notation

We use a de-facto standard notation to reference card ranks and suits.

### Card Ranks

The rank of a card is noted with one of the following character written in **uppercase**:

| 2   | 3   | 4   | 5   | 6   | 7   | 8   | 9   | 10  | Jack | Queen | King | Ace |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | ---- | ----- | ---- | --- |
| `2` | `3` | `4` | `5` | `6` | `7` | `8` | `9` | `T` | `J`  | `Q`   | `K`  | `A` |

### Card Suits

The suit of a card is noted with one of the following character written in **lowercase**:

| Hearts | Diamonds | Clubs | Spades |
| ------ | -------- | ----- | ------ |
| `h`    | `d`      | `c`   | `s`    |
| `♥`    | `♦`      | `♣`   | `♠`    |

_Note: Unicode characters are often used nowadays._

### Examples

Hereafter, we provide some examples of cards and their _standard_ notation:

|                                              | Ace of Clubs       | King of Spades     | Queen of Hearts    | Jack of Spades     | 10 of Diamonds     | 2 of Hearts        |
| -------------------------------------------- | ------------------ | ------------------ | ------------------ | ------------------ | ------------------ | ------------------ |
| Card                                         | ![](assets/Ac.png) | ![](assets/Ks.png) | ![](assets/Qh.png) | ![](assets/Js.png) | ![](assets/Td.png) | ![](assets/2h.png) |
| [ASCII](https://en.wikipedia.org/wiki/ASCII) | `Ac`               | `Ks`               | `Qh`               | `Js`               | `Td`               | `2h`               |
| Unicode                                      | `A♣`               | `K♠`               | `Q♥`               | `J♠`               | `T♦`               | `2♥`               |

## Card Ranking

The ranking of the cards from highest to lowest:

- Based on their rank: 2 , Ace (`A`), King (`K`), Queen (`Q`), Jack (`J`), 10 (`T`), 9, 8, 7, 6, 5, 4, 3;
- Based on their suit: Hearts (`H`), Diamonds (`D`), Clubs (`C`), Spades (`S`).

|     | `2`                | `A`                | `K`                | `Q`                | `J`                | `10`               | `9`                | `8`                | `7`                | `6`                | `5`                | `4`                | `3`                |
| --- | ------------------ | ------------------ | ------------------ | ------------------ | ------------------ | ------------------ | ------------------ | ------------------ | ------------------ | ------------------ | ------------------ | ------------------ | ------------------ |
| `H` | ![](assets/2h.png) | ![](assets/Ah.png) | ![](assets/Kh.png) | ![](assets/Qh.png) | ![](assets/Jh.png) | ![](assets/Th.png) | ![](assets/9h.png) | ![](assets/8h.png) | ![](assets/7h.png) | ![](assets/6h.png) | ![](assets/5h.png) | ![](assets/4h.png) | ![](assets/3h.png) |
| `D` | ![](assets/2d.png) | ![](assets/Ad.png) | ![](assets/Kd.png) | ![](assets/Qd.png) | ![](assets/Jd.png) | ![](assets/Td.png) | ![](assets/9d.png) | ![](assets/8d.png) | ![](assets/7d.png) | ![](assets/6d.png) | ![](assets/5d.png) | ![](assets/4d.png) | ![](assets/3d.png) |
| `C` | ![](assets/2c.png) | ![](assets/Ac.png) | ![](assets/Kc.png) | ![](assets/Qc.png) | ![](assets/Jc.png) | ![](assets/Tc.png) | ![](assets/9c.png) | ![](assets/8c.png) | ![](assets/7c.png) | ![](assets/6c.png) | ![](assets/5c.png) | ![](assets/4c.png) | ![](assets/3c.png) |
| `S` | ![](assets/2s.png) | ![](assets/As.png) | ![](assets/Ks.png) | ![](assets/Qs.png) | ![](assets/Js.png) | ![](assets/Ts.png) | ![](assets/9s.png) | ![](assets/8s.png) | ![](assets/7s.png) | ![](assets/6s.png) | ![](assets/5s.png) | ![](assets/4s.png) | ![](assets/3s.png) |

## Card Combinations

The legal plays in the game are as follows:

|                     |                                         |                    |                    |                    |                    |                    |                    |
| ------------------- | --------------------------------------- | ------------------ | ------------------ | ------------------ | ------------------ | ------------------ | ------------------ |
| **Single**          | A single card                           | ![](assets/3s.png) |                    |                    |                    |                    |                    |
| **Pair**            | Two cards of the same rank              | ![](assets/Qd.png) | ![](assets/Qs.png) |                    |                    |                    |                    |
| **Triple**          | Three cards of the same rank            | ![](assets/5d.png) | ![](assets/5h.png) | ![](assets/5c.png) |                    |                    |                    |  |
| **Four of a kind**  | Four cards of the same rank             | ![](assets/9h.png) | ![](assets/9d.png) | ![](assets/9c.png) | ![](assets/9s.png) |                    |                    |
| **Sequence**        | Three or more cards of consecutive rank | ![](assets/4d.png) | ![](assets/5s.png) | ![](assets/6h.png) |                    |                    |                    |
| **Double Sequence** | Three or more pairs of consecutive rank | ![](assets/Th.png) | ![](assets/Ts.png) | ![](assets/Jd.png) | ![](assets/Jc.png) | ![](assets/Qh.png) | ![](assets/Qd.png) |

## Dealing

A standard deck of 52 playing cards is used, is dealt evenly between four players (13 cards each, hence the name of the game). When playing with 2 to 3 players, deal 13 cards to each player. The remaining cards will be unused.

# Cards

## Waypoint 1: Card Class

Write a [class](https://www.youtube.com/watch?v=apACNr7DC_s) `Card` that represents a single card from a 52-card [French playing cards](https://en.wikipedia.org/wiki/French_playing_cards) deck .

The constructor of this class takes 2 arguments `rank` and `suit` that respectively correspond to the rank and suit of this card.

Both the rank and suit of the card are given in compliance with the standard notation:

- `rank`: An ASCII character, either a digit (`2`-`9`) or an uppercase letter (`T`, `J`, `Q`, `K`, `A`).

- `suit`: An ASCII lowercase letter (`h` , `d` , `c` , `s`) or Unicode character (`♥` , `♦` , `♣` , `♠`).

For example:

```python
>>> Card('2', 'h')
<__main__.Card object at 0x10e3b0eb8>
>>> Card('K', '♦')
<__main__.Card object at 0x108d0fe48>
>>> Card('G', 'h')
Traceback (most recent call last):
  File "<input>", line 1, in <module>
  File "<input>", line 6, in __init__
ValueError: wrong rank "G"
>>> Card('2', 'x')
Traceback (most recent call last):
  File "<input>", line 1, in <module>
  File "<input>", line 11, in __init__
ValueError: wrong suit "x"
```

## Waypoint 2: Human-Readable String Representation of a Card

[Override](https://en.wikipedia.org/wiki/Method_overriding) the built-in function [`__str__`](https://docs.python.org/3/reference/datamodel.html#object.__str__) in your class `Card`. This function is used for returning a nice string representation of an object.

Your implementation of this [built-in function `__str__` ](https://www.youtube.com/watch?v=aIdzBGzaxUo) returns a string consisting of the rank and suit (ASCII letter) of the card concatenated together in that order.

For example:

```python
>>> card = Card('2', 'h')
>>> str(card)
'2h'
>>> print(card)
2h
```

## Waypoint 3: Official String Representation of a Card

Override the built-in function [`__repr__`](https://docs.python.org/3/reference/datamodel.html#object.__repr__) in your class `Card`. This function is used for returning the official string representation of an object.

The official Python documentation states that: "_If at all possible, this should look like a **valid Python expression** that could be used to recreate an object with the same value (given an appropriate environment)._"

Your implementation of this [built-in function `__repr__` ](https://www.youtube.com/watch?v=aIdzBGzaxUo) returns a string consisting of the name of the class `Card` followed with, in parentheses and quotes, the rank concatenated to the suit (ASCII letter) of the card.

```python
>>> card = Card('2', 'h')
>>> repr(card)
"Card('2h')"
>>> card
Card('2h')
```

## Waypoint 4: Constructor with Variadic Arguments

Change the [signature](https://en.wikipedia.org/wiki/Type_signature#Method_signature) of the constructor of your class `Card` to accept an argument `symbol` that corresponds to the symbol of the card (i.e., the rank and suit of the card concatenated together in that order). For example: `Kh`, `Ts`, etc.

The constructor of the class `Card` accepts a [varying number of arguments](https://realpython.com/python-kwargs-and-args/): either two arguments `rank` and `suit`, or a single argument `symbol`.

_Note: This constructor can actually be passed even more [arguments](https://docs.python.org/3/glossary.html#term-parameter): this constructor is said to be a [variadic function](https://en.wikipedia.org/wiki/Variadic_function). However, if more than two arguments are passed, the constructor will raise an exception `ValueError` to inform the caller that the list of arguments is invalid._

For example:

```python
>>> Card('2h')
<__main__.Card object at 0x10e3d1ba8>
>>> Card('Q♥')
<__main__.Card object at 0x108d27208>
>>> Card('2hx')
Traceback (most recent call last):
  File "<input>", line 1, in <module>
  File "<input>", line 6, in __init__
ValueError: wrong symbol "2hx"
>>> Card('Gh')
Traceback (most recent call last):
  File "<input>", line 1, in <module>
  File "<input>", line 22, in __init__
ValueError: wrong rank "G"
>>> Card('2x')
Traceback (most recent call last):
  File "<input>", line 1, in <module>
  File "<input>", line 27, in __init__
ValueError: wrong suit "x"
>>> Card('2', 'h')
<__main__.Card object at 0x10e3ba320>
>>> Card('2', 'h', '$')
Traceback (most recent call last):
  File "<input>", line 1, in <module>
  File "<input>", line 17, in __init__
ValueError: invalid arguments ('2', 'h', '$')
```

## Waypoint 5: Properties `Rank`, `Suit`, and `Symbol`

Write 3 **read-only [properties](https://docs.python.org/3/library/functions.html#property)** `rank`, `suit`, and `symbol` of the class `Card` that returns the string corresponding respectively to the rank, suit, and symbol of an object `Card`.

These [properties](https://www.datacamp.com/community/tutorials/property-getters-setters) hide details about how the rank and the suit of the object `Card` are stored in this object. These read-only [properties](https://www.python-course.eu/python3_properties.php) allows us to read some data of the object `Card`, but they prevent us from modifying them.

_Note: The [attributes](https://docs.python.org/3.8/tutorial/classes.html) of the class `Card` that are used to store the rank and suit of a card, whatever their number and type, **MUST** be [**private**](https://docs.python.org/3.8/tutorial/classes.html#private-variables)._

For example:

```python
>>> card = Card('2h')
>>> card.rank
'2'
>>> card.suit
'h'
>>> card.symbol
'2h'
>>> card.rank = 'K'
Traceback (most recent call last):
  File "<input>", line 1, in <module>
AttributeError: can't set attribute
```

## Waypoint 6: Cards Comparison

We would like to be able to compare two cards together. Comparison will allow us to sort cards by ascending or descending order. It will also allow us to check whether a card is more, higher or lower than the other one.

Right now, the comparison operators are not defined in our class `Card`:

```python
>>> card1 = Card('2h')
>>> card2 = Card('2s')
Traceback (most recent call last):
  File "<input>", line 1, in <module>
TypeError: '>' not supported between instances of 'Card' and 'Card'
```

Each card game has a specific order to rank individual cards from highest to lowest.

For example:

- [Belote](https://en.wikipedia.org/wiki/Belote): `J` `9` `A` `T` `K` `Q` `8` `7` (trump suit) or `A` `T` `K` `Q` `J` `9` `8` `7` (non-trump suit).
- [Poker](https://en.wikipedia.org/wiki/Poker): `A` `K` `Q` `J` `T` `9` `8` `7` `6` `5` `4` `3`.
- Tiến Lên: `A` `K` `Q` `J` `T` `9` `8` `7` `6` `5` `4` `3`.

Therfore, we **MUST NOT** implement comparison operators in the class `Card`, which is independent from any card games, but in a more specialized class.

Create a class `TienLenCard` that [inherits](https://www.digitalocean.com/community/tutorials/understanding-class-inheritance-in-python-3) from the [parent class](https://realpython.com/inheritance-composition-python/) `Card`.

```python
>>> card = TienLenCard('2h')
>>> isinstance(card, TienLenCard)
True
>>> isinstance(card, Card)  # `TienLenCard` inherits from `Card`
True
```

We don't need to redefine the built-in functions `__str__` and `__repr__` in our class `TienLenCard`. They are inherited from the parent class `Card`.

```python
>>> TienLenCard('2h')
TienLenCard('2h')
```

_Note: If the previous snippet returns `Card('2h')` instead of `TienLenCard('2h')`, it means that you have hard-coded some values in the built-in function `__repr__` that you have implemented in your class `Card`. That's bad! You **MUST** use the special attributes [`__class__`](https://docs.python.org/3/library/stdtypes.html#instance.__class__) and [`__name__`](https://docs.python.org/3/library/stdtypes.html#definition.__name__)._

Now, [override](https://en.wikipedia.org/wiki/Method_overriding) the _rich comparison_ built-in functions of your class `TienLenCard`:

- [`__eq__`](https://docs.python.org/3/reference/datamodel.html#object.__eq__): equal to.
- [`__ge__`](https://docs.python.org/3/reference/datamodel.html#object.__ge__): greater than or equal to.
- [`__gt__`](https://docs.python.org/3/reference/datamodel.html#object.__gt__): greater than.
- [`__le__`](https://docs.python.org/3/reference/datamodel.html#object.__le__): less than or equal to.
- [`__lt__`](https://docs.python.org/3/reference/datamodel.html#object.__lt__): less than.
- [`__ne__`](https://docs.python.org/3/reference/datamodel.html#object.__ne__): not equal to.

```python
>>> card1 = TienLenCard('2h')
>>> card2 = TienLenCard('2s')
>>> card1 == card2
False
>>> card1 >= card2
True
>>> card1 > card2
True
>>> card1 <= card2
False
>>> card1 < card2
False
>>> card1 != card2
True
```

Now we can now easily sort a list of cards. 

For example:

```python
>>> # Generate a deck of 52 cards
>>> cards = [
...    TienLenCard(rank, suit)
...    for rank in '23456789TJQKA'
...    for suit in 'hdcs']
>>> print([str(card) for card in cards])
['2h', '2d', '2c', '2s', '3h', '3d', '3c', '3s', '4h', '4d', '4c', '4s', '5h', '5d', '5c', '5s', '6h', '6d', '6c', '6s', '7h', '7d', '7c', '7s', '8h', '8d', '8c', '8s', '9h', '9d', '9c', '9s', 'Th', 'Td', 'Tc', 'Ts', 'Jh', 'Jd', 'Jc', 'Js', 'Qh', 'Qd', 'Qc', 'Qs', 'Kh', 'Kd', 'Kc', 'Ks', 'Ah', 'Ad', 'Ac', 'As']

>>> # Shuffle the cards
>>> import random
>>> random.shuffle(cards)
>>> print([str(card) for card in cards])
['Ks', '7c', 'Jc', 'Ts', '9c', '6h', '6d', 'Qh', 'Tc', '3d', '6s', 'Kc', 'Ac', '5d', '3h', '8h', '5c', '8s', '3c', '6c', '2d', '4c', '9s', '9h', 'Ah', '4h', '3s', '4d', '2s', '9d', '4s', 'Th', 'As', '8c', 'Kd', 'Kh', '8d', 'Td', 'Jh', '7d', '2c', 'Qs', 'Qd', '7h', 'Jd', 'Ad', '5s', 'Qc', '5h', '2h', 'Js', '7s']

>>> # Sort the cards
>>> deck.sort()
>>> print([str(card) for card in cards])
['3s', '3c', '3d', '3h', '4s', '4c', '4d', '4h', '5s', '5c', '5d', '5h', '6s', '6c', '6d', '6h', '7s', '7c', '7d', '7h', '8s', '8c', '8d', '8h', '9s', '9c', '9d', '9h', 'Ts', 'Tc', 'Td', 'Th', 'Js', 'Jc', 'Jd', 'Jh', 'Qs', 'Qc', 'Qd', 'Qh', 'Ks', 'Kc', 'Kd', 'Kh', 'As', 'Ac', 'Ad', 'Ah', '2s', '2c', '2d', '2h']
```

## Waypoint 7: Generate a 52-Card Deck of French Playing Cards

Write a [**class method**](https://realpython.com/instance-class-and-static-methods-demystified/) `generate_deck` of your class `Card` that takes one optional argument `shuffle` (a boolean) that indicates whether the cards need to be shuffled. This [class method](https://docs.python.org/3/library/functions.html?highlight=classmethod#classmethod) `generate_deck` returns a list of 52 French playing cards.

For example:

```python
>>> Card.generate_deck()
[Card('2h'), Card('2d'), Card('2c'), Card('2s'), Card('3h'), Card('3d'), Card('3c'), Card('3s'), Card('4h'), Card('4d'), Card('4c'), Card('4s'), Card('5h'), Card('5d'), Card('5c'), Card('5s'), Card('6h'), Card('6d'), Card('6c'), Card('6s'), Card('7h'), Card('7d'), Card('7c'), Card('7s'), Card('8h'), Card('8d'), Card('8c'), Card('8s'), Card('9h'), Card('9d'), Card('9c'), Card('9s'), Card('Th'), Card('Td'), Card('Tc'), Card('Ts'), Card('Jh'), Card('Jd'), Card('Jc'), Card('Js'), Card('Qh'), Card('Qd'), Card('Qc'), Card('Qs'), Card('Kh'), Card('Kd'), Card('Kc'), Card('Ks'), Card('Ah'), Card('Ad'), Card('Ac'), Card('As')]
>>> TienLenCard.generate_deck()  # Method inherited from `Card`
[TienLenCard('2h'), TienLenCard('2d'), TienLenCard('2c'), TienLenCard('2s'), TienLenCard('3h'), TienLenCard('3d'), TienLenCard('3c'), TienLenCard('3s'), TienLenCard('4h'), TienLenCard('4d'), TienLenCard('4c'), TienLenCard('4s'), TienLenCard('5h'), TienLenCard('5d'), TienLenCard('5c'), TienLenCard('5s'), TienLenCard('6h'), TienLenCard('6d'), TienLenCard('6c'), TienLenCard('6s'), TienLenCard('7h'), TienLenCard('7d'), TienLenCard('7c'), TienLenCard('7s'), TienLenCard('8h'), TienLenCard('8d'), TienLenCard('8c'), TienLenCard('8s'), TienLenCard('9h'), TienLenCard('9d'), TienLenCard('9c'), TienLenCard('9s'), TienLenCard('Th'), TienLenCard('Td'), TienLenCard('Tc'), TienLenCard('Ts'), TienLenCard('Jh'), TienLenCard('Jd'), TienLenCard('Jc'), TienLenCard('Js'), TienLenCard('Qh'), TienLenCard('Qd'), TienLenCard('Qc'), TienLenCard('Qs'), TienLenCard('Kh'), TienLenCard('Kd'), TienLenCard('Kc'), TienLenCard('Ks'), TienLenCard('Ah'), TienLenCard('Ad'), TienLenCard('Ac'), TienLenCard('As')]
>>> TienLenCard.generate_deck(shuffle=True)
[TienLenCard('3d'), TienLenCard('7d'), TienLenCard('Jh'), TienLenCard('7c'), TienLenCard('Kd'), TienLenCard('3h'), TienLenCard('6d'), TienLenCard('5h'), TienLenCard('Ac'), TienLenCard('Ah'), TienLenCard('Qd'), TienLenCard('5c'), TienLenCard('Jc'), TienLenCard('9s'), TienLenCard('9h'), TienLenCard('6s'), TienLenCard('9d'), TienLenCard('Th'), TienLenCard('As'), TienLenCard('4h'), TienLenCard('8c'), TienLenCard('4d'), TienLenCard('6h'), TienLenCard('Tc'), TienLenCard('Kc'), TienLenCard('Jd'), TienLenCard('7h'), TienLenCard('Ad'), TienLenCard('Js'), TienLenCard('2d'), TienLenCard('8s'), TienLenCard('8d'), TienLenCard('Kh'), TienLenCard('Qc'), TienLenCard('5s'), TienLenCard('6c'), TienLenCard('3s'), TienLenCard('8h'), TienLenCard('5d'), TienLenCard('4s'), TienLenCard('4c'), TienLenCard('3c'), TienLenCard('Qh'), TienLenCard('2s'), TienLenCard('Ks'), TienLenCard('2h'), TienLenCard('2c'), TienLenCard('9c'), TienLenCard('Ts'), TienLenCard('Td'), TienLenCard('7s'), TienLenCard('Qs')]
```

## Waypoint 8: Sort Cards

Write a [**static method**](https://docs.python.org/3/library/functions.html?highlight=classmethod#staticmethod) or a [**class method**](https://julien.danjou.info/guide-python-static-class-abstract-methods/) `sort_cards` in your class `TienLenCard`, that takes an argument `cards` (a list of `TienLenCard` objects) and an optional argument `reverse` (a boolean in which the default value is `False`).

_Note: You will need to justify your choice between a **static method** or a **class method**._

The function returns the list of cards sorted in ascending order if the argument `reverse` is `False`, or in descending order if the argument `reverse` is `True`.

For example:

```python
>>> cards = TienLenCard.generate_deck(shuffle=True)
>>> TienLenCard.sort_cards(cards)
[TienLenCard('3s'), TienLenCard('3c'), TienLenCard('3d'), TienLenCard('3h'), TienLenCard('4s'), TienLenCard('4c'), TienLenCard('4d'), TienLenCard('4h'), TienLenCard('5s'), TienLenCard('5c'), TienLenCard('5d'), TienLenCard('5h'), TienLenCard('6s'), TienLenCard('6c'), TienLenCard('6d'), TienLenCard('6h'), TienLenCard('7s'), TienLenCard('7c'), TienLenCard('7d'), TienLenCard('7h'), TienLenCard('8s'), TienLenCard('8c'), TienLenCard('8d'), TienLenCard('8h'), TienLenCard('9s'), TienLenCard('9c'), TienLenCard('9d'), TienLenCard('9h'), TienLenCard('Ts'), TienLenCard('Tc'), TienLenCard('Td'), TienLenCard('Th'), TienLenCard('Js'), TienLenCard('Jc'), TienLenCard('Jd'), TienLenCard('Jh'), TienLenCard('Qs'), TienLenCard('Qc'), TienLenCard('Qd'), TienLenCard('Qh'), TienLenCard('Ks'), TienLenCard('Kc'), TienLenCard('Kd'), TienLenCard('Kh'), TienLenCard('As'), TienLenCard('Ac'), TienLenCard('Ad'), TienLenCard('Ah'), TienLenCard('2s'), TienLenCard('2c'), TienLenCard('2d'), TienLenCard('2h')]
>>> TienLenCard.sort_cards(cards, reverse=True)
[TienLenCard('2h'), TienLenCard('2d'), TienLenCard('2c'), TienLenCard('2s'), TienLenCard('Ah'), TienLenCard('Ad'), TienLenCard('Ac'), TienLenCard('As'), TienLenCard('Kh'), TienLenCard('Kd'), TienLenCard('Kc'), TienLenCard('Ks'), TienLenCard('Qh'), TienLenCard('Qd'), TienLenCard('Qc'), TienLenCard('Qs'), TienLenCard('Jh'), TienLenCard('Jd'), TienLenCard('Jc'), TienLenCard('Js'), TienLenCard('Th'), TienLenCard('Td'), TienLenCard('Tc'), TienLenCard('Ts'), TienLenCard('9h'), TienLenCard('9d'), TienLenCard('9c'), TienLenCard('9s'), TienLenCard('8h'), TienLenCard('8d'), TienLenCard('8c'), TienLenCard('8s'), TienLenCard('7h'), TienLenCard('7d'), TienLenCard('7c'), TienLenCard('7s'), TienLenCard('6h'), TienLenCard('6d'), TienLenCard('6c'), TienLenCard('6s'), TienLenCard('5h'), TienLenCard('5d'), TienLenCard('5c'), TienLenCard('5s'), TienLenCard('4h'), TienLenCard('4d'), TienLenCard('4c'), TienLenCard('4s'), TienLenCard('3h'), TienLenCard('3d'), TienLenCard('3c'), TienLenCard('3s')]
```

## Waypoint 9: Card Combinations

A legal play corresponds to a valid combination of cards, i.e., a set of cards played by each player in turn, during the play of a hand, also known as a [**trick**](https://en.wikipedia.org/wiki/Glossary_of_card_game_terms).

We have already described the list of Tiến Lên tricks:

|                     |                                         |                    |                    |                    |                    |                    |                    |
| ------------------- | --------------------------------------- | ------------------ | ------------------ | ------------------ | ------------------ | ------------------ | ------------------ |
| **Single**          | A single card                           | ![](assets/3s.png) |                    |                    |                    |                    |                    |
| **Pair**            | Two cards of the same rank              | ![](assets/Qd.png) | ![](assets/Qs.png) |                    |                    |                    |                    |
| **Triple**          | Three cards of the same rank            | ![](assets/5d.png) | ![](assets/5h.png) | ![](assets/5c.png) |                    |                    |                    |  |
| **Four of a kind**  | Four cards of the same rank             | ![](assets/9h.png) | ![](assets/9d.png) | ![](assets/9c.png) | ![](assets/9s.png) |                    |                    |
| **Sequence**        | Three or more cards of consecutive rank | ![](assets/4d.png) | ![](assets/5s.png) | ![](assets/6h.png) |                    |                    |                    |
| **Double Sequence** | Three or more pairs of consecutive rank | ![](assets/Th.png) | ![](assets/Ts.png) | ![](assets/Jd.png) | ![](assets/Jc.png) | ![](assets/Qh.png) | ![](assets/Qd.png) |

Write a class `TienLenTrick` in which the constructor accepts two arguments:

- `trick_type`: The type of trick.
- `cards`: A list of cards, in any order, that correspond to this trick.

Create a class attribute `TrickType` that corresponds to an [**enumeration**](https://docs.python.org/3/library/enum.html), i.e., a set of symbolic names bound to [unique constant values](https://docs.python.org/3/library/enum.html#functional-api).

For example:

```python
>>> TienLenTrick.TrickType
<enum 'TrickType'>
>>> list(TienLenTrick.TrickType)
[<TrickType.single: 1>, <TrickType.pair: 2>, <TrickType.triple: 3>, <TrickType.four_of_a_kind: 4>, <TrickType.sequence: 5>, <TrickType.double_sequence: 6>]
```

The argument `trick_type` passed to the constructor of the class `TienLenTrick` must correspond to an element of the enumeration `TrickType`.

For example:

```python
>>> trick = TienLenTrick(
...     TienLenTrick.TrickType.triple,
...     [TienLenCard('5d'), TienLenCard('5h'), TienLenCard('5c')])

>>> trick = TienLenTrick(
...     'sequence',
...     [TienLenCard('4d'), TienLenCard('5s'), TienLenCard('6h')])
Traceback (most recent call last):
  File "<input>", line 1, in <module>
  File "<input>", line 198, in __init__
ValueError: invalid argument trick_type

>>> trick = TienLenTrick(
...     TienLenTrick.TrickType.sequence,
...     [Card('4d'), Card('5s'), Card('6h')])
Traceback (most recent call last):
  File "<input>", line 1, in <module>
  File "<input>", line 204, in __init__
ValueError: The list cards must contain TienLenCard objects only

>>>> trick = TienLenTrick(TienLenTrick.TrickType.sequence, [])
Traceback (most recent call last):
  File "<input>", line 1, in <module>
  File "<input>", line 201, in __init__
ValueError: invalid argument cards
```

_Note: You also need to override the built-in functions **`__str__`** and **`__repr__`** of your class `TienLenTrick`._

![](face_of_a_surprised_dog.jpg)

What the heck?! The constructor of the class `TienLenTrick` could accept arguments such as:

|                    |                    |                    |                    |
| ------------------ | ------------------ | ------------------ | ------------------ |
| ![](assets/4c.png) | ![](assets/6h.png) | ![](assets/Js.png) | ![](assets/Qd.png) |

```python
>>> trick = TienLenTrick(
...     TienLenTrick.TrickType.triple,
...     [TienLenCard('4c'), TienLenCard('6h'), TienLenCard('Jc')])
```

This combination of cards is not a **triple**! This isn't even a valid Tiến Lên trick! What a strange way to design the interface of this constructor, isn't it?!

Don't worry, we are going to protect the access to this constructor later. Just follow the [White Rabbit](https://en.wikipedia.org/wiki/White_Rabbit).

![](white_rabbit.jpg)

## Waypoint 10: Validate Card Combinations

Now we need to check whether a set of cards correspond to a valid Tiến Lên trick.

Write the following **static methods** or **class methods** in the class `TienLenTrick`:

- `is_single`: A single card.
- `is_pair`: Two cards of the same rank.
- `is_triple`: Three cards of the same rank.
- `is_four_of_a_kind`: Four cards of the same rank.
- `is_sequence`: Three or more cards of consecutive rank.
- `is_double_sequence`: Three or more pairs of consecutive rank.

_Note: You will need to justify your choice between **static methods** or **class methods**._

Each of these methods takes an argument `cards` (a list of objects `TienLenCard`) and returns `True` if this list of cards corresponds to the type of combination that this function checks, otherwise it returns `False`.

For example:

```python
>>> TienLenTrick.is_single([TienLenCard('3s')])
True
>>> TienLenTrick.is_pair([TienLenCard('Qd'), TienLenCard('Qs')])
True
>>> TienLenTrick.is_triple([TienLenCard('5d'), TienLenCard('5h'), TienLenCard('5c')])
True
>>> TienLenTrick.is_four_of_a_kind([TienLenCard('9h'), TienLenCard('9d'), TienLenCard('9c'), TienLenCard('9s')])
True
>>> TienLenTrick.is_sequence([TienLenCard('4d'), TienLenCard('5s'), TienLenCard('6h')])
True
>>> TienLenTrick.is_double_sequence([TienLenCard('Th'), TienLenCard('Ts'), TienLenCard('Jd'), TienLenCard('Jc'), TienLenCard('Qh'), TienLenCard('Qd')])
True
>>> TienLenTrick.is_triple([TienLenCard('Ks'), TienLenCard('7c'), TienLenCard('Jc')])
False
>>> TienLenTrick.is_sequence([TienLenCard('9h'), TienLenCard('9d'), TienLenCard('9c'), TienLenCard('9s')])
False
```

**WARNING!** The list of cards can be given in **any order**. 

For example:

```python
>>> TienLenTrick.is_sequence([TienLenCard('Qd'), TienLenCard('Js'), TienLenCard('Kh')])
True
>>> TienLenTrick.is_double_sequence([TienLenCard('4h'), TienLenCard('5s'), TienLenCard('3d'), TienLenCard('4c'), TienLenCard('5h'), TienLenCard('3c')])
True
```

## Waypoint 11: Find Singles

Write a class method `find_singles` of the class `TienLenTrick` that takes an argument `cards` (a list of objects `TienLenCard`) and that returns a list of all the **single** cards (list of objects `TienLenTrick`). Yep, quite trivial...

For example:

```python
>>> cards = [TienLenCard('4h'), TienLenCard('8h'), TienLenCard('7d'), TienLenCard('Qc')]
>>> tricks = TienLenTrick.find_singles(cards)
>>> import pprint
>>> pprint.pprint(tricks)
[TienLenTrick(TienLenTrickType.single, [TienLenCard('4h')]),
 TienLenTrick(TienLenTrickType.single, [TienLenCard('8h')]),
 TienLenTrick(TienLenTrickType.single, [TienLenCard('7d')]),
 TienLenTrick(TienLenTrickType.single, [TienLenCard('Qc')])]
```

## Waypoint 12: Find Pairs

Write a class method `find_pairs` of the class `TienLenTrick` that takes an argument `cards` (a list of objects `TienLenCard`) and that returns a list of all the **pairs** (list of objects `TienLenTrick`) that can be formed with these cards.

For example:

```python
>>> cards = [TienLenCard('9h'), TienLenCard('Jc'), TienLenCard('9c'), TienLenCard('4h'), TienLenCard('8h'), TienLenCard('7d'), TienLenCard('Qc'), TienLenCard('As'), TienLenCard('7h'), TienLenCard('Qd'), TienLenCard('Jh'), TienLenCard('9d'), TienLenCard('8c')]
>>> tricks = TienLenTrick.find_pairs(cards)
>>> import pprint
>>> pprint.pprint(tricks)
[TienLenTrick(TienLenTrickType.pair, [TienLenCard('9c'), TienLenCard('9h')]),
 TienLenTrick(TienLenTrickType.pair, [TienLenCard('9d'), TienLenCard('9h')]),
 TienLenTrick(TienLenTrickType.pair, [TienLenCard('9c'), TienLenCard('9d')]),
 TienLenTrick(TienLenTrickType.pair, [TienLenCard('Jc'), TienLenCard('Jh')]),
 TienLenTrick(TienLenTrickType.pair, [TienLenCard('8c'), TienLenCard('8h')]),
 TienLenTrick(TienLenTrickType.pair, [TienLenCard('7d'), TienLenCard('7h')]),
 TienLenTrick(TienLenTrickType.pair, [TienLenCard('Qc'), TienLenCard('Qd')])]
```

This example can be visually represented with the following cards in the hand of the player:

| `4h`               | `7d`               | `7h`               | `8c`               | `8h`               | `9c`               | `9d`               | `9h`               | `Jc`               | `Jh`               | `Qc`               | `Qd`               | `As`               |
| ------------------ | ------------------ | ------------------ | ------------------ | ------------------ | ------------------ | ------------------ | ------------------ | ------------------ | ------------------ | ------------------ | ------------------ | ------------------ |
| ![](assets/4h.png) | ![](assets/7d.png) | ![](assets/7h.png) | ![](assets/8c.png) | ![](assets/8h.png) | ![](assets/9c.png) | ![](assets/9d.png) | ![](assets/9h.png) | ![](assets/Jc.png) | ![](assets/Jh.png) | ![](assets/Qc.png) | ![](assets/Qd.png) | ![](assets/As.png) |

The **pairs** the player can form with the cards in their hand are (from left to right):

| 1st Pair                              | 2nd Pair                              | 3rd Pair                              | 4th Pair                              | 5th Pair                              | 6th Pair                              | 7th Pair                              |
| ------------------------------------- | ------------------------------------- | ------------------------------------- | ------------------------------------- | ------------------------------------- | ------------------------------------- | ------------------------------------- |
| ![](assets/7d.png) ![](assets/7h.png) | ![](assets/8c.png) ![](assets/8h.png) | ![](assets/9c.png) ![](assets/9d.png) | ![](assets/9c.png) ![](assets/9h.png) | ![](assets/9d.png) ![](assets/9h.png) | ![](assets/Jc.png) ![](assets/Jh.png) | ![](assets/Qc.png) ![](assets/Qd.png) |

## Waypoint 13: Find Triples

Write a class method `find_triples` of the class `TienLenTrick` that takes an argument `cards` (a list of objects `Card`) and that returns a list of all the **triples** (list of objects `TienLenTrick`) that can be formed with these cards.

For example:

```python
>>> cards = [TienLenCard('3s'), TienLenCard('3c'), TienLenCard('3d'), TienLenCard('3h'), TienLenCard('4h'), TienLenCard('6c'), TienLenCard('7d'), TienLenCard('9h'), TienLenCard('Th'), TienLenCard('Qd'), TienLenCard('Kh'), TienLenCard('As'), TienLenCard('Ad')]
>>> tricks = TienLenTrick.find_triples(cards)
>>> pprint.pprint(tricks)
[TienLenTrick(TienLenTrickType.triple, [TienLenCard('3s'), TienLenCard('3c'), TienLenCard('3d')]),
 TienLenTrick(TienLenTrickType.triple, [TienLenCard('3s'), TienLenCard('3c'), TienLenCard('3h')]),
 TienLenTrick(TienLenTrickType.triple, [TienLenCard('3s'), TienLenCard('3d'), TienLenCard('3h')]),
 TienLenTrick(TienLenTrickType.triple, [TienLenCard('3c'), TienLenCard('3d'), TienLenCard('3h')])]
```

This example can be visually represented with the following cards in the hand of the player:

| `3s`               | `3c`               | `3d`               | `3h`               | `4h`               | `6c`               | `7d`               | `9h`               | `Th`               | `Qd`               | `Kh`               | `As`               | `Ad`               |
| ------------------ | ------------------ | ------------------ | ------------------ | ------------------ | ------------------ | ------------------ | ------------------ | ------------------ | ------------------ | ------------------ | ------------------ | ------------------ |
| ![](assets/3s.png) | ![](assets/3c.png) | ![](assets/3d.png) | ![](assets/3h.png) | ![](assets/4h.png) | ![](assets/6c.png) | ![](assets/7d.png) | ![](assets/9h.png) | ![](assets/Th.png) | ![](assets/Qd.png) | ![](assets/Kh.png) | ![](assets/As.png) | ![](assets/Ad.png) |

The **triples** the player can form with the cards in their hand are (from left to right):

| 1st Triple         | 2nd Triple         | 3rd Triple         | 4th Triple         |
| ------------------ | ------------------ | ------------------ | ------------------ |
| ![](assets/3s.png) | ![](assets/3s.png) | ![](assets/3s.png) | ![](assets/3c.png) |
| ![](assets/3c.png) | ![](assets/3c.png) | ![](assets/3d.png) | ![](assets/3d.png) |
| ![](assets/3d.png) | ![](assets/3h.png) | ![](assets/3h.png) | ![](assets/3h.png) |

## Waypoint 14: Find Fours of a Kind

Write a class method `find_fours_of_a_kind` of the class `TienLenTrick` that takes an argument `cards` (a list of objects `TienLenCard`) and that returns a list of all the **fours of a kind** (list of objects `TienLenTrick`) that can be formed with these cards.

For example:

```python
>>> cards = [TienLenCard('Qc'), TienLenCard('6d'), TienLenCard('Ad'), TienLenCard('6h'), TienLenCard('Jd'), TienLenCard('6s'), TienLenCard('Ah'), TienLenCard('As'), TienLenCard('6c'), TienLenCard('5d'), TienLenCard('2c'), TienLenCard('3c'), TienLenCard('Kc')]
>>> tricks = TienLenTrick.find_fours_of_a_kind(cards)
>>> pprint.pprint(tricks)
[TienLenTrick(TienLenTrickType.four_of_a_kind, [TienLenCard('6s') TienLenCard('6c') TienLenCard('6d') TienLenCard('6h')])]
```

This example can be visually represented with the following cards in the hand of the player:

| `3c`               | `5d`               | `6s`               | `6c`               | `6d`               | `6h`               | `Jd`               | `Qc`               | `Kc`               | `As`               | `Ad`               | `Ah`               | `2c`               |
| ------------------ | ------------------ | ------------------ | ------------------ | ------------------ | ------------------ | ------------------ | ------------------ | ------------------ | ------------------ | ------------------ | ------------------ | ------------------ |
| ![](assets/3c.png) | ![](assets/5d.png) | ![](assets/6s.png) | ![](assets/6c.png) | ![](assets/6d.png) | ![](assets/6h.png) | ![](assets/Jd.png) | ![](assets/Qc.png) | ![](assets/Kc.png) | ![](assets/As.png) | ![](assets/Ad.png) | ![](assets/Ah.png) | ![](assets/2c.png) |

The single **four of a kind** the player can form with the cards in their hand is:

| `6s`               | `6c`               | `6d`               | `6h`               |
| ------------------ | ------------------ | ------------------ | ------------------ |
| ![](assets/6s.png) | ![](assets/6c.png) | ![](assets/6d.png) | ![](assets/6h.png) |

## Waypoint 15: Find Sequences

Write a class method `find_sequences` of the class `TienLenTrick` that takes an argument `cards` (a list of objects `TienLenCard`) and that returns a list of all the **sequences** (list of objects `TienLenTrick`) that can be formed with these cards.

For example:

```python
>>> cards = [TienLenCard('4s'), TienLenCard('4h'), TienLenCard('5c'), TienLenCard('6s'), TienLenCard('7c'), TienLenCard('7d'), TienLenCard('Tc'), TienLenCard('Td'), TienLenCard('Jd'), TienLenCard('Qc'), TienLenCard('Qd'), TienLenCard('As'), TienLenCard('2d')]
>>> tricks = TienLenTrick.find_sequences(cards)
>>> pprint.pprint(tricks)
[TienLenTrick(TienLenTrickType.sequence, [TienLenCard('4s'), TienLenCard('5c'), TienLenCard('6s')]),
 TienLenTrick(TienLenTrickType.sequence, [TienLenCard('4h'), TienLenCard('5c'), TienLenCard('6s')]),
 TienLenTrick(TienLenTrickType.sequence, [TienLenCard('5c'), TienLenCard('6s'), TienLenCard('7c')]),
 TienLenTrick(TienLenTrickType.sequence, [TienLenCard('5c'), TienLenCard('6s'), TienLenCard('7d')]),
 TienLenTrick(TienLenTrickType.sequence, [TienLenCard('4s'), TienLenCard('5c'), TienLenCard('6s'), TienLenCard('7c')]),
 TienLenTrick(TienLenTrickType.sequence, [TienLenCard('4s'), TienLenCard('5c'), TienLenCard('6s'), TienLenCard('7d')]),
 TienLenTrick(TienLenTrickType.sequence, [TienLenCard('4h'), TienLenCard('5c'), TienLenCard('6s'), TienLenCard('7c')]),
 TienLenTrick(TienLenTrickType.sequence, [TienLenCard('4h'), TienLenCard('5c'), TienLenCard('6s'), TienLenCard('7d')]),
 TienLenTrick(TienLenTrickType.sequence, [TienLenCard('Tc'), TienLenCard('Jd'), TienLenCard('Qc')]),
 TienLenTrick(TienLenTrickType.sequence, [TienLenCard('Tc'), TienLenCard('Jd'), TienLenCard('Qd')]),
 TienLenTrick(TienLenTrickType.sequence, [TienLenCard('Td'), TienLenCard('Jd'), TienLenCard('Qc')]),
 TienLenTrick(TienLenTrickType.sequence, [TienLenCard('Td'), TienLenCard('Jd'), TienLenCard('Qd')])]
```

This example can be visually represented with the following cards in the hand of the player:

| `4s`               | `4h`               | `5c`               | `6s`               | `7c`               | `7d`               | `Tc`               | `Td`               | `Jd`               | `Qc`               | `Qd`               | `As`               | `2d`               |
| ------------------ | ------------------ | ------------------ | ------------------ | ------------------ | ------------------ | ------------------ | ------------------ | ------------------ | ------------------ | ------------------ | ------------------ | ------------------ |
| ![](assets/4s.png) | ![](assets/4h.png) | ![](assets/5c.png) | ![](assets/6s.png) | ![](assets/7c.png) | ![](assets/7d.png) | ![](assets/Tc.png) | ![](assets/Td.png) | ![](assets/Jd.png) | ![](assets/Qc.png) | ![](assets/Qd.png) | ![](assets/As.png) | ![](assets/2d.png) |

The **sequences** the player can form with the cards in their hand are (from left to right):

| 1st                | 2nd                | 3rd                | 4th                | 5th                | 6th                | 7th                | 8th                | 9th                | 10th               | 11th               | 12th               |
| ------------------ | ------------------ | ------------------ | ------------------ | ------------------ | ------------------ | ------------------ | ------------------ | ------------------ | ------------------ | ------------------ | ------------------ |
| ![](assets/4s.png) | ![](assets/4h.png) | ![](assets/5c.png) | ![](assets/5c.png) | ![](assets/4s.png) | ![](assets/4s.png) | ![](assets/4h.png) | ![](assets/4h.png) | ![](assets/Tc.png) | ![](assets/Tc.png) | ![](assets/Td.png) | ![](assets/Td.png) |
| ![](assets/5c.png) | ![](assets/5c.png) | ![](assets/6s.png) | ![](assets/6s.png) | ![](assets/5c.png) | ![](assets/5c.png) | ![](assets/5c.png) | ![](assets/5c.png) | ![](assets/Jd.png) | ![](assets/Jd.png) | ![](assets/Jd.png) | ![](assets/Jd.png) |
| ![](assets/6s.png) | ![](assets/6s.png) | ![](assets/7c.png) | ![](assets/7d.png) | ![](assets/6s.png) | ![](assets/6s.png) | ![](assets/6s.png) | ![](assets/6s.png) | ![](assets/Qc.png) | ![](assets/Qd.png) | ![](assets/Qc.png) | ![](assets/Qd.png) |
|                    |                    |                    |                    | ![](assets/7c.png) | ![](assets/7d.png) | ![](assets/7c.png) | ![](assets/7d.png) |                    |                    |                    |                    |

_Note: The list of cards for each sequence (column) are sorted by ascending order (and displayed in successive rows)._

Sounds complicated, huh? Below we will provide a few steps you can follow to complete this waypoint.

### Find Sequences of Ranks

We note `Rank #`, the position (starting from `0`) of a rank in the list of ranks sorted by ascending order:

| Rank # | 0   | 1   | 2   | 3   | 4   | 5   | 6   | 7   | 8    | 9     | 10   | 11  | 12  |
| ------ | --- | --- | --- | --- | --- | --- | --- | --- | ---- | ----- | ---- | --- | --- |
| Name   | 3   | 4   | 5   | 6   | 7   | 8   | 9   | 10  | Jack | Queen | King | Ace | 2   |
| Code   | `3` | `4` | `5` | `6` | `7` | `8` | `9` | `T` | `J`  | `Q`   | `K`  | `A` | `2` |

You might want to write a private static method `__build_rank_sequences_indices` of the class `TienLenTrick` that takes an argument `rank_indices` (a list of integers) and that returns a list of tuples of integers `(i, j)` where:

- `i`: index of the first rank of a sequence of consecutive ranks.
- `j`: index of the last rank in this sequence of consecutive ranks.

For example, we said that the hand of the player was:

| `4s`               | `4h`               | `5c`               | `6s`               | `7c`               | `7d`               | `Tc`               | `Td`               | `Jd`               | `Qc`               | `Qd`               | `As`               | `2d`               |
| ------------------ | ------------------ | ------------------ | ------------------ | ------------------ | ------------------ | ------------------ | ------------------ | ------------------ | ------------------ | ------------------ | ------------------ | ------------------ |
| ![](assets/4s.png) | ![](assets/4h.png) | ![](assets/5c.png) | ![](assets/6s.png) | ![](assets/7c.png) | ![](assets/7d.png) | ![](assets/Tc.png) | ![](assets/Td.png) | ![](assets/Jd.png) | ![](assets/Qc.png) | ![](assets/Qd.png) | ![](assets/As.png) | ![](assets/2d.png) |

So the list of **distinct** `Rank #` (sorted by ascending order) in the player's hand is:

|        | 0   | 1   | 2   | 3   | 4   | 5   | 6   | 7   | 8   |
| ------ | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Rank   | `4` | `5` | `6` | `7` | `T` | `J` | `Q` | `A` | `2` |
| Rank # | 1   | 2   | 3   | 4   | 7   | 8   | 9   | 11  | 12  |

There are 2 sequences of consecutive ranks in the player's hand:

|        | 0     | 1   | 2   | 3    | 4     | 5   | 6    | 7   | 8   |
| ------ | ----- | --- | --- | ---- | ----- | --- | ---- | --- | --- |
| Rank   | `4`   | `5` | `6` | `7`  | `T`   | `J` | `Q`  | .   | .   |
| Rank # | 1     | 2   | 3   | 4    | 7     | 8   | 9    | .   | .   |
|        | (`i`, |     |     | `j`) | (`i`, |     | `j`) | .   | .   |

_Note: We ignore any other ranks that are not part of a sequence ("`.`")._

`i` refers to the **index** of the first rank of a sequence, and `j` refers to the **index** of the last rank of this sequence:

- 1st sequence `[4, 5, 6, 7]` => `i = 0` and `j = 3`.
- 2nd sequence `[T, J, Q]` => `i = 4` and `j = 6`.

```python
# List of cards in the player's hands
>>> cards = [TienLenCard('4s'), TienLenCard('4h'), TienLenCard('5c'), TienLenCard('6s'), TienLenCard('7c'), TienLenCard('7d'), TienLenCard('Tc'), TienLenCard('Td'), TienLenCard('Jd'), TienLenCard('Qc'), TienLenCard('Qd'), TienLenCard('As'), TienLenCard('2d')]

# Find the list of distinct ranks in the player's hands
>>> ranks = ['4', '5', '6', '7', 'T', 'J', 'Q', 'A', '2']

# Find the list of the positions of these ranks
>>> rank_positions = [1, 2, 3, 4, 7, 8, 9, 11, 12]

# Return the list indices `(i, j)` of sequence of ranks
# (Hey! this is a private function: you need to call it from your
# function `find_sequences`)
>>> TienLenTrick.__build_rank_sequences_indices(rank_positions)
[(0, 3), (4, 6)]
```

### Find Variable Length of Sequences of Ranks

You might want to write a private static method `__build_variable_length_sequence_ranks` of the class `TienLenTrick` that takes an argument `rank_positions` (a list of integers) and that returns all the possible combinations of consecutive ranks (**positions**), which varies in length from `3` consecutive ranks to the maximum number of consecutive ranks.

For example, we take the **first** sequence of ranks from the player's hand:

|        | 0     | 1   | 2   | 3    | 4   | 5   | 6   | 7   | 8   |
| ------ | ----- | --- | --- | ---- | --- | --- | --- | --- | --- |
| Rank   | `4`   | `5` | `6` | `7`  | .   | .   | .   | .   | .   |
| Rank # | 1     | 2   | 3   | 4    | .   | .   | .   | .   | .   |
|        | (`i`, |     |     | `j`) | .   | .   | .   | .   |     |

We can form **3** sequences of consecutive ranks:

1. Sequence of **3** consecutive ranks `4`, `5`, `6` (i.e., rank positions `1`, `2`, `3`)
1. Sequence of **3** consecutive ranks `5`, `6`, `7` (i.e., rank positions `2`, `3`, `4`)
1. Sequence of **4** consecutive ranks `4`, `5`, `6`, `7` (i.e., rank positions `1`, `2`, `3`, `4`)

```python
# List of cards in the player's hand
>>> cards = [TienLenCard('4s'), TienLenCard('4h'), TienLenCard('5c'), TienLenCard('6s'), TienLenCard('7c'), TienLenCard('7d'), TienLenCard('Tc'), TienLenCard('Td'), TienLenCard('Jd'), TienLenCard('Qc'), TienLenCard('Qd'), TienLenCard('As'), TienLenCard('2d')]

# Find the list of distinct ranks in the player's hand
>>> ranks = ['4', '5', '6', '7', 'T', 'J', 'Q', 'A', '2']

# Find the list of the positions of these ranks
>>> rank_positions = [1, 2, 3, 4, 7, 8, 9, 11, 12]

# Find the 1st and the last rank positions of the first sequence of
# consecutive ranks
>>> i = 0
>>> j = 3

# Take the list of rank positions of this first sequence:
>>> sequence_rank_positions = rank_positions[i:j + 1]
>>> print(sequence_rank_positions)
[1, 2, 3, 4]

# We build all the combinations of consecutive ranks
# (Hey! this is a private function: you need to call it from your
# function `find_sequences`)
>>> TienLenTrick.__build_variable_length_sequence_ranks(sequence_rank_positions)
[[1, 2, 3], [2, 3, 4], [1, 2, 3, 4]]
```

We now take the **second** sequence of ranks from the player's hand:

|        | 0   | 1   | 2   | 3   | 4     | 5   | 6    | 7   | 8   |
| ------ | --- | --- | --- | --- | ----- | --- | ---- | --- | --- |
| Rank   | .   | .   | .   | .   | `T`   | `J` | `Q`  | .   | .   |
| Rank # | .   | .   | .   | .   | 7     | 8   | 9    | .   | .   |
|        | .   | .   | .   | .   | (`i`, |     | `j`) | .   | .   |

We can only form **1** sequence of consecutive ranks:

1. Sequence of **3** consecutive ranks `T`, `J`, `Q` (i.e., rank positions `7`, `8`, `9`)

```python
# Find the 1st and the last rank positions of the second sequence of
# consecutive ranks
>>> i = 4
>>> j = 6

# Take the list of rank positions of this first sequence:
>>> sequence_rank_positions = rank_positions[i:j + 1]
>>> print(sequence_rank_positions)
[7, 8, 9]

# We build all the combinations of consecutive ranks
# (Hey! this is a private function: you need to call it from your
# function `find_sequences`)
>>> TienLenTrick.__build_variable_length_sequence_ranks(sequence_rank_positions)
[[7, 8, 9]]
```

### Find Combinations of Sequences of Ranks

You might want to write a private static method `__build_sequence_combinations` of the class `TienLenTrick` that takes an argument `cards` (a list of groups of objects `TienLenCard`).

For example:

```python
[[TienLenCard('4s'), TienLenCard('4h')], [TienLenCard('5c')], [TienLenCard('6s')]]
```

Each group of objects `TienLenCard` corresponds to a list of cards of the same rank, as in our example:

```python
[TienLenCard('4s'), TienLenCard('4h')]
```

The groups correspond to consecutive ranks sorted by ascending order, as in our example the ranks `4`, `5`, `6`.

The function `__build_sequence_combinations` returns a list of all the combinations of cards (a list of cards in which their length corresponds to the number of groups) that form a sequence.

```python
>>> cards = [[TienLenCard('4s'), TienLenCard('4h')], [TienLenCard('5c')], [TienLenCard('6s')]]
>>> __build_sequence_combinations(cards)
[[TienLenCard('4s'), TienLenCard('5c'), TienLenCard('6s'), [TienLenCard('4h'), TienLenCard('5c'), TienLenCard('6s')]
```

We can visually represent this example as follows. Below is a list of cards that is passed to the function `__build_sequence_combinations`:

| Group 1            | Group 2            | Group 3            |
| ------------------ | ------------------ | ------------------ |
| ![](assets/4s.png) | ![](assets/5c.png) | ![](assets/6s.png) |
| ![](assets/4h.png) |                    |                    |

The function `__build_sequence_combinations` returns a list of **2** sequences:

|       | Group 1            | Group 2            | Group 3            |
| ----- | ------------------ | ------------------ | ------------------ |
| Seq 1 | ![](assets/4s.png) | ![](assets/5c.png) | ![](assets/6s.png) |
| Seq 2 | ![](assets/4h.png) | ![](assets/5c.png) | ![](assets/6s.png) |

Let's take another example:

```python
cards = [[TienLenCard('4s'), TienLenCard('4h')], [TienLenCard('5c')], [TienLenCard('6s')], [TienLenCard('7c'), TienLenCard('7d')]]
>>> TienLenTrick.__build_sequence_combinations(cards)
[[TienLenCard('4s'), TienLenCard('5c'), TienLenCard('6s'), TienLenCard('7c'), [TienLenCard('4s'), TienLenCard('5c'), TienLenCard('6s'), TienLenCard('7d'), [TienLenCard('4h'), TienLenCard('5c'), TienLenCard('6s'), TienLenCard('7c'), [TienLenCard('4h'), TienLenCard('5c'), TienLenCard('6s'), TienLenCard('7d')]
```

We can visually represent this example as follows. Below is a list of cards that is passed to the function `__build_sequence_combinations`:

| Group 1            | Group 2            | Group 3            | Group 4            |
| ------------------ | ------------------ | ------------------ | ------------------ |
| ![](assets/4s.png) | ![](assets/5c.png) | ![](assets/6s.png) | ![](assets/7c.png) |
| ![](assets/4h.png) |                    |                    | ![](assets/7d.png) |

The function `__build_sequence_combinations` returns a list of **4** sequences:

|       | Group 1            | Group 2            | Group 3            | Group 4            |
| ----- | ------------------ | ------------------ | ------------------ | ------------------ |
| Seq 1 | ![](assets/4s.png) | ![](assets/5c.png) | ![](assets/6s.png) | ![](assets/7c.png) |
| Seq 2 | ![](assets/4s.png) | ![](assets/5c.png) | ![](assets/6s.png) | ![](assets/7d.png) |
| Seq 3 | ![](assets/4h.png) | ![](assets/5c.png) | ![](assets/6s.png) | ![](assets/7c.png) |
| Seq 4 | ![](assets/4h.png) | ![](assets/5c.png) | ![](assets/6s.png) | ![](assets/7d.png) |

Your class method `find_sequences` needs to combine the private static methods `__build_rank_sequences_indices`, `__build_variable_length_sequence_ranks`, and `__build_sequence_combinations`, to find all the **sequences** of different lengths.

## Waypoint 16: Find Double Sequences

Write a class method `find_double_sequences` of the class `TienLenTrick` that takes an argument `cards` (a list of objects `TienLenCard`) and that returns a list of all the **double sequences** (list of objects `TienLenTrick`) that can be formed with these cards.

For example:

```python
>>> cards = [TienLenCard('Qh'), TienLenCard('4c'), TienLenCard('Qc'), TienLenCard('9s'), TienLenCard('5s'), TienLenCard('8d'), TienLenCard('Th'), TienLenCard('Qs'), TienLenCard('Ts'), TienLenCard('Kd'), TienLenCard('Jd'), TienLenCard('Js'), TienLenCard('Kh')]
>>> TienLenTrick.find_double_sequences(cards)
[
    [TienLenCard('Ts'), TienLenCard('Th'), TienLenCard('Js'), TienLenCard('Jd'), TienLenCard('Qs'), TienLenCard('Qc')],
    [TienLenCard('Ts'), TienLenCard('Th'), TienLenCard('Js'), TienLenCard('Jd'), TienLenCard('Qc'), TienLenCard('Qh')],
    [TienLenCard('Ts'), TienLenCard('Th'), TienLenCard('Js'), TienLenCard('Jd'), TienLenCard('Qs'), TienLenCard('Qh')],
    [TienLenCard('Js'), TienLenCard('Jd'), TienLenCard('Qs'), TienLenCard('Qc'), TienLenCard('Kd'), TienLenCard('Kh')],
    [TienLenCard('Js'), TienLenCard('Jd'), TienLenCard('Qc'), TienLenCard('Qh'), TienLenCard('Kd'), TienLenCard('Kh')],
    [TienLenCard('Js'), TienLenCard('Jd'), TienLenCard('Qs'), TienLenCard('Qh'), TienLenCard('Kd'), TienLenCard('Kh')],
    [TienLenCard('Ts'), TienLenCard('Th'), TienLenCard('Js'), TienLenCard('Jd'), TienLenCard('Qs'), TienLenCard('Qc'), TienLenCard('Kd'), TienLenCard('Kh')],
    [TienLenCard('Ts'), TienLenCard('Th'), TienLenCard('Js'), TienLenCard('Jd'), TienLenCard('Qc'), TienLenCard('Qh'), TienLenCard('Kd'), TienLenCard('Kh')],
    [TienLenCard('Ts'), TienLenCard('Th'), TienLenCard('Js'), TienLenCard('Jd'), TienLenCard('Qs'), TienLenCard('Qh'), TienLenCard('Kd'), TienLenCard('Kh')]
]
```

This example can be visually represented with the following cards in the hand of the player:

| `4c`               | `5s`               | `8d`               | `9s`               | `Ts`               | `Th`               | `Js`               | `Jd`               | `Qs`               | `Qc`               | `Qh`               | `Kd`               | `Kh`               |
| ------------------ | ------------------ | ------------------ | ------------------ | ------------------ | ------------------ | ------------------ | ------------------ | ------------------ | ------------------ | ------------------ | ------------------ | ------------------ |
| ![](assets/4c.png) | ![](assets/5s.png) | ![](assets/8d.png) | ![](assets/9s.png) | ![](assets/Ts.png) | ![](assets/Th.png) | ![](assets/Js.png) | ![](assets/Jd.png) | ![](assets/Qs.png) | ![](assets/Qc.png) | ![](assets/Qh.png) | ![](assets/Kd.png) | ![](assets/Kh.png) |

The **double sequences** the player can form with the cards in their hand are (from left to right):

|       |                    |                    |                    |                    |                    |                    |                    |                    |
| ----- | ------------------ | ------------------ | ------------------ | ------------------ | ------------------ | ------------------ | ------------------ | ------------------ |
| Seq 1 | ![](assets/Ts.png) | ![](assets/Th.png) | ![](assets/Js.png) | ![](assets/Jd.png) | ![](assets/Qs.png) | ![](assets/Qc.png) |
| Seq 2 | ![](assets/Ts.png) | ![](assets/Th.png) | ![](assets/Js.png) | ![](assets/Jd.png) | ![](assets/Qs.png) | ![](assets/Qh.png) |
| Seq 3 | ![](assets/Ts.png) | ![](assets/Th.png) | ![](assets/Js.png) | ![](assets/Jd.png) | ![](assets/Qc.png) | ![](assets/Qh.png) |
| Seq 4 | ![](assets/Js.png) | ![](assets/Jd.png) | ![](assets/Qs.png) | ![](assets/Qc.png) | ![](assets/Kd.png) | ![](assets/Kh.png) |
| Seq 5 | ![](assets/Js.png) | ![](assets/Jd.png) | ![](assets/Qs.png) | ![](assets/Qh.png) | ![](assets/Kd.png) | ![](assets/Kh.png) |
| Seq 6 | ![](assets/Js.png) | ![](assets/Jd.png) | ![](assets/Qc.png) | ![](assets/Qh.png) | ![](assets/Kd.png) | ![](assets/Kh.png) |
| Seq 7 | ![](assets/Ts.png) | ![](assets/Th.png) | ![](assets/Js.png) | ![](assets/Jd.png) | ![](assets/Qs.png) | ![](assets/Qc.png) | ![](assets/Kd.png) | ![](assets/Kh.png) |
| Seq 8 | ![](assets/Ts.png) | ![](assets/Th.png) | ![](assets/Js.png) | ![](assets/Jd.png) | ![](assets/Qs.png) | ![](assets/Qh.png) | ![](assets/Kd.png) | ![](assets/Kh.png) |
| Seq 9 | ![](assets/Ts.png) | ![](assets/Th.png) | ![](assets/Js.png) | ![](assets/Jd.png) | ![](assets/Qc.png) | ![](assets/Qh.png) | ![](assets/Kd.png) | ![](assets/Kh.png) |

Building the list of **double sequences** is very similar to building the list of **sequences** except that it is applied to pairs of cards instead of single cards.

You start with finding all the pairs of cards. You have already developed such a function in a previous waypoint.

Your class method `find_double_sequences` combines the private static methods `__build_rank_sequences_indices`, `__build_variable_length_sequence_ranks`, and `__build_sequence_combinations`, to find all the **double sequences** of different lengths, exactly the same way your class method `find_sequences` does.

## Waypoint 17: Protect class `TienLenTrick`'s Constructor

Back to waypoint 9, we have seen that the constructor of the class `TienLenTrick` accepts two arguments `trick_type` and `cards`, but it doesn't check whether the values of these arguments are coherent. For example, we can build a new object `TientLenTrick` by passing the following arguments that don't make sense:

```python
>>> trick = TienLenTrick(
...     TienLenTrick.TrickType.triple,
...     [TienLenCard('4c'), TienLenCard('6h'), TienLenCard('Jc')])
```

The reason we don't check the coherence of the arguments in the constructor of the class `TienLenTrick` is because this constructor is actually called by the methods `find_singles`, `find_pairs`, `find_triples`, etc., which pass coherent values to the constructor. Testing the coherence of the arguments `trick_type` and `cards` in the the constructor of the class `TienLenTrick` would be useless and CPU consuming.

The problem is that this constructor is public, meaning that functions other than the aforementioned methods could potentially call this constructor with incoherent values. We need to protect the access to this constructor. For that, we will use the [factory method pattern](https://en.wikipedia.org/wiki/Factory_method_pattern).

The problem here is that the programming language Python doesn't have the concept of a **protected** or **private** constructor like in other programming languages such as Java, only a **public** constructor. 

For example: using Java, it would be trivial to implement the factory method patten by declaring a **public** factory method `findPairs` and declaring the constructor of the class `TienLenTrick` as **private**:

```java
public class TienLenTrick {
  public enum TrickType{
    SINGLE,
    PAIR,
    TRIPLE,
    FOUR_OF_A_KIND,
    SEQUENCE,
    DOUBLE_SEQUENCE
  }

  private ArrayList<TienLenCard> mCards;
  private TrickType mType;

  private TienLenTrick(TrickType type, ArrayList<TienLenCard> cards) {
    mType = type;
    mCards = cards;
  }

  public static ArrayList<TienLenTrick> findPairs(ArrayList<TienLenCard> cards) {
    ArrayList<TienLenTrick> tricks = new ArrayList<TienLenTrick>();

    // Find the list of pairs.
    (...)

    for (ArrayList<TienLenCard> pair : pairs) {
      tricks.add(new TienLenTrick(TrickType.PAIR, pair));
    }

    return tricks;
  }
}
```

Having said that, there are some ways to hack Python and to protect the constructor of a class to avoid building instances of this class.

For example:

```python
class Foo:
    def __init__(self):
        if self.__class__.__name__ == Foo.__name__:
            raise Exception(f"The class {self.__class__.__name__} MUST be instantiated with its factory methods")
```

This code prevents instantiating new objects `Foo` by directly calling its constructor:

```python
>>> foo = Foo()
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
  File "<stdin>", line 4, in __init__
Exception: The class Foo MUST be instantiated with its factory methods
```

So now, we cannot instantiate new objects `Foo`! How does this help us?! Well, you can create a class `FooImpl` that inherits from `Foo`.

```python
class FooImpl(Foo):
    def __init__(self):
      super().__init__()
```

And now we are allowed to instantiate objects `FooImpl`:

```python
>>> foo = FooImpl()
>>> foo
<__main__.FooImpl object at 0x10d9c69e8>
>>> isinstance(foo, Foo)
True
```

Now, we need to hide the class `FooImpl` so that it cannot be instantiated from outside the class `Foo`. We can simply locally declare the private class in a **static** method of the class `Foo`:

```python
class Foo:
    def __init__(self):
        if self.__class__.__name__ == Foo.__name__:
            raise Exception(f"The class {self.__class__.__name__} MUST be instantiated with its factory methods")

    @staticmethod
    def __build_instance():
        class __FooImpl(Foo):
            def __init__(self):
                super().__init__()

        return __FooImpl()

    @classmethod
    def my_factory_method(cls):
        return cls.__build_instance()
```

This hack works like a charm:

```python
>>> foo = Foo()
  File "<input>", line 1, in <module>
  File "<string>", line 4, in __init__
Exception: The class Foo MUST be instantiated with its factory methods
>>> foo = Foo.my_factory_method()
>>> foo
<__main__.Foo.my_factory_method.<locals>.__FooImpl object at 0x10d9c6ba8>
>>> isinstance(foo, Foo)
True
```

_Note: You cannot define the **private** inner class `__FooImpl` as follows because it references the class `Foo` which is not yet defined when the class `__FooImpl` is declared:_

<em>

```python
>>> class Foo:
...    class __FooImpl(Foo):
...        def __init__(self):
...            super().__init__()
...
...    def __init__(self):
...        if self.__class__.__name__ == Foo.__name__:
...            raise Exception(f"The class {self.__class__.__name__} MUST be instantiated with its factory methods")
...
...    @classmethod
...    def my_factory_method(cls):
...        return Foo.__FooImpl()
...
Traceback (most recent call last):
File "<stdin>", line 1, in <module>
File "<stdin>", line 2, in Foo
NameError: name 'Foo' is not defined
```

</em>

Update the constructor of your class `TienLenTrick` and all the class methods `find_*` to implement this [software design pattern](https://en.wikipedia.org/wiki/Software_design_pattern).

For example:

```python
# We can build `TienLenTrick` objects from the factory methods
>>> pprint.pprint(TienLenTrick.find_pairs([TienLenCard('9h'), TienLenCard('Jc'), TienLenCard('9c'), TienLenCard('4h'), TienLenCard('8h'), TienLenCard('7d'), TienLenCard('Qc'), TienLenCard('As'), TienLenCard('7h'), TienLenCard('Qd'), TienLenCard('Jh'), TienLenCard('9d'), TienLenCard('8c')]))
[__TienLenTrickImpl(TienLenTrickType.pair, [TienLenCard('9c'), TienLenCard('9h')]),
 __TienLenTrickImpl(TienLenTrickType.pair, [TienLenCard('9d'), TienLenCard('9h')]),
 __TienLenTrickImpl(TienLenTrickType.pair, [TienLenCard('9c'), TienLenCard('9d')]),
 __TienLenTrickImpl(TienLenTrickType.pair, [TienLenCard('Jc'), TienLenCard('Jh')]),
 __TienLenTrickImpl(TienLenTrickType.pair, [TienLenCard('8c'), TienLenCard('8h')]),
 __TienLenTrickImpl(TienLenTrickType.pair, [TienLenCard('7d'), TienLenCard('7h')]),
 __TienLenTrickImpl(TienLenTrickType.pair, [TienLenCard('Qc'), TienLenCard('Qd')])]

# But we cannot build `TienLenTrick` by calling its constructor
>>> trick = TienLenTrick(
...     TienLenTrick.TrickType.triple,
...     [TienLenCard('4c'), TienLenCard('6h'), TienLenCard('Jc')])
Traceback (most recent call last)
  File "<string>", line 3, in <module>
  File "<string>", line 230, in __init__
Exception: The class TienLenTrick MUST be instantiated with its factory methods
```

## Waypoint 18: Build a Tiến Lên Trick from a List of Cards

We need to have another **factory method** to build an object `TienLenTrick` from a list of cards. This method needs to verify that the combination of cards corresponds to a valid Tiến Lên trick. This method needs to find which trick this combination of cards corresponds to.

Write a **class method** `build_trick` in your class `TienLenTrick` that takes an argument `cards` (a list of objects `TienLenCard`) and that returns an object `TienLenTrick`.

If the argument `cards` doesn't correspond to a valid Tiến Lên trick, the method `build_trick` raises an exception `ValueError`.

For example:

```python
>>> TienLenTrick.build_trick([TienLenCard('6s'), TienLenCard('6c'), TienLenCard('6d')])
__TienLenTrickImpl(TienLenTrickType.triple, [TienLenCard('6s') TienLenCard('6c') TienLenCard('6d')])
>>> TienLenTrick.build_trick([TienLenCard('4c'), TienLenCard('6h'), TienLenCard('Jc')])
Traceback (most recent call last):
  File "<input>", line 1, in <module>
  File "<string>", line 260, in build_trick
ValueError: the cards 4c 6h Jc don't correspond to a Tiến Len trick
```

# Players

Tiến Lên is usually played with 4 players (2 minimum).

We are not going to implement a [multiplayer video](https://en.wikipedia.org/wiki/Multiplayer_video_game) [online game](https://en.wikipedia.org/wiki/Online_game), but a [single player](https://en.wikipedia.org/wiki/Single-player_video_game) video game. The user (**player character**) will play against opponents (**non-player characters**) controlled by the computer.

The [**player character** (PC)](https://en.wikipedia.org/wiki/Player_character) will be directly controlled by the user themself, while the [**non-player characters** (NPC)](https://en.wikipedia.org/wiki/Non-player_character) will be controlled by a primitive and limited [Artificial Intelligence (AI)](https://en.wikipedia.org/wiki/Artificial_intelligence_in_video_games).

_Note: This type of **NPC** is actually called a [**Bot**](https://en.wikipedia.org/wiki/Video_game_bot). The key distinction is that a **Bot** represents an automated player, while an **NPC**, by contrast, isn't playing the game at all. But for the sake of simplicity, we will use the term **NPC** instead._

## Waypoint 19: Class `Player`

The game engine (to be implemented later in this mission) does not differentiate between a **PC** and an **NPC**; the game engine simply handles **players**.

Write a class `Player` that represents a player. This class will be the parent class for **PC** or **NPC**.

The constructor of the class `Player` accepts an argument **name** representing the name of the player. The class `Player` stores the name of the player in a private [instance attribute](https://medium.com/swlh/class-and-object-attributes-python-8191dcd1f4cf).

The class `Player` has a readable and a writable property `name` to access the name of the player.

For example:

```python
>>> player = Player('LÝ Thị Kim Anh')
>>> player.name
'LÝ Thị Kim Anh'
>>> player.name = 'LÝ Thị Minh Anh'
>>> player.name
'LÝ Thị Minh Anh'
```

The constructor and the setter method `name` of the class `Player` **MUST** remove any leading and trailing whitespace characters, and remove any duplicated whitespace characters between words.

_Note: This is the reason why we're using a `property` (and a private instance attribute) instead of a public instance attribute; we better control changes applied to the value stored in our object._

For example:

```python
>>> player = Player('  LÝ   Thị    Kim  Anh ')
>>> player.name
'LÝ Thị Kim Anh'
>>> player.name = ' LÝ  Thị Minh    Anh   '
>>> player.name
'LÝ Thị Minh Anh'
```

## Waypoint 20: Class `PC`

Write a class `PC` that [inherits](https://www.digitalocean.com/community/tutorials/understanding-class-inheritance-in-python-3) from the [parent class](https://realpython.com/inheritance-composition-python/) `Player`.

The constructor of the class `PC` accepts an argument **name** representing the name of the player. This name **MUST** be stored in the private attribute of the parent class `Player`.

For example:

```python
>>> pc = PC('  LÝ   Thanh Phú ')
>>> pc.name
'LÝ Thanh Phú'
>>> pc.name = 'NGUYỄN Bá   Trí '
>>> pc.name
'NGUYỄN Bá Trí'
```

_Note: Do you need to write a specific constructor for the class `PC`? ;)_

## Waypoint 21: Class `NPC`

Write a class `NPC` that inherits from the parent class `Player`.

The constructor of the class `NPC` doesn't take any arguments. This constructor automatically generates a name for the object that is created.

For example:

```python
>>> npc = NPC()
>>> npc.name
'Tsushimada'
```

How can you automatically generate a name for a **NPC**? You can write your own library for generating hunan-readable names, or you can use an existing library such as [`perseus-name-generator-library`](https://github.com/dcaune/perseus-name-generator-python-library) that you can easily install with `pipenv` as follows:

```bash
$ pipenv install perseus-name-generator-library
```

_Note: You will make sure that you don't instantiate a new `NameGenerator` object every time you create a new `NPC` object. You **SHOULD** use a private [class attribute](https://realpython.com/lessons/class-and-instance-attributes/)._

# Game & Player Session

A **game session** is an instance of Tiến Lên game. Players join by creating a **player session** for the game session.

## Waypoint 22: Class `GameSession`

Write a class `GameSession` that represents a session of a Tiến Lên game between players. You can compare a game session with a table where players sit at to play.

The constructor of the class `GameSession` takes one argument `name` (a string) that corresponds to the human-readable name of the game session. This name is [immutable](https://en.wikipedia.org/wiki/Immutable_object).

For example:

```python
>>> game_session = GameSession("Tiến Lên Table 1")
>>> game_session.name
'Tiến Lên Table 1'
>>> game_session.name = "Tiến Lên #1"
Traceback (most recent call last):
  File "<input>", line 1, in <module>
AttributeError: can't set attribute
```

## Waypoint 23: Class `PlayerSession`

Write a class `PlayerSession` that represents the session of a player who joins a Tiến Lên game. A player session is created for each player who sits at a Tiến Lên table.

A Tiến Lên game session corresponds to a virtual table. A player can sit at many tables, meaning a player can handle several **player sessions**.

The constructor of the class `PlayerSession` takes two arguments:

- `player`: An object `Player` that references the player who is joining a game session.

- `game_session`: An object `GameSession` that references the game session that a player is joining.

For example:

```python
>>> player = PC('lythanhphu')
>>> game_session = GameSession("Tiến Lên Table 1")
>>> player_session = PlayerSession(player, game_session)
```

## Waypoint 24: Joining a Game Session (1)

The class `PlayerSession` is instantiated when a player joins a game session.

Write an instance method `join` in the class `GameSession` that takes one argument `player` (an object `Player` that references the player who is joining a game session).

The method `join` returns an object `PlayerSession` corresponding to the player joining the game session. A player cannot join more than once in a given game session.

For example:

```python
>>> pc = PC('lythanhphu')
>>> game_session = GameSession("Tiến Lên Table 1")
>>> game_session.join(pc)
<__main__.PlayerSession object at 0x105c82c88>
>>> game_session.join(pc)
Traceback (most recent call last):
  File "<input>", line 1, in <module>
  File "<string>", line 858, in join
GameSession.PlayerHasAlreadyJoinedException: The player "lythanhphu" has already joined this game session
```

A game session accepts a maximum of 4 players:

```python
>>> game_session = GameSession("Tiến Lên Table 1")
>>> game_session.join(NPC())
<__main__.PlayerSession object at 0x10c1a6518>
>>> game_session.join(NPC())
<__main__.PlayerSession object at 0x10c1a6ac8>
>>> game_session.join(NPC())
<__main__.PlayerSession object at 0x10c1a6f98>
>>> game_session.join(NPC())
<__main__.PlayerSession object at 0x10c1a6898>
>>> game_session.join(NPC())
Traceback (most recent call last):
  File "<input>", line 1, in <module>
  File "<string>", line 861, in join
GameSession.NoSeatLeftException: All the seats are already occupied
```

You need to write classes for the exceptions `PlayerHasAlreadyJoinedException` and `NoSeatLeftException`. You should consider writing a parent class `GameSessionException` that inherits from the built-in [`Exception`](https://docs.python.org/3/library/exceptions.html#Exception).

## Waypoint 25: Joining a Game Session (2)

Add an instance method `join_game_session` to the class `Player` that takes an argument `game_session` (an object `GameSesion` that represents an existing game session) and that returns nothing.

The method `join_game_session` calls the method `join` of the object `game_session` that returns an object `PlayerSession`. The method `join_game_session` needs to add this object `PlayerSession` in an attribute of the class `Player` (more likely a list) to keep track of all the game sessions the player has joined. However, the method `join_game_session` **MUST NOT** return the object `PlayerSession` for security reasons that we will discuss later.

For example:

```python
>>> game_session1 = GameSession("Tiến Lên Table 1")
>>> game_session2 = GameSession("Tiến Lên Table 2")
>>> pc = PC('lythanhphu')
>>> pc.join_game_session(game_session1)
>>> pc.join_game_session(game_session2)
```

The `PlayerSession` will be used later to store the cards that are dealt to the player in the game session. Because the player can join several game sessions, the class `Player` handles several `PlayerSession` objects.

You **SHOULD NOT** store the player sessions in a **private** attribute, but a **protected** attribute, otherwise the player sessions would not be accessible from within a child class such as `PC` or `NPC`.

<em>Note: In [Object Oriented Programming (OOP)](https://en.wikipedia.org/wiki/Object-oriented_programming), **data encapsulation** leads to an important concept of controlling access to attributes of a class using different levels of access to these attributes, for example:

- **public**: These attributes are accessible to any code.
- **protected**: These attributes are accessible from within the class and are also available to its sub-classes. This enables some attributes of the parent class to be inherited by the child class.
- **private**: These attributes are only accessible from within the class.

A class may permit access to **private** (or even **protected**) attributes through methods only: this is a strong form of **abstraction** known as **encapsulation**.

In Python, access to **protected** attributes is enforced only by convention: **protected attributes** have names that start with an underscore. That is telling others "[can’t touch this](https://www.youtube.com/watch?v=otCpCn0l4Wo) (unless you’re a child class)".

```python
# Define a class with public, protected, and private attributes.
>>> class Person:
...     def __init__(self, name, dob, sex):
...         self.name = name  # public attribute
...         self.__dob = dob  # private attribute
...         self._sex = sex   # protected attribute

# Instantiate an object of this class.
>>> person = Person('LÝ Thanh Phú', '1975-09-22', 'M')

# Access to the public attribute "name".
>>> person.name
'LÝ Thanh Phú'

# Access to the private attribute "__dob".
>>> person.__dob
Traceback (most recent call last):
  File "<input>", line 1, in <module>
AttributeError: 'Person' object has no attribute '__dob'

# Access to the supposedly protected attribute "_sex"!... :/
>>> person._sex
'M'

# Even the private attribute "__dob" is not really private in
# Python!... :(
>>> vars(person)
{'name': 'LÝ Thanh Phú', '_Person__dob': '1975-09-22', '_sex': 'M'}
>>> person._Person__dob
'1975-09-22'
```

</em>

# Game Engine

## Waypoint 26: Class `GameEngine`

Write the class `GameEngine` that represents the controller of all the Tiến Lên game sessions that will be created.

The constructor of the `GameEngine` doesn't take any arguments.

For example:

```python
>>> game_engine = GameEngine()
```

## Waypoint 27: Create Game Sessions

Write the instance method `create_game_session` to the class `GameEngine` that takes one argument `name` (a string) and returns an object `GameSession` that is created with this name.

The game engine doesn't allow us to create a game session with a name that is already used. If the method `create_game_session` is passed a game session name that already exits, the method raises the exception `GameSessionAlreadyExistException`.

For example:

```python
>>> game_engine = GameEngine()
>>> game_session = game_engine.create_game_session("Tiến Lên Table 1")
>>> game_session = game_engine.create_game_session("Tiến Lên Table 1")
Traceback (most recent call last):
  File "<input>", line 1, in <module>
  File "<string>", line 14, in create_game_session
GameEngine.GameSessionAlreadyExistException: The game session "Tiến Lên Table 1" already exists
```

# Game Events

We will use an [event-driven programming](https://en.wikipedia.org/wiki/Event-driven_programming) paradigm to notify the players of the different phases and actions (the flow) within a game session.

Below we provide a list of the events (in a logical sequence) that occur during a Tiến Lên game session:

- `on_player_joined`: Invoked when a player joins a game session. This event is sent to the players who have already joined the game session. This event provides a reference to the player who just joined the game session.

- `on_game_started`: Invoked when a game session starts. This event is sent to the players who have joined the game session.

- `on_cards_dealt`: Invoked when cards are dealt to a player. This event is only sent to the player who is receiving these cards. This event provides the list of cards that have been dealt to the player.

* `on_round_started`: Invoked when a new round starts in a game session. This event is sent to the players who have joined the game session. This event provides the round number within the current game session.

* `on_player_in_turn`: Invoked when this is the turn of a player (**current player**) to play some cards. This event is sent to the players who have joined the game session. This event provides a reference of the player who needs to play (or pass). At this particular time, the **current player** needs to play some cards (or pass).

* `on_cards_played`: Invoked when the **current player** plays some cards. This event is sent to the players who have joined the game session. This event provides a reference to the **current player** and the list of cards that have been played.

* `on_player_passed`: Invoked when the **current player** passes their turn. This event is sent to the players who have joined the game session, except the current player that passed their turn. This event provides a reference to the **current player**.

* `on_round_ended`: Invoked when a round of a game session ends. This event is sent to the players who have joined the game session. This event provides a reference to the players who are in this round.

* `on_game_ended`: Invoked when a game session ends. This event is sent to the players who have joined the game session. This event provides a reference to the player who won the game session.

Below we provide the [diagram sequence](https://en.wikipedia.org/wiki/Sequence_diagram) of a short example of a game session between 2 players:

![Tiến Lên Game Events Sequence Diagram](tien_len_game_events_sequence_diagram.svg)

## Waypoint 28: Event `on_cards_dealt`

Add the instance method `on_cards_dealt` to the class `Player`, which takes 2 arguments:

- `game_session`: An object `GameSession` that references the game session for which this event occurs.

- `cards`: A list of object `Card` that are dealt to the player.

<!-- The method `on_cards_dealt` **SHOULD** store the cards that have been dealt to the player in a **_protected_** attribute. You **SHOULD NOT** stores the cards in a **private** attribute, otherwise the cards would not be accessible from within a child class such as `PC` or `NPC`. -->

## Waypoint 29: Event `on_player_joined`

Add the instance method `on_player_joined` to the class `Player`, which takes two arguments `game_session` (an object `GameSession` that references the game session for which this event occurs) and `player` (an object `Player` that references the player who just joined the game session).

## Waypoint 30: Events `on_game_started`, `on_game_ended`, `on_round_started`, and `on_round_ended`

Add the instance methods `on_game_started` and `on_round_stated` to the class `Player`, which takes one argument `game_session` (an object `GameSession` that references the game session for which this event occurs).

Also add the instance methods `on_game_ended` and `on_round_ended` to the class `Player`, which takes two arguments `game_session` and `winner` (an object `Player` that references the player who won the game session or the round of the game session).

## Waypoint 31: Event `on_player_in_turn`

Add the instance method `on_player_in_turn` to the class `Player`, which takes two arguments `game_session` (an object `GameSession` that references the game session for which this event occurs) and `current_player` (an object `Player` that references the player who is in turn).

You **SHOULD** store this information in a **protected** attribute of the class `Player`.

## Waypoint 32: Event `on_cards_played`

Add the instance method `on_cards_played` to the class `Player`, which takes two arguments `game_session` (an object `GameSession` that references the game session for which this event occurs) and `cards` (a list of object `Cards` that the **current player** has played).

# Game Logic

## Waypoint 33: Game Logic Main Loop

Write an **instance method** `run` in the class `GameSession` that will be responsible for handling the flow of the game session until the game ends.

1. Raise an exception if there is only one player who has joined the game session.

2. Inform all the players when the game session starts.

3. Deal cards to the players.

4. Find which player starts the game session, i.e., the player with the lowest card.

5. Inform all the players that a round starts.

6. Inform all the players who is going to play.

7. Request the player whose turn it is to provide the trick they would like to play or to pass. If the player is not allowed to play this trick or to pass, redo `7`.

8. Inform all the players about the cards that have been played.

9. If the current player has won the round, inform all the players that the round has ended. If the player has won the game, inform all the players that the game has ended and return the method `run`, otherwise go to `5`.

10. Determine the new current player of the round and go to `6`.

## Waypoint 34: Abstract Method `play`

Write the **instance method** `play` in the class `Player` that takes an argument `game_session` (an object `GameSession`) and that returns an object `TienLenTrick` that represents the cards the player would like to play, or `None` if the player prefers to pass.

The method `play` of the class `Player` is actually only declared but it does not contain any logic. The class `Player` is a **base class**. The logic needs to be implemented in the inheriting classes `PC` and `NPC`. We say that the method `play` of the class `Player` is an [**abstract method**](<https://en.wikipedia.org/wiki/Method_(computer_programming)#Abstract_methods>), i.e., a method that is declared, but contains no implementation.

Python didn't initially support the concept of **abstract method**. A technique that was used is to declare a method and to raise the exception [`NotImplementedError`](https://docs.python.org/3/library/exceptions.html#NotImplementedError).

```python
>>> class Animal:
...     def say_something(self):
...         raise NotImplementedError()
>>> class Cat(Animal):
...     def say_something(self):
...         return "Meow!"
>>> class Dog(Animal):
...     def say_something(self):
...         return "Wof wof!"
>>> class Human(Animal):
...     def say_something(self):
...         return "I want a beer!"
>>> Cat().say_something()
'Meow!'
>>> Dog().say_something()
'Wof wof!'
>>> Human().say_something()
'I want a beer!'
>>> Animal().say_something()
Traceback (most recent call last):
  File "<input>", line 1, in <module>
  File "<string>", line 4, in say_something
NotImplementedError
```

Python recently introduced the module [`abc`](https://docs.python.org/3/library/abc.html) that provides support for declaring [**abstract classes and methods**](https://realpython.com/inheritance-composition-python/#abstract-base-classes-in-python).

We can declare the class `Animal` as **abstract**, and declare the method `say_something` as **abstract**:

```python
>>> from abc import ABC, abstractmethod
>>> class Animal(ABC):
...     @abstractmethod
...     def say_something(self):
...         pass
>>> class Cat(Animal):
...     def say_something(self):
...         return "Meow!"
>>> class Dog(Animal):
...     def say_something(self):
...         return "Wof wof!"
>>> Cat().say_something()
'Meow!'
>>> Dog().say_something()
'Wof wof!'
```

If we declare a class `Human` inherited from `Animal`, and we don't provide an implementation of the **abstract method** `say_something`, we won't be able to instantiate this class `Human`:

```python
>>> class Human(Animal):
...     pass
>>> Human().say_something()
Traceback (most recent call last):
  File "<input>", line 1, in <module>
TypeError: Can't instantiate abstract class Human with abstract methods say_something
>>> Animal().say_something()
Traceback (most recent call last):
  File "<input>", line 1, in <module>
TypeError: Can't instantiate abstract class Animal with abstract methods say_something
```

Declare the **instance method** `play` of the class `Player` as **abstract** and write the **instance method** `play` in both classes `PC` and `NPC`. The initial implementation of the method `play` of these two classes `PC` and `NPC` is empty. Just return `None`. We will complete this part in the next waypoint.

## Waypoint 35: Method `play` Implementation for Player Character (PC)

The method `play` of the class `PC` interacts with the real player. It requests the player to enter the list of cards the player would like to play. The method `play` builds and returns an object `TienLenTrick`.

The method `play` needs to translate the characters entered by the player to a list of cards, to check whether the player currently has these cards in their hand, and whether the combination of these cards corresponds to a valid Tiến Len trick. The method `play` will loop until the player respects these requirements.

For example:

```text
You turn! You have the following cards in your hands:
   3s 3c 4d 4h 7c 7h 9h Ts Td Js Qs As 2d
Enter the cards (separated with comma or space) to play: 3s 3c 4d 4h 7c 7h
Dude, what trick is that 3s 3c 4d 4h 7c 7h?!
Enter the cards (separated with comma or space) to play: 2d 2h 2c 2s
You might be kidding! You don't have the card 2h!
Enter the cards (separated with comma or space) to play: Js Qs Td 9h
You play 9h Td Js Qs
```

## Waypoint 36: Method `play` Implementation for Non Player Character (NPC)

Implement the method `play` of the class `NPC` to integrate a naive Artificial Intelligence. We just expect that your method `play` returns a Tiên Lên trick that is coherent in the context of the round:

- Any trick if the bot is starting a round.
- A trick that is higher than the trick previously played by another player.

The method `play` can decide that the bot is passing (if the bot is not starting a round).
