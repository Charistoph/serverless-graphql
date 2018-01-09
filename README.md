# Test with

* Query
  curl -G 'https://5zy1dahvra.execute-api.us-east-1.amazonaws.com/dev/query' --data-urlencode 'query={greeting(firstName: "Felix")}'

* Mutation
  curl -G 'https://5zy1dahvra.execute-api.us-east-1.amazonaws.com/dev/query' --data-urlencode 'query=mutation {changeNickname(firstName: "Felix", nickname: "TJ")}'
