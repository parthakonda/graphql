# What is GraphQL?

- new API standard like REST(not exactly)
- open source
- by facebook (Now it is maintained by community)
- enables declerative data fetching
    Question ?<br>
    - What is declerative data loading/fetching? <br>
    - How it is different from the normal HTTP ajax requests?<br>
    Answer: <br>
    Ref: https://stackoverflow.com/questions/38679952/what-is-declarative-data-loading-in-relation-to-falcor-graphql-and-resolver

    The major difference between traditional HTTP Ajax and declerative fetching is that in declerative fetching you'll just declere what you need and underlying implementation will take care of HOW. This will be more abstractive.
- No confusion around having multiple end-points like REST, here only single endpoint will serve all depends on the query. And also this will serve the data      precisely which client asked for.



# Why GraphQL ?

- Since the mobile usage is increased, the data loading needs to be very efficient
- Since the platforms/frameworks are increased, single API is not enough to serve for all these.
- Pace of development needs to be high, if you consider REST based thing then if there are any changes in the API then that needs to exposed and modified.

Above are the main requirements to design an API query language.


# History of GraphQL

- Facebook started it and uses GraphQL since 2012 in their native mobile apps
- First time they presented in react.js conf 2015 and after some time they made that as public.
- GraphQL is not a technology and it is more of a API Query Language and independent of implementation in any language.