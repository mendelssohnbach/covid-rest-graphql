# URL

[Create a GraphQL API Wrapper for your REST API](https://javascript.plainenglish.io/create-a-graphql-api-wrapper-for-your-rest-api-7873c63fcce2)

[github](https://github.com/keonik/covid-graphql/tree/main)

[Covid Act Now API (v2.0.0)](https://apidocs.covidactnow.org/api/)

**apollo-datasource-rest**  
RESTソース周りのキャッシュや他のクラスベースの継承を活用するために使用します。

**graphql**  
API用のクエリ言語であるGraphQLのJavaScriptリファレンス実装

```json
  "devDependencies": {
    "dotenv": "^16.0.0",
    "nodemon": "^2.0.15"
  },
  "dependencies": {
    "apollo-datasource-rest": "^3.5.1",
    "apollo-server": "^3.6.3",
    "graphql": "^16.3.0"
  }
```

[州名一覧表](https://www.americanexpress.com/jp/benefits/product/travel/travel-support/tso/countrycode.html)

```gql
{
  state(stateCode:"OH"){
    state
    counties{
      fips
      county
      population
      metrics{
        testPositivityRatio
      }
      actuals{
        cases
        deaths
      }
    }
  }
}
```
