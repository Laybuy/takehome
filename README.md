# takehome
The Laybuy Takehome test for Devs

## Backend GraphQL Excercise
Implement a simple GraphQL server which implements a single `getTiles` query.

This query should resolve to our current shop directory API end point which returns a collection of merhchant tiles. Ideally most of the key attributes should be mapped to the GrapqQL schema.

At Laybuy we love languages like ruby, nodejs/ES6/TypeScript/Go, but please feel free to implement this in whatever language or framework you feel comfortable with.

This is a sample of the `getTiles` GraphQL query.
```
{
    getTiles{
        id
        name
        url
        tileImage
    } 
}
```

### API END POINT
**GET** `https://shop-directory-heroku.laybuy.com/api/tiles?page%5Bsize%5D=8&page%5Bnumber%5D=1&include=activePromotion&filter%5Border%5D=Offers%20%26%20Deals&filter%5Bcategory_id%5D=1`

Good Luck, and have fun implementing!

## Frontend React Excercise (Bonus)

Now if you wanted to flex your frontend skills, be our guest :) We'd love to see your React chops, by consuming the GraphQL query you've built above, build out React components which showcases our merchant tiles in a grid format.

Use libraries, frameworks, and tooling to make your life easier, the most important thing here is the end result. 

Can't wait to see what you've built!


