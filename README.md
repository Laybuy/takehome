# takehome
The Laybuy Takehome test for Devs

## GraphQL Excercise
Implement a simple GrapQL server which implements a single `getMerchants` query.

This query should resolve to our current shop directory API end point which coincidentally returns a collection of merhchants. Ideally most of the attributes should be mapped to the GrapqQL schema.

At Laybuy we love languages like ruby, nodejs/ES6/TypeScript, but please feel free to implement this in whatever language or framework you feel comfortable with.

This is a sample of the `getMerchants` GraphQL query.
```
{
 	getMerchants{
    merchantid
    name
    phone
    imageurl300
  } 
}
```

### API END POINT
*POST* `https://dashboard.laybuy.com/api/general/shophere?country_id=3`

Good Luck, and have fun implementing!


