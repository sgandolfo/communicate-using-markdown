# This is an h1 header

## This is an h2 header

![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png)

```
const inventoryValue = (queryResult) => {
    let accumulator = 0
    const result = queryResult.forEach(element => {
        accumulator += element.currentStock.quantity * element.currentStock.price
    })
    return accumulator;
}
```
