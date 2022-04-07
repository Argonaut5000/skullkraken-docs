## Breeding Calculation Stages

### Attributes based on the parents that are not affected by any modifies are calculated first 

- BG: 47% chance it will match one parent, 6% a mixed background)

- Skin Color: 47% chance it will match one parent, 6% a mixed background)->Accessories(50% chance for each "feature" to match a parent)

- Shiny Bc Of Parent: 25% will a roll for each parent who is shiny themselves)

- Accessories/Features: all have 50% chance to match either parent
    
    1. Eye Shape
    
    2. Eye Color
    
    3. Head
    
    4. Mouth
    
    5. Body
    
    6. Extra Attributes

### Boost Multiplier and affected attributes calculated

- We calculate the total boost multiplier based on stone and parent natural bonuses.

- Shiny Bc of stone, or Roll: 2% x boost = the odds of a shiny BG, or 100% odds if shiny stone is used

- Unique Feature stone or roll: 2% x boost = the odds of a new unique feature or 100% odds if stone is used

- Status (Dead or Mutant) stone or roll: 2% x boost = the odds of Mutant, 2% x boost = the odds of Dead, 100% if stone of either type is used

### Finally Rarity is calculated, based on all resulted BB rolls/calculations.

- If the BB has a Mixed BG AND Skin Color its (L) 

- If the BB is M or D its (L)

- If the BB has a unique item (E) <- this should be the case that if it has a unique item and not by using a stone, but currently if a users uses a stone it will be consider (E)

- If the BB has a shiny BG BUT not stone was used, AND neither parent was shiny its (E)

- If the BB has a Mixed BG or Skin Color or extra attributes (#6 Accessories/Features) its (R)