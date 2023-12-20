| **Methods**                       | **Inputs**                               | **Data**                         | **Scenario**                                     | **Outputs**                                |
| --------------------------------- | ---------------------------------------- | -------------------------------- | ------------------------------------------------ | ------------------------------------------ |
| `getBasket()`                     | None                                     | `this.basket`                    | Get all items in the basket                      | Array of items in the basket               |
| `setBasketSize(size)`             | `size: String`                           | `this.basketSizes`               | Set the size of the basket                       | Updated basket size                        |
| `addItem(itemName, itemQuantity)` | `itemName: String, itemQuantity: Number` | `this.basket`, `MENU.GetMenu()`  | Add an item to the basket                        | Updated basket contents                    |
| `removeItem(itemName)`            | `itemName: String`                       | `this.basket`                    | Remove an item from the basket                   | Updated basket contents or error message   |
| `basketCapacity()`                | None                                     | `this.basket`, `this.basketSize` | Check if the basket is full                      | String indicating if basket is full or not |
| `priceChecker(itemName)`          | `itemName: String`                       | `MENU.GetMenu()`                 | Get the price of an item from the menu           | Price of the item                          |
| `basketTotal()`                   | None                                     | `this.basket`                    | Calculate the total price of items in the basket | Total price of items in the basket         |
| `GetMenu()`                       | None                                     | None                             | Get the menu items and their prices              | Object representing menu items and prices  |