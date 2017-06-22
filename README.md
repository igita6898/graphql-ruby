# graphql-ruby

## Installation

Install dependencies:

```
bundle install

rake db:create
rake db:migrate
rake db:seed
```

Starting the server:

```
rails server
```

Opening the application:

```
open http://localhost:3000
```

## Interesting Files:

- [GraphqlController](https://github.com/howtographql/graphql-ruby/blob/master/app/controllers/graphql_controller.rb) - GraphQL controller (api entry point)
- [GraphqlSchema](https://github.com/howtographql/graphql-ruby/blob/master/app/graphql/graphql_schema.rb) - the schema definition
- [Mutations](https://github.com/howtographql/graphql-ruby/blob/master/app/graphql/types/mutation_type.rb) - root mutations
- [Queries](https://github.com/howtographql/graphql-ruby/blob/master/app/graphql/types/query_type.rb) - root queries
- [UserType](https://github.com/howtographql/graphql-ruby/blob/master/app/graphql/types/user_type.rb) - record type
- [VoteType](https://github.com/howtographql/graphql-ruby/blob/master/app/graphql/types/vote_type.rb) - record type
- [LinkType](https://github.com/howtographql/graphql-ruby/blob/master/app/graphql/types/link_type.rb) - record type
- [DateTimeType](https://github.com/howtographql/graphql-ruby/blob/master/app/graphql/types/date_time_type.rb) - scalar type
- [LinksSearch](https://github.com/howtographql/graphql-ruby/blob/master/app/graphql/resolvers/links_search.rb) - complex search resolver and its [tests](https://github.com/howtographql/graphql-ruby/blob/master/test/graphql/resolvers/links_search_test.rb)
- [CreateLink](https://github.com/howtographql/graphql-ruby/blob/master/app/graphql/resolvers/create_link.rb) - mutation and its [tests](https://github.com/howtographql/graphql-ruby/blob/master/test/graphql/resolvers/create_link_test.rb)
- [CreateUser](https://github.com/howtographql/graphql-ruby/blob/master/app/graphql/resolvers/create_user.rb) - mutation and its [tests](https://github.com/howtographql/graphql-ruby/blob/master/test/graphql/resolvers/create_user_test.rb)
- [CreateVote](https://github.com/howtographql/graphql-ruby/blob/master/app/graphql/resolvers/create_vote.rb) - mutation and its [tests](https://github.com/howtographql/graphql-ruby/blob/master/test/graphql/resolvers/create_vote_test.rb)
- [SignInUser](https://github.com/howtographql/graphql-ruby/blob/master/app/graphql/resolvers/sign_in_user.rb) - mutation and its [tests](https://github.com/howtographql/graphql-ruby/blob/master/test/graphql/resolvers/sign_in_user_test.rb)

## Sample GraphQL Queries

```
TODO
```
