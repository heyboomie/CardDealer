# CardDealer
Deals 1 hand with a variable size from a standard 52-card deck
Inputs:
  This code takes 2 inputs
    The first input is internally called "cardList" which is a list containing one 0 for each card, which updates to prevent drawing a card twice.
    The second input is interally called "handCount" which is an interger which dictates how many cards are drawn for each hand
Outputs:
  This code returns 2 outputs
    The first output is internally called "cardList" which outputs a list with a value for each card, 0 if not yet drawn, and 1 if already drawn.
    The secound output is internally called "hand" which is a list conatining tuples which are the cards drawin in the hand
      The tuples contains card value (A, 2, 3, etc.) and type (Clubs, Hearts, etc.)
