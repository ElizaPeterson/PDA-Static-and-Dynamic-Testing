### Testing task 1:

# Carry out static testing on the code below.
# Comment on any errors that you see below.

Note that we are only looking for errors here.

**Not** any issues with, i.e.: 
Thinking that methods should be renamed or should be class level, or using string interpolation etc. 

These aren't errors but rather standards that vary from developer to developer. 

Only comment on errors that would stop the tests running.

```python

class CardGame:

#Error in the if statement, it should be == to 1 to compare. Else should have a colon.
  def check_for_ace(self, card):
    if card.value = 1:
      return True
    else
      return False
   

#Error in indentation here, the if statement needs to be in one tab. It also should be def instead of dif.
  dif highest_card(self, card1 card2):
  if card1.value > card2.value:
    return card
  else:
    return card2
  

#Error in the concatenation in the return statement, and total should be given an initial value.
def cards_total(self, cards):
  total
  for card in cards:
    total += card.value
    return "You have a total of" + total
  
```
