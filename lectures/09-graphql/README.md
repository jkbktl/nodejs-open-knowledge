
# 9. GraphQL

## Links

* [Presentation](https://docs.google.com/presentation/d/1H0dKAiMofkCGX01YjEDJ3KdKePbTNjzGKCC1n67qJQc/edit?usp=sharing)
* [Video](https://www.youtube.com/watch?v=RNqreGmK3gs&list=PLfX7tWavkVjBVmmZOU5sWuyutpekJ6KNP&index=9)

## Theoretical part
* Motivation
  * What's wrong with REST
* GraphQL Language
  * Queries
  * Arguments
  * Variables
  * Aliases
  * Directives
  * Fragments
  * Inline Fragments
  * Mutations

## Practical part
1. `npm install apollo-server-koa graphql merge-graphql-schemas -S`
2. Init graphql server
3. Create typeDefs
4. Create resolvers
5. Implement queries
  * dogs: [Dog]
  * dog(id: Int!): Dog
  * login mutation
6. Authorization & context
7. Data loader
8. Engine
```
apollo schema:publish --endpoint http://localhost:3001/graphql --key="<apollo-engine-service-key>"
```

## Other Resources
- [Language](https://graphql.org/learn/queries/)
- [Public GraphQL APIs](https://github.com/APIs-guru/graphql-apis)
- [GraphQL Tools](https://github.com/chentsulin/awesome-graphql)
- [Countries GraphQL](https://countries.trevorblades.com/)
- [GraphQL Voyager](https://apis.guru/graphql-voyager/)
