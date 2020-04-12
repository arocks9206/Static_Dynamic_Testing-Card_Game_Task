### Testing task 1:

# Carry out static testing on the code below.
# Comment on any errors that you see below.
```ruby

class CardGame


  def checkforAce(card) #Incorrect name convention--check_for_ace()
    if card.value = 1 #operator needs to be '=='
      return true
    else
      return false
    end
  end

  dif highest_card(card1 card2) #Incorrect dif--needs to be def. Comma needed--correct: (card1, card2)
  if card1.value > card2.value #alignment needs to be indented
    return card #which card to return isn't specified
  else
    return card2
  end
end #needs to align with 'def', currently aligning with 'class'
end #extra 'end'--delete

def self.cards_total(cards)
  total #this needs to be set to something, or could be an extra variable.
  for card in cards
    total += card.value
    return "You have a total of" + total #Incorrect layout for a concatenation
  end
end

#missing 'end' for class
