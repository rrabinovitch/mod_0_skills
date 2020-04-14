# Class 1 Example Object

* Instance: tomato_soup
* Attributes:
  1. `entree_name = "Tomato Soup"`
  2. `price = 5.99`
  3. `number_dishes_available = 15`
  4. `ingredients = {
        "tomato" => "3 cups, diced"
        "tomato paste" => "1 can"
        "onion" => "1/4 cup, chopped"
        "ground pepper" => "1/2 teaspoon"
        "salt" => "1/2 teaspoon"
      }`
* Methods:
  1. `place_order(tomato_soup)`
    * ```
      puts "You have placed an order for #{tomato_soup.entree_name}, which costs $#{tomato_soup.price}."
      number_dishes_available = number_dishes_available - 1
      ```
  2. `change_price(-1.05)`
    * ```
      price = 5.99 - difference_in_price
      =>
      price = 4.94
      ```
  3. `change_entree_name("Snazzy Red Bisque")`
    * ```
      entree_name = new_entree_name
      =>
      entree_name = "Snazzy Red Bisque"
      ```
  4. `update_ingredients`: remove onions from recipe
      ```
      ingredients = {
            "tomato" => "3 cups, diced"
            "tomato paste" => "1 can"
            "ground pepper" => "1/2 teaspoon"
            "salt" => "1/2 teaspoon"
          }
      ```
