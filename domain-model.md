#Domain Models In Here

As a supermarket shopper,
So that I can pay for products at checkout,
I'd like to be able to know the total cost of items in my basket.

| Classes       | Methods                         |  Scenario                    | Outputs      |
| ------------- | -------------                   |  ------------                | -----------  |
| `Supermarket` | checkTotal(List<item> items)    |  List is empty               | 0            |
|               |                                 |  List is not empty           | double total |

As an organised individual,
So that I can evaluate my shopping habits,
I'd like to see an itemised receipt that includes the name and price of the products
I bought as well as the quantity, and a total cost of my basket.

| Classes       | Methods                         |  Scenario                    | Outputs      |
| ------------- | -------------                   |  ------------                | -----------  |
| `Supermarket` | makeReceipt(List<item> items)   |  Creates receipt object      | Receipt      |
| `Receipt`     | printReceipt(List<item> items)  |  Prints receipt object       | void         |

