# Class 1

* Class: `Entree`
* Attributes:
  1. `entree_name` (string)
  2. `price` (float)
  3. `number_dishes_available` (integer; ie, how many more times can the dish be ordered, based on ingredients in stock)
  4. `ingredients` (hash; key = ingredient name as string, value = ingredient amount as string, to allow for different unit types)
* Methods:
  1. `place_order(entree_name)` (A customer places an order for a specific entree, taking the argument using the entree_name so that we know which specific entree is being ordered -- Utilizes `entree_name` and `entree_price`, and modifies `number_dishes_available`)
  2. `change_price(difference_in_price)` (Either increases or decreases the price of an entree, taking the argument of a positive or negative value float that indicates the amount the price should increase/decrease -- Modifies `price`)
  3. `change_entree_name(new_entree_name)` (If the restaurant wants to get more creative with its entree naming practices or wants to make the name of an entree better represent what it is, they can change the name of the entree menu item; takes the argument of new_entree_name to represent the new name -- Modifies `entree_name`)
  4. `update_ingredients` (Allows the restaurant to update the type or amount of ingredients it uses in a dish -- Modifies `ingredients`)
