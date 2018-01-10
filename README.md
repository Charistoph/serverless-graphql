# Get started

* Set AWS IAM credentials
  export AWS_ACCESS_KEY_ID=--------------------
  export AWS_SECRET_ACCESS_KEY==---------------------------------------

* Deploy
  sls deploy -v

# Test with

* Query
  curl -G 'https://5zy1dahvra.execute-api.us-east-1.amazonaws.com/dev/query' --data-urlencode 'query={greeting(firstName: "Felix")}'

* Mutation
  curl -G 'https://5zy1dahvra.execute-api.us-east-1.amazonaws.com/dev/query' --data-urlencode 'query=mutation {changeNickname(firstName: "Felix", nickname: "TJ")}'
